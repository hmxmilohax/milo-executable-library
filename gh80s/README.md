# *Guitar Hero: Rocks the 80's* Patches

## Prototype Debug
The debug executable found in the Project Deluge dump of the game. *Mostly* compatible with a final copy of the game, if the drivers are copied over and an `(unlock_song)` array is created in the disc's songs.dtb. Career will not complete unless all references to `playwithme` are renamed to `freebird`.

## Strum Limit Fix
A patch to kill the 52ms cooldown on strums, causing songs with notes over 18NPS (see: "Green Grass and High Tides" from RB1 or "Trogdor" from GH2) to be unFCable.

## Vanilla
The final, retail executable with no fixes applied.