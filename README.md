# electronhax
The script allows you to attach CheatEngine to any steam game using the same idea as protonhax.
Rather than typing up commands to get the appid, and then supply the path of CE to run inside the same wineprefix
this allows you to have a CLI-GUI to make it faster and easier.

## Credit
This script was inspired by the tech behind ["ProtonHax"](https://github.com/jcnils/protonhax)
Credit to the inital code base and work go [jcnils](https://github.com/jcnils)

## Installation
- Put the `ElectronHax` folder and scripts in any $PATH locaiton

## Uninstall
- Remove the "ElectronHax" folder from your $PATH

## Usage
#### * This will need to be done per-game
1. Open Steam 
2. Right-click any game from your library
3. Select Properties
4. Under General > Launch Options paste `electronhax init %command%`

Once you have that setup launch the game and then in any terminal type `hax` and select the game you want to open CE with.

This can be modified to run any software.

## Setup
- Set the variables for your own environment
 - `STEAM_APPS_DIR` should be where you have your steam library install
 - `LOG_DIR` should be where you want the log output (Optional and mostly used for debugging)
 - `CE_PATH` should be the path + exe to where you have Cheat Engine installed
