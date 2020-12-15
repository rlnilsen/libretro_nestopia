# libretro_nestopia_tetris

Modification of the Nestopia libretro core specifically for use with NES Tetris. A snapshot of the screen (in form of a nametable dump) will be saved in folder 'C:\\nestetris\\' at every Tetris game start and game over. Use in conjunction with [chewie](https://github.com/rlnilsen/chewie) to automatically generate a text file with data from your NES Tetris games.

## How to install

1. Install [RetroArch](https://www.retroarch.com/).
2. Download zip file from [Releases](https://github.com/rlnilsen/libretro_nestopia_tetris/releases).
3. Extract 'nestopia_tetris_libretro.dll' to your RetroArch 'cores' folder.
4. Extract 'nestopia_tetris_libretro.dll' to your RetroArch 'info' folder.
5. Install [chewie](https://github.com/rlnilsen/chewie).

## How to use

1. Start RetroArch and play NES Tetris using the 'Nestopia Tetris' core.
2. Use [chewie](https://github.com/rlnilsen/chewie) to process the generated files in 'C:\\nestetris\\'.
