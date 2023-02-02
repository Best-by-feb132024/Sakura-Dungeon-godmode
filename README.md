# Sakura-Dungeon-godmode
Godmode cheat for Sakura Dungeon. Essentially allows you to crank up Ceri and other party members to absurd power levels.





# Changes

You can pick and chose which ones you use by installing just what's needed.



## Insta capture

Makes the Capture attack cost basically nothing and insta delete anything. Changes the `skills.tsv` file.

|        |   ap cost  | cp cost   |  power   |  hit rate   |   crit  |
|--------|-----|----|-----|-----|-----|
| before | -35 | -1 | 12  | 90  | 30  |
| after  | -5  | -1 | 800 | 200 | 100 |


## Goddess Ceri + Sylvi (+ Yomi in the future?)

*TODO* add Yomi but avoid making the Yomi battles in `level0_chat.rpy` against the op yomi.

*TODO* upload modified actors.tsv

Cranks up Ceri and Sylvi's stats and resists far beyond even any lategame enemies. Adds new abilities to Sylvi. They should be invincable and unstoppable. Changes the `actors.tsv` file. Edit the values in the tsv file as you see fit.


| name           | vit | agi | mnt | str | dex | res | physical | poison | air | fire | ice | shock | skills                              | abilities                   |
|----------------|-----|-----|-----|-----|-----|-----|----------|--------|-----|------|-----|-------|-------------------------------------|-----------------------------|
| Ceri (before)  | 2   | 1   | 1   | 2   | 1   | 2   | 1        | 0      | 0   | 0    | 0   | 0     | guard,standard_sword_slash,sparks   | Capacity,Grappler,Fortitude |
| Ceri (after)   | 32  | 48  | 20  | 40  | 36  | 36  | 2        | 2      | 4   | 3    | 2   | 2     | guard,standard_sword_slash,sparks   | Capacity,Grappler,Fortitude |
| Sylvi (before) | 2   | 3   | 4   | 2   | 3   | 2   | 0        | 2      | 1   | 1    | 1   | 1     | guard,whip_attack,ice_flash,combust | Recovery                    |
| Sylvi (after)  | 30  | 48  | 40  | 20  | 36  | 36  | 2        | 4      | 2   | 1    | 2   | 3     | guard,whip_attack,ice_flash,combust | Recovery,Capacity,Parry     |





## Cheap shop

Makes everything in the shop cost next to nothing. *(optional)* Also modifies `base.rpy` to allow shop to 

*WIP*


## On demand stat boost

Adds a repeatable town event to boost stats

*WIP*


## XP-debug (not reccomended)

New ability that inflates XP gains to level you up every battle. I 

*WIP*


***

# Compatability
Likely conflicts with other mods


# Credits
Modify and use this code however you want without credit. It's a mod for a horribly balanced 6 year old ecchi dungeon crawler that no one plays.
