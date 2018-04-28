# Helix keymap by ayatk
## Usage
1. Clone `qmk/qmk_firmware` and move to qmk_firmware directory.

        git clone https://github.com/qmk/qmk_firmware.git
        cd qmk_firmware

1. Add submodule this repository in qmk_firmware.

        git submodule add https://github.com/ayatk/keymap.git keyboards/helix/rev2/keymaps/ayatk
        
1. Build keymap.

        docker run -e keymap=ayatk -e keyboard=helix --rm -v $('pwd'):/qmk:rw edasque/qmk_firmware
