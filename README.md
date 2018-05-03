# Helix keymap by ayatk
## Usage
1. Clone `qmk/qmk_firmware` and move to qmk_firmware directory.

        git clone https://github.com/qmk/qmk_firmware.git
        cd qmk_firmware

1. Add submodule this repository in qmk_firmware.

        git submodule add https://github.com/ayatk/keymap.git keyboards/helix/rev2/keymaps/ayatk
        
1. Build keymap.

        docker run -e keymap=ayatk -e keyboard=helix --rm -v $('pwd'):/qmk:rw edasque/qmk_firmware

## Layer
1. [Eucalyn](http://eucalyn.hatenadiary.jp/entry/saikyo-interface)

```
,-----------------------------------------.             ,-----------------------------------------.
| ESC  |   1  |   2  |   3  |   4  |   5  |             |   6  |   7  |   8  |   9  |   0  |   `  |
|------+------+------+------+------+------|             |------+------+------+------+------+------|
| Tab  |   /  |   ,  |   .  |   F  |   Q  |             |   M  |   R  |   D  |   Y  |   P  |   -  |
|------+------+------+------+------+------|             |------+------+------+------+------+------|
|   =  |   A  |   O  |   E  |   I  |   U  |             |   G  |   T  |   K  |   S  |   N  |   '  |
|------+------+------+------+------+------+------+------+------+------+------+------+------+------|
| GUI  |   Z  |   X  |   C  |   V  |   W  |   [  |   ]  |   B  |   H  |   J  |   K  |   ;  |   \  |
|------+------+------+------+------+------+------+------+------+------+------+------+------+------|
| Lower| Lower|      | GUI  | Shift| Space|  BS  | Enter| Space| Shift| Alt  | Menu |Lower |Lower |
`-------------------------------------------------------------------------------------------------'
```
