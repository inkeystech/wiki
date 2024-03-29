---
title: posh
description: 
published: true
date: 2023-09-02T08:11:43.887Z
tags: keymap
editor: markdown
dateCreated: 2023-08-19T10:33:53.753Z
---

![Holding teacup with pinkie extended](https://qph.cf2.quoracdn.net/main-qimg-37615fa2111b6d45a66b63b8173cc51b.webp)

Posh is a [taipo](/en/keymaps/taipo) style layout that excludes the pinkies in order to make combos more accurate and long periods of work more comfortable.

## Layout

Similar to taipo, the layout is two mirrored keyboards that are designed to be alternated between for each keypress. Here is the base layout and some things worth noting:

- Space and backspace are swapped
- Makes use of both thumb keys together in combos
- Space and backspace together is sticky shift

```
A N I           I N A
O T E           E T O
    BS SP   SP BS
```

Below is the keymap as viewed from the left hand. The # represents which keys are pressed from the six in the finger cluster. The other columns represent the output when pressed alone or with the outer, inner or both thumb keys.

The order is based loosely on the [Wikipedia Letter Frequency](https://en.wikipedia.org/wiki/Letter_frequency) by English text, with a slight preference to keep combos similar to taipo so I could benefit from my existing practice.


|input|alone|outer|inner|both|
|---|---|---|---|---|
|---  <br>--#|e|E|right|end|
|---  <br>-#-|t|T|down|pgdn|
|#--  <br>---|a|A|esc|del|
|---  <br>#--|o|O|left|home|
|--#  <br>---|i|I|enter|tab|
|-#-  <br>---|n|N|up|pgup|
|-##  <br>---|s|S|,|'|
|---  <br>-##|h|H|.|"|
|-#-  <br>--#|r|R|0|F10|
|##-  <br>---|d|D|1|F1|
|--#  <br>-#-|l|L|2|F2|
|---  <br>#-#|c|C|3|F3|
|---  <br>##-|u|U|4|F4|
|#--  <br>--#|m|M|5|F5|
|--#  <br>#--|w|W|6|F6|
|#-#  <br>---|f|F|7|F7|
|-#-  <br>#--|g|G|8|F8|
|-##  <br>#--|y|Y|9|F9|
|###  <br>---|p|P|+|=|
|---  <br>###|b|B|-|_|
|-#-  <br>#-#|v|V|/|\|
|##-  <br>--#|k|K|;|\||
|--#  <br>##-|j|J|:|*|
|#--  <br>-##|x|X|$|#|
|#--  <br>#-#|q|Q|@|F11|
|-#-  <br>-##|z|Z|&|F12|
|#--  <br>-#-|?|!|^||
|--#  <br>#-#|\`|~|%||
|-#-  <br>-#-|gui|)|(|gui+shift|
|--#  <br>--#|ctrl|]|\[|ctrl+shift|
|#--  <br>#--|alt|}|{|alt+shift|
|#--  <br>##-|ralt|>|<|ralt+shift|
|--#  <br>-##|play/pause|next track|prev track|stop|
|-#-  <br>##-|print|vol up|vol down|mute|
|#-#  <br>--#|insert|bri up|bri down||
|#-#  <br>-#-|layer 0|layer 1|layer 2|layer 3|
|##-  <br>-#-|||||
|##-  <br>#--|||||
|#-#  <br>#--|||||
|-##  <br>-#-|||||
|-##  <br>--#|||||

## Firmware

I'm currently working on QMK firmware here:

https://github.com/dlip/qmk_firmware/tree/dlip/keyboards/chouchou/keymaps/posh

## Contact

.fata1err0r on Discord