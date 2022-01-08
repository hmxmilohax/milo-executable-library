# Milo Executable Library
The Harmonix rhythm game community has taken increasing steps to patch bugs present in the game's code itself--not the scripts as seen in the [Milo Script Library](https://github.com/mariteaux/milo-script-library) sister repo, but the actual game executables.

Further, for a couple games, we have proper debugging builds available to us, as Harmonix would often build debugging functions into the game itself and then patch those functions out on shipping builds.

This repo aims to round up as many of these unofficial bugfixed executables, plus the vanilla shipping and debug executables for comparison, as possible. If the executable requires extra files beyond what's already in the game files, they will be included here.

Interested in this stuff? Join MiloHax, the Discord where a lot of this gets sorted, found, or hacked together: https://discord.gg/TPycZbVeqY

## Testing Status
Unless otherwise noted, all executables have been tested on both console and emulator. Only NTSC builds are featured at current.

Here's a list of which ones have only been tested on emulator:

- GH1 second note fix
- GH1 SP delay fix
- GH1 all patches applied
- RB1 PS2 strum limit fix (we don't have a proper way to rebuild dual-layer discs, so while the patch works, songs likely won't load unless forced into a single ARK part and rebuilt into a malformed single-layer ISO)
- RB2 PS2 strum limit fix (same as with RB1)
- RB2 PS3 TU2 strum limit fix (works when EBOOT.ELF is renamed to EBOOT.BIN and replaced in both the copy on the hard drive and the copy in the original game)

And here's a list of which ones haven't been tested at all:

- LRB strum limit fix

## Contributors
Aside from Harmonix, obviously...

- All strum limit patches, plus all GH1 bugfixes and the HO/PO bugfix for GH2, were contributed by GenericMadScientist.
- Debug executables for GH1, GH2, and GH80's were released as part of the [Project Deluge PS2 lot of March 2021](https://hiddenpalace.org/News/Project_Deluge:_PlayStation_2). Thank you, anonymous game dumper!
- The Amplitude OPM debug executable was found by Carter...somehow.