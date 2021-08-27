# Craftsound Subtitles

To load this pack, you can simply drop a .zip of it in your resource packs folder. It's all ready to go with an en_us translation.

To get it to work, however, you'll need to modify the <a href=https://www.planetminecraft.com/data-pack/craftsound-datapack-all-crafting-come-with-sound/>Craftsound Datapack</a> as follows:
1. Extract the datapack, if you haven't already
2. Open "<code>\data\playbabe\functions\craftsound\sounds\small</code>"
3. Modify all instances of sound events (e.g. "<code>minecraft:block.grass_block.break</code>") to say "<code>minecraft:craftsound.\<categoryname\>[.\<categorynumber\>[.\<soundletter\>]]</code>", without the brackets and greater than/less than symbols.
<br>For example, if the file name is "<code>grass_2</code>" then change the sound event to "<code>minecraft:craftsound.grass.2</code>". If there are multiple events, add a period and a lowercase letter, labeling them alphabetically. (e.g. "<code>minecraft:craftsound.grass.2.a</code>" and "<code>minecraft:craftsound.grass.2.b</code>")<br>
4. Compress again (optional)<br><hr>
Please note that to modify the sounds you want now, you will need to do that in the <code>sounds.json</code> of this pack.<br>
Subtitle translations would be much appreciated, I only speak English.
