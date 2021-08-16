# dwm-relative-controls

## About
This patch allows [dwm](https://dwm.suckless.org) users to move between their tags and to move their windows relative to the currently selected tags.

## Demo
This patch is part of my personal build of [dwm](https://github.com/misobarisic/dwm).
![demo](./demo.gif)

## Installation
Place the .diff file in your dwm source folder and run
``` bash
cd /path/to/dwm
patch < dwm-relative-controls.diff
```

## Default keybindings
| Keybinding |  Action|
|:-----|------:|
| MOD + S  | go to next tag |
| MOD + A | go to previous tag |
| MOD + SHIFT + S  | move window to next tag and go there |
| MOD + SHIFT + A | move window to previous tag and go there |
| MOD + SHIFT + X  | move window to next tag |
| MOD + SHIFT + Y/Z | move window to previous tag |

## Author

**Mišo Barišić**

* Website: https://www.misobarisic.com
* GitHub: [@misobarisic](https://github.com/misobarisic)
* GitLab: [@misobarisic](https://gitlab.com/misobarisic)
