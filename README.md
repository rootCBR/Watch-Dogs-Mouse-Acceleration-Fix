# Mouse Acceleration Fix for Watch Dogs
This mod gets rid of all damping and smoothing the game does on the camera input.\
\
Two variants are available:

## Standalone
A single `dinput8.dll` file to place in the same directory as your game executable.

## Loader
This variant comes with two separate libraries:

### `dinput8.dll`
Allows you to load multiple libraries at the same time.\
To do this, create a `loader.txt` in the same directory as your game executable and list the paths to the library files (*.dll) you want to load in the game.\
\
Works with relative paths.\
Use two backward slashes `\\` for directories.

### `Fixer.dll`
Contains the isolated functionalities of the mod and is to be targeted by the loader.

## Troubleshooting
This mod removes post-processing of the camera input including linearity.\
\
The more sensitive response can lead to "stick-drift"-like behavior when analog sticks of a connected controller are not centered completely. Center the analog stick or unplug the device to prevent this.

Find this mod and many more on the [Watch Dogs Modding](https://discord.gg/watch-dogs-modding-345656208411328514) Discord server.
