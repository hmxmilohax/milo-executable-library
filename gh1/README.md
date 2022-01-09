# *Guitar Hero* Patches

## All Patches Applied
A version of the game with all three of the known GH1 bugs (SP delay, second note needing to be strummed regardless of HOPO status, strum limit) patched out.

## Prototype Debug
The debug executable found in the Project Deluge dump of the game. **This cannot be used with a final copy of GH1!**

## Second Note Fix
A patch to resolve the second note of a song having to be strummed, regardless of its HO/PO status. To patch in the vanilla executable:
```
Offset: 5E960
Change 02 to 01
```

## SP Delay Fix
A patch to resolve the length of time it takes for Star Power to kick in. Previously, pausing was used to make SP activation instantaneous. To patch in the vanilla executable:
```
Offset: 33DE4
Change 04 to 00
```

## Strum Limit Fix
A patch to kill the 52ms cooldown on strums, causing songs with notes over 18NPS (see: "Green Grass and High Tides" from RB1 or "Trogdor" from GH2) to be unFCable. To patch in the vanilla executable:
```
Offset: 15B108
Change 50 42 to 80 3F
```

## Vanilla
The final, retail executable with no fixes applied.
