## MPV-vis

v 2026-11-10-11-08-49

Visualizers for mpv 

- modified: qtbar without text in the middle
- added: spectrum visualiser inspired by vlc spectrum. spectrum is default. to change default change `name` variable in `visualizer.lua`
- add osd with vis name



forked from https://github.com/mfcc64/mpv-scripts

## lua files:

- visualizer.lua - various audio visualization.
- firequalizer.lua - linear phase 15-bands equalizer (this is not graphic, it is automatically used)

## instalation:

- in mpv folder, create folder `scripts`
- copy lua files to `scripts` folder
- You can alterantively copy lua files to `%appdata%/mpv/scripts`, or `.config/mpv/scripts`

### Key bindings

use c key to flip through vis models

use standard f key to go to fullscreen in mpv.

### modify visualizer.lua

- you can modify spectrum values. lower quality if it spectrum takes too much cpu. (It takes a bit more than qt vis)
