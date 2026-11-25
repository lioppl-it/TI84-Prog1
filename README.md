# TI84-Prog1

## TI-84 Plus CE Geometry Dash-style game

Load `GEODASH.8XP.txt` on a TI-84 Plus CE using TI-OS's program editor or a compatible calculator transfer tool.

- Press the **up arrow** to jump.
- Avoid the blocks that approach from the right.
- The score increases as obstacles pass.
- `CLEAR` exits the game.

The source is written for TI-BASIC on the TI-84 Plus CE. It uses the pixel-display commands and a 96-column by 64-row coordinate grid.

## How to check the program

This repository contains TI-BASIC source, not an executable `.8xp` file. VS Code cannot run or simulate the program.

1. Open the TI-84 Plus CE emulator included with an official TI-SmartView CE license, or use a compatible TI-84 emulator.
2. Create a new program in the emulator.
3. Enter the lines from `GEODASH.8XP.txt` as TI-BASIC commands. The emulator's copy/paste or import support may not accept plain text, so manual entry may be required.
4. Run it with `prgmGEODASH` or by selecting the program from the **PRGM** menu.
5. Press the **up arrow** to jump. Press **CLEAR** to exit.

The source can be visually reviewed in VS Code, but only a calculator or emulator can verify TI-BASIC tokenization and execution. Save the emulator program as an actual `.8xp` file before trying to transfer it with TI Connect CE.
