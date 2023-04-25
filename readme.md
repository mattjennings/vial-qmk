# setup
- clone this repo
- [follow steps](https://get.vial.today/docs/porting-to-vial.html) to setup the build environment
    - consder this repo as the vial-qmk repo
    - only follow until you build the example firmware, then come back here

- install [qmk toolbox](https://github.com/qmk/qmk_toolbox)

# editing the config
- config is found in `keyboards/sofle/vial`
- if the keyboard is already flashed, use the vial app to edit keymap

# compiling and flashing
- run `make sofle:vial`
- open QMK toolbox, turn on auto flash
- select `sofle_rev1_vial.hex`
- plug in the sofle keyboard and press the reset button under the OLED screen cover
