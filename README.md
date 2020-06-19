# Minecraft-datapacks
A collection of data packs that I have made for minecraft.

## Contents
[AFK Detector](AFK-Detector)  
[Auto Lag Clearer](Auto-Lag-Clearer)  
[Custom Chair](Custom-Chair)  
[Chest Backpacks](Chest-Backpacks)  
[Coordinate Display](Coordinate-Display)  
[Exploding Arrows](Exploding-Arrows)  
[Extra Recipes](Extra-Recipes)  
[Item Mixing](Item-Mixing)  
[Minecraft Manhunt](Minecraft-Manhunt)  
[Slabs to Blocks](Slabs-to-Blocks)  
[Thru Command](Thru-command)
<br><br><br>
### AFK detector
This datapack will detect if a player is afk. If a player is afk then a message will be displayed in the chat, notifying others that they are afk.  
A player needs to stay still for 30 seconds for the datapack to consider them afk.

[Datapack here](afk_detector.zip)

#### Usage
Make sure the datapack is enabled.  
Then type `/function afk_detect:start` to start the detector.
To stop the detector type `/function afk_detect:stop`.  
To reset the detector type `/function afk_detect:reset`.
<br><br><br>
### Auto Lag Clearer
This datapack will remove all items entites from the world at regular intervals of time in order to reduce lag.

[Datapack here](auto_lag_clearer.zip)

### Usage
Make sure the datapack is enabled.  
Then type `/function auto_lag:start` to start the clearer.  
To stop the clearer type `/function auto_lag:stop`.  
<br><br><br>
### Custom Chair
This datapack will make a chair out of armor stands.

[Datapack here](chair_model.zip)

### Usage
Make sure the datapack is enabled.  
Then type `/function chair_model:get_chair_spawn_egg` to receive a spawn egg.  
Then use the spawn egg. A chair should appear.  
To delete all chairs type `/function chair_model:delete_all_chairs`
<br><br><br>
### Chest Backpacks
This datapack will turn named chests into backpacks/enderchests.

[Datapack here](chest_backpacks.zip)

### Usage
Make sure the datapack is enabled.  
Then type `/function chest_backpacks:start` to start the datapack.  
To stop the datapack type `/function chest_backpacks:stop`.  
To make a backpack, rename a chest in an anvil to 'A', and place that chest at 241 4 -28.  
Rename another chest to 'A' and carry that chest on you.  
When you place down the chest named 'A', you can put items in it, and then destroy the chest.  
When you place down the chest again, all of your items should be inside, with nothing lost.
<br><br><br>
### Coordinate Display
This datapack will display your coordinates at the bottom of your screen.

[Datapack here](coords.zip)

### Usage
Make sure the datapack is enabled.  
Then type `/function coords:start` to start the display.  
To stop the display type `/function coords:stop`.
<br><br><br>
### Exploding Arrows
This datapack will make arrows explode upon impact.

[Datapack here](exploding_arrows.zip)

### Usage
Make sure the datapack is enabled.  
Get a bow and some arrows.  
Fire the arrows.  
If they explode when they hit the ground then all is good.  
To turn this off, disable the datapack.
<br><br><br>
### Extra Recipes
This datapack will add a number of recipes to the game.

[Datapack here](extra_recipes.zip)

### Usage
Make sure the datapack is enabled.  
Have a look through the datapack to see what recipes are there.  
Try out some of the recipes in the game.  
If they work then all is good.  
To remove the extra recipes, disable the datapack.
<br><br><br>
### Item Mixing
This datapack will alow you to mix items by throwing them on the ground.

[Datapack here](item_mixing.zip)

### Usage
Make sure the datapack is enabled.   
Then type `/function item_mixing:giveitems` to receive some items.  
Throw both items on the ground to make a new item.  
If you want to use different items then change what will be given to you in the `giveitems.mcfunction` file.  
Don't change the nbt of the items, only the names of them from redstone and glowstone_dust to something else.
<br><br><br>
### Minecraft Manhunt
This datapack will make a compass point to a player who is tagged with `speedrunner`.
The speedrunner needs to beat the game before the hunter kills them.  
The hunter gets a compass.

[Datapack here](manhunt.zip)

### Usage
Make sure the datapack is enabled.  
To make the compass work, type `/function manhunt:start`.  
To make the compass not work, type `/function manhunt:stop`.
<br><br><br>
### Slabs to Blocks
This datapack will add recipes to allow you to turn slabs back into blocks.

[Datapack here](slabs_to_blocks.zip)

### Usage
Make sure the datapack is enabled.  
Put two slabs into a crating table and see what happens.  
If you get a block out of the slabs then everything is good.
To remove the recipes, disable the datapack.
<br><br><br>
### Thru Command
This datapack will add recipes to allow you to turn slabs back into blocks.

[Datapack here](thru.zip)

### Usage
Make sure the datapack is enabled.  
Type `/trigger thru <add|set> <number>` to be move forward a number of blocks.  
For example:
`/trigger thru add 10` would move you forward 10 blocks.  
`/trigger thru set 50` would move you forward 50 blocks.
The max number of blocks that you can move is 50.
