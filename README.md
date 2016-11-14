#fastcraft
###Purpose
This is supposed to be a faster version of minecraft in that it is intended to have a lot less grinding involved.

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
Cheats and bonus chest on

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

**Another suggestion** for really casual play, you could toggle keeping of inventories by using the command `/gamerule keepInventory true`

##Changes
###Chests
**spawn_bonus_chest**
- Food rolls were doubled (now 6, was 3)
- Chest now includes one purple shulker box
- Chest always includes two villager eggs

*all other chests are the same*
###Entities
**neutral mobs** includes chicken, cow, donkey, horse, llama, mule, mushroom cow, ocelot, pig ,polar bear, rabbit, sheep, snowman, squid, wolf
- Drop rolls doulbed (now 2, was 1)
- Has 1 roll for experience bottles if a player killed the mob

**hostile mobs** includes blaze, cave_spider, creeper, elder guardian, enderman, endermite, ghast, guardian, iron golem, magma_cube, silverfish, skeleton, skelton horse, slime, spider, stray, vindication_illager, wither_skeleton, zombie_horse, zombie_pigman
- Drop rolls doulbed (now 2, was 1)
- Percent chance drops doubled (now 0.05 was 0.025) (applies to wither_skeleton, zombie, zombie_villager)
- Has 2 rolls for experience bottles if the player killed the mob

**ender_dragon**
- Drops 1-3 elytra wings
- Drops dragon head
- Drops 10 experience bottles
- Drops 2 ender chests

**enderman**
- Drops 1-3 enderpearls (was 0-1)
- Has 2 rolls for experience bottles if the player killed the mob

**slime**
- Drop rolls doubled (now 2, was 1)
- Has 1 roll for experience bottles if a player killed the mob

**witch**
- Drop rolls doubled (now 2-6, was 1-3)
- Has 2 rolls for experience bottles if the player killed the mob

**zombie and zombie_villager**
- Rotten flesh drop rate is 1.5x. Drops 0-3 pieces (was 0-2)
- random_chance_with_looting for iron ingot, carrot, and potato was set to 0.05 (was 0.025)
- Has 2 rolls for experience bottles if the player killed the mob

###Ideas/Todo
- Add seeds to zombie?
- Add Woodland and Ocean Exploration Maps to bonus chest (1.11)
- Add map to bonus chest? (like console version)
- Guaranteed stone tools in bonus chest?
- https://www.reddit.com/r/Minecraft/comments/54rlur/small_vanilla_custom_dungeon_chest_loot_pack/
- https://www.reddit.com/r/Minecraft/comments/5cvlxr/paints_better_loot_tables_cleaning_the_junk_out/
- https://www.reddit.com/r/Minecraft/comments/3qou13/loot_tables_ideas_heres_some_of_mine_what_are/
- Reduce coal settings to 30 (now 40, was 20)
- Reduce lapis settings to 4 (now 5, was 1)
