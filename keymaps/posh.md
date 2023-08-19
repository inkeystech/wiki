---
title: Posh
description: 
published: true
date: 2023-08-19T11:41:52.053Z
tags: 
editor: markdown
dateCreated: 2023-08-19T10:33:53.753Z
---

# Posh (work in progress)

Posh is a [taipo](/en/keymaps/taipo) style layout that excludes the pinkies in order to make long periods of work more comfortable.

## Layout

Similar to taipo, the layout is two mirrored keyboards that are designed to be alternated between for each keypress. Here is the base layout, some things worth noting:

- Space and backspace are swapped
- Makes use of both thumb keys together in combos
- Space and backspace together is sticky shift

```
A N I           I N A
O T E           E T O
    BS SP   SP BS
```

Below is the keymap as viewed from the left hand. The # represents which keys are pressed from the six in the finger cluster. The other columns represent the output when pressed alone or with the outer, inner or both thumb keys.


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
|-#-  <br>#-#|v|V|/|\|
|--#  <br>##-|k|K|;|\||
|##-  <br>--#|j|J|:|*|
|#--  <br>-##|x|X|$|#|
|-#-  <br>-##|q|Q|@|F11|
|-##  <br>-#-|z|Z|&|F12|
|#--  <br>-#-|?|!|\`|~|
|-#-  <br>-#-|gui|)|(|gui+shift|
|--#  <br>--#|ctrl|]|\[|ctrl+shift|
|#--  <br>#--|alt|}|{|alt+shift|
|-#-  <br>##-|ralt|>|<|ralt + shift|
|--#  <br>-##|play/pause|next track|prev track|stop|
|-##  <br>--#|^|vol up|vol down|print|
|--#  <br>#-#|%|bri up|bri down|insert|
|#-#  <br>--#|layer 0|layer 1|layer 2|layer 3|

## Firmware

I'm currently working on QMK firmware here:

https://github.com/dlip/qmk_firmware/tree/posh/keyboards/chouchou/keymaps/taipo