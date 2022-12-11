# DIM
Destiny Item Manager Wish lists

# FORMAT
Examples:
- chad (PVE): ?-Tier. MW: ?. Mod: ?
- chad (PVE): ?-Tier. MW: ?. Mod: ? GODROLL

Metadata
- Tiers: S, A, B, C, F 
- Masterwork: Range, Reload, Stability, etc.
- Mod: backup mag, targetting, etc.


# HOW-TO
1. Lookup perk name
    - https://www.light.gg/db/items/<perk # here>
2. Lookup item
    - https://d2gunsmith.com/w/<item # here>
3. Create wishlist reference links
    - https://destinyitemmanager.fandom.com/wiki/Creating_Wish_Lists
4. Create block comments

//notes:These are notes that will apply to everything that immediately follows
dimwishlist:item=2326716489&perks=202670084,3142289711,2117683199,47981717
dimwishlist:item=2326716489&perks=3250034553,3142289711,2117683199,47981717
dimwishlist:item=2326716489&perks=1467527085,3142289711,2117683199,47981717

// ^ the blank line above will end the "block"

# EXTERNAL RESOURCES
Default rolls
- https://raw.githubusercontent.com/48klocs/dim-wish-list-sources/master/voltron.txt

D2Checklist god rolls
- https://gist.github.com/dcaslin/e614cf030f14c41e07c87f6f7f08d465

Player vs. Enemies rolls
- https://github.com/Adamsdown-Boy/destiny-rolls/blob/main/player-versus-enemies-rolls/ep37-s18-festival-of-the-lost-reprised-weapons.txt

# Roll types

## Mandatory roll types tags (one of these must be used)
- pve - rolls suggested for PvE content
- pvp - rolls suggested for PvP content

## Optional roll types tags - these are judgements made against each individual weapon, not whether that subtype is considered S-Tier for that activity
- pve-god - best combination of perks for a particular use case in PvE. Absence is implied pve-good and indicates traits are first-choice but barrel/mag perks not optimal, or that while the roll is good, there are better traits available)
- pvp-god - best combination of perks for a particular use case in PvP. Absence is implied pvp-good and  indicates traits are first-choice but barrel/mag perks not optimal, or that while the roll is good, there are better traits available)

# Use cases

## Mandatory PvE use case tags (at least one of these must be used)
- pve-minor - perks aimed at enemies covered by Minor Spec mod description. Usually Primary red-bar add clear.
- pve-major (incl burst damage) - perks aimed at enemies covered by Major Spec mod description. Ususally Special or Power weapons for quick burst DPS against a target, but can also include Primary weapons
- pve-boss (incl sustained damage) - perks aimed at enemies covered by Boss Spec mod description. Usually Special or Power weapons for sustained DPS in a damage phase either on their own or in combination with another weapon in the loadout.

## Optional PvE use case tags 
- pve-endgame - suggested perks for use in end-game (primarily power-capped) activities. Perks generally don't need a weapon kill to proc. Absence  is implied pve-general and indicates traits good for general content, but generally require a kill to activate.
- pve-champion (good perk combinations) - specific perk combinations for stunning anti-Barrier, anti-Overload, or anti-Unstoppable champions
- pve-solo - combination of perks that are useful for solo activities such as Lost Sectors or solo runs through activities for seasonal triumphs

Source: https://github.com/Adamsdown-Boy/destiny-rolls/blob/main/barrels-mags-groupings.txt

# PERKS
- 839105230 | Arrowhead Brake
- 3250034553 | hammer-forged rifling
- 3230963543 | flared-magwell
- 1774574192 | osmosis
- 4104185692 | frenzy
- 384158423 | MW: Stability
- 2697220197 | MW: Range
- 1482024992 | smallbore
