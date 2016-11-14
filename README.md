#fastcraft
###Purpose
make a new world with dungeons set to 100
all spawn rates on ores x2 except for diamond which is x5
use bonus chests

what is in here is modified loot tables
almost all drops from mobs are doubled. all percent chance drops are doubled (2.5% chance has been increased to 5% chance)
bonus chests have two spawn villager eggs in them

put the loot table in \.minecraft\saves\WORLDNAME\data\loot_tables

if someone else is joining in, to give them a bonus chest use the following command
`/give PLAYER chest 1 0 {BlockEntityTag:{LootTable:"minecraft:chests/spawn_bonus_chest"}}`

https://www.reddit.com/r/Minecraft/comments/4j6t7f/how_to_bonus_chest_for_each_player_on_a_server/

other ideas
starting difficulty could be easy and then increase it as time goes on
maybe increase to normal when you have full iron armor or something


enderdragon
`/entitydata @e[type=EnderDragon,tag=!processed] {DeathLootTable:"custom:enderdragon",Tags:["processed"]}`

###Recommended World Options
**World Type:** Customized

Setting | Value | Change
--- | --- | ---
Dungeon Count | 100 | (default: 7)
Coal Ore | 40 | (default: 20)
Iron Ore | 40 | (default: 20)
Gold Ore | 4 | (default: 2)
Redstone Ore | 16 | (default: 8)
Diamond Ore | 5 | (default: 1)
Lapis Lazuli Ore | 5 | (default: 1)

##Changes
###Chests
**spawn_bonus_chest**
- Food rolls were doubled (now 6, was 3)
- Chest always includes two villager eggs

*all other chests are the same*
###Entities
**neutral mobs** includes chicken, cow, horse, mushroom cow, ocelot, pig ,polar bear, rabbit, sheep, squid, stray, wolf
- Drop rolls doulbed (now 2, was 1)
- Has 1 roll for experience bottles if a player killed the mob

**hostile mobs** includes blaze, creeper, elder guardian, enderman, endermite, ghast, guardian, iron golem, magma cube, silverfish, skeleton, skelton horse, slime, spider, wolf, wither skeleton, zombie, zombie horse, zombie pigman
- Drop rolls doulbed (now 2, was 1)
- Percent chance drops doubled (now 0.5 was 0.25)
- Has 2 rolls for experience bottles if the player killed the mob
