# CORNE ZMK WITH DONGLE 

If you use Corne, Nijuni, Dao or any other keyboard with corne-like matrix you may clone this repo
After that, go to "Actions" tab in github and enable it

You will get archive with firmware

If you use dongle, load "corne_central_dongle-nice-nano-v2-zmk.uf2" if you use nice!nano controller for dongle
Or "corne_central_dongle-seeeduino_xiao_ble-zmk.uf2" if you use xiao for dongle
Also, if you use dongle load "peripheral" uf2 for left and right parts

If you don't use Dongle, than load "corne_central_left-nice_nano_v2-zmk.uf2" on the left part
and "corne_peripheral_right-nice_nano_v2-zmk.uf2" for the right part

For generate keymap-picture:
https://keymap-drawer.streamlit.app/?zmk_url=https%3A%2F%2Fgithub.com%2Frk108%2Fcorne-keyboard-layout%2Fblob%2Fmain%2Fconfig%2Fcorne.keymap

![1](imgs/my_keymap.svg)
