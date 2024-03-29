---
title: taipo
description: A (primarily) two-handed layout focused on consistency, rhythm, and generality
published: true
date: 2024-03-13T02:23:41.107Z
tags: 
editor: markdown
dateCreated: 2022-05-02T17:52:18.590Z
---

# Basics
Taipo is a two-handed chording system that can be used one-handed (based on your firmware setup) because it is simply two, full, mirrored keyboards that you can 100% alternate between. It uses 2 keys per finger, 10 keys per hand, 20 keys total. All characters are single chords involving 3 or fewer keys and nothing requires holds except for modifiers (for two handed). There is zero consecutive hand or finger usage when using it with two hands and Taipo's biggest benefit is its consistent flow and ease of access to all symbols. Here are some visual aides (yes I am NotGate: I made the ISRT and Whorf layouts): 
Typing Demonstration: https://www.youtube.com/watch?v=FI8Imy3krnA

**Chord Layout:**

This is a 2x4 set of keys and combos from the perspective of the right hand.
Keys in a color, when pressed simultaneously, produce the first row of chars of that color.
The 2nd and 3rd rows are produced by adding a thumb key. The 2 thumb keys are referred to as "inner" and "outer" thumb keys, the "inner" one is closest to your palm. When pressed individually, the inner thumb key is space and the outer one is backspace.
Ex: Top index + top middle is y and adding a thumb key gives you Y or 5.

![taipo.png](/taipo.png)

**Alternative Diagram:**

![taipo_left_right_v3.png](/taipo_left_right_v3.png)

# Firmware

If you have a programmable keyboard these examples can help you set it up for Taipo

## QMK

- https://github.com/dlip/qmk_firmware/blob/chouchou/users/dlip/taipo.md
- https://github.com/hunner/keyboard-layouts/blob/personal/keyboards/gboards/georgi/taipo/keymap.c

## KMK

- https://github.com/dlip/chouchou/tree/main/firmware/kmk

## ZMK

- https://github.com/dlip/zmk-taipo

# Keyboards

Custom keyboards designed specifically for Taipo

- [UT22](https://github.com/bubbleology/UT22)
- [Chouchou](https://github.com/dlip/chouchou)

# History
Taipo's name comes from taiko+typo. Taiko is the rhythm game that inspired my creation of Taipo, and I even made a typing game a couple years ago that is essentially Taiko but with letters. The original Taipo was not at all well optimized for English and I eventually stopped using it even though I averaged around 90-100 WPM on it. I have since made a couple different mappings using machine generation or the advice of friends. While the chord map I posted above may not be perfect, it is more than good enough for comfortable English writing and coding at decent speed.
Game: https://www.youtube.com/watch?v=SO6AJb3AzhY
Typing Demonstration: https://www.youtube.com/watch?v=A_NVzUSEAxM

# FAQ 
## Why is X on Y chord??
Basically no one can agree on what chords feel better than what. It's preference. Taipo is more of an idea than a specific chord map. I will probably change how I do things like direction keys, function keys, mods, etc. to what ends up making the most sense to me. If you end up finding this system interesting, feel free to mess around with any aspect of it you like.
## Is it hard to learn?
Chords are pretty quick to memorize for me - not much slower than a normal layout. What makes taipo hard at first is the full alternation, since you could be starting a word on either hand, spacing with either thumb, and are essentially learning how to type every word two ways. I have found that the brain gets used to this as it will with anything. A good way to speed up the process is to practice a wordlist of 2 length words with or without a mix of 3 length words. It will quickly just feel like typing and no longer be confusing.
## How fast can you get on it?
I got to 100 WPM on simple English in a couple weeks of learning this version of Taipo (video above) but am still around 60-70 on more complex English since starting a month ago. I think of the speed cap as being entirely mental. Alternating fast enough to hit 150 WPM or higher will be doable for me within the next year or so, which is good for a system which has such an emphasis on consistency and symbol accessibility.
## Why am I inaccurate on the layers?
Rememeber, Taipo has NO holding for any symbols or characters. The "layers" are more of a conceptual term to frame how you think about the system. Everything is still typed simultaneously as one combo. 

# Showcase
I enjoy Taipo for it's generality and consistency. It is probably the best system (imo) for long, complex, accurate tests like this: 
![ascii](https://media.discordapp.net/attachments/962807598665576478/962899525792579594/unknown.png?width=741&height=663)
However, I have still been able to hit 110+ WPM on simple English: 
![english](https://cdn.discordapp.com/attachments/962807598665576478/966177493717483580/unknown.png)

# Contact
whorf#7361