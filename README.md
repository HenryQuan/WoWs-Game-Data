# WoWs Game Data (0.9.4.0)
Extract some game data from World of Warships. There are also some other data that are collected by me.

## Modernizations
It includes all modernization (upgrades, legendary upgrades and special upgrades).

## Ship Additional
Some additional information for all ships that don't exist in the official API.

- Shell sigma
- HE penetration value
- SAP penetration value
- Ship consumables
- AP shell information for calculating the penetration value
- Indicate whether this is a paper ship
- Total battles (wows-numbers.com/ships/, dataProvider.ships)

### AP Penetration
- [reddit post](https://www.reddit.com/r/WorldOfWarships/comments/560yg2/wows_ballistic_model_penetration/)
- [matlab version](https://pastebin.com/1NEwkf7R)
- [kotlin version](https://github.com/EdibleBug/WoWSFT-Kotlin/blob/5d4ce2d4ffb722c010b265ce3c39417eddd009c7/WoWSFT-Data/src/main/kotlin/WoWSFT/utils/PenetrationUtils.kt) by wowsft
- [python version](https://github.com/HenryQuan/WoWs-Game-Data/blob/master/ap_pen.py) by me
- [dart version]() by me (coming soon)

## Ship consumables
All available ship consumables in the game. 

## Removed ships
A list of ships that are changed due to rework or removed in the game with tier and name.

# Icons
Now, it only has consumable icons and they will be added to WoWs Info later. 

# Extra
Extra data that might be interesting to see.
## Long range torpedoes (>= 12km)
A list of torpedoes which are more than 12km in range. There are some interesting ones that are not available in game.

## Fast reloading guns (< 4sec)
## Slow reloading guns (> 30sec)

## Big guns (>= 410mm)
## Big guns (< 120mm)
