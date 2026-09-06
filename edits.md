Aside from
* patches.h
* config.mk

I've also edited some minor details in
* config.h
- boxdraw from 0 to 1
- boxdraw_bold from 0 to 1
- cursorshape from 2 to 4
- "dmenu" to "rofi -dmenu -p 'URLs: '" in *openurlcmd
- "open" to "xdg-open" in *openurlcmd
- zoom 1 keybind from XK_Prior to XK_plus
- zoom -1 keybind from XK_Next to XK_underscore
- zoomreset keybind from XK_Home to XK_parenright
- "open" to 'xdg-open' in *openurlcmd (might be uneeded)

* iso14755.h
- "dmenu" to "rofi -dmenu -w \"$WINDOWID\" -p codepoint: </dev/null" in #define ISO14755CMD

shell
```sh
clear && s make clean install
```
