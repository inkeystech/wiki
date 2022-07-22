---
title: ardux
description: General documentation for the ardux keymap
published: true
date: 2022-07-22T16:28:59.859Z
tags: ardux, keymap, comingsoon
editor: markdown
dateCreated: 2022-04-20T14:58:35.235Z
---

# What is ardux?

ardux is a keyboard layout designed to be used one handed with as few as 8 keys or as many as 36 keys or two handed. The layout is setup to be a consistent way to type one handed that scales up or down based on need, environment and more.

ardux aims to facilitate one handed typing (mobile needs, physical needs, etc) while also helping users to be efficient (>50wpm is possible one handed) as typists, even if they only use one hand for typing. The layout can be ultra-mobile (only 8 keys) or 'desk sized' (16-18 keys) or a full one _or_ two handed layout (32-36 keys).

## ardux has three major forms

- **standard ardux**: 8 keys and ultra mobile and ultra accessible. this is fundamental form of ardux and is available in _all_ ardux layouts ; if you're looking for mobile or general one handed typing, this is the form to look into
- **big ardux**: 16-18 keys and designed to be a one handed desk keyboard layout ; it allows for easier typing of symbols and use of mod keys ; if you do a lot of typing, copy editing, programming or IT work, this is the form to look into
- **40% ardux**: a full 40% layout that defaults to big ardux ; this form will let you flip between big ardux and a standard 40% layout that uses ardux to fill in any 'gaps' that are common with 40% layouts ; if you want to alternate between one and two handed typing, this is the form to look into

## Additional Information

Below you'll find additional details about the ardux layout, including a full overview of the layout and its three forms. We have a Discord at [https://discord.gg/fGUjnUuAVQ](https://discord.gg/fGUjnUuAVQ) if you'd like to get in touch directly.

Feedback via Discord is welcome.

# Supported Keyboards

ardux is available for a number of keyboards. We currently have both [zmk](https://zmkfirmware.dev/) and [qmk](https://qmk.fm/) ports available. These ports include support for different keyboards. Please check either the [zmk-ardux](https://github.com/arduxio/zmk-ardux/) or [qmk-ardux](https://github.com/arduxio/qmk-ardux) release pages for current keyboard support.

# Source Code

All source code is available on GitHub at [https://github.com/arduxio/](https://github.com/arduxio/)

# Remixes

If you see a remix for ardux, it means a user has taken the ardux sources and made customizations using various bits of code we have setup to allow overriding the layout defaults [more] easily. The ardux source code repos have details on how to setup and get going with remixes.

We _encourage_ users of ardux to change the layout if desired and make it their own.

If you have a remix, we welcome posts about how you've remixed on our Discord.

A list of remixes that have been posted to Discord is also available [here](/keymaps/ardux/remixes)

Please note: you will need to compile the appropriate keyboard firmware in order to create a remix and we have found there is a bit of a learning curve to get going with remixes. We work to minimize the learning curve but have not found a way to improve the situation further yet.

# Layout: Conventions

## Single Taps

`Single Taps` are when you simply tap the indicated key.

## Hold Taps

`Hold Taps` are when you tap and hold the key down. Like you'd do for `Shift` on a traditional keyboard.

## Combos

`Combos` are when you tap multiple keys at the same time. Combos are a key feature of ardux and you'll be pressing multiple keys at the same time to type letters, symbols, etc. In the diagrams you'll want to press all of the indicated keys at the same time for the action to register.

### Tables

We use tables to create an illustrative grid of what functions are mapped to which keys.

We also use tables to illustrate which keys to press to activate a combo.

### _Italic_ function names

We use _italics_ to denote a key / function that is _optional_ for inclusion on a physical keyboard. There are a number of keyboard options available in similar sizes. Due to clustering of keyboard sizes, the big and 40% ardux layouts make certain functions _optional_ to be compatible with more keyboards.

### Subscripts

We use subscripts to denote secondary functions assigned to keys. If there is a `x` preceeding a number then `=` and a value ; it means you tap that key the number of times and youll get the value after the `=`. We have setup multi-tap functions for some keys.

We also use subscripts with an `H` at the start. This means to hold the key to get the shown function. We also have setup hold-tap functions for some keys.

## Key Icons

We use the `⚪` symbol to denote a key that is _not_ pressed and a `⚫` symbol to denote a pressed key.

We also use the `⚪` symbol to denote a key that is _not_ mapped to a function.

We use the `🔘` symbol to denote a key is _held_ to activate a layer so that another key may be pressed.

# Layout: Standard ardux (8 key)

This is the standard form of ardux. This layout is 100% present in both big ardux and 40% ardux.

# Left Handed

## Left Layer Activation (Hold)

| C1                    | C2  | C3  | C4                            |
| --------------------- | --- | --- | ----------------------------- |
| Activate Number Layer | ⚪  | ⚪  | Activate Parentheticals Layer |
| Activate Custom Layer | ⚪  | ⚪  | Activate Symbol Layer         |

## Global Combos

| Action                  | Left                 |
| ----------------------- | -------------------- |
| Space                   | ⚪⚪⚪⚪<br>⚫⚫⚫⚫ |
| Enter                   | ⚪⚪⚪⚫<br>⚪⚪⚪⚫ |
| Tab                     | ⚪⚫⚫⚫<br>⚫⚪⚪⚪ |
| Backspace               | ⚪⚪⚫⚪<br>⚪⚪⚪⚫ |
| Forward Delete          | ⚪⚪⚫⚪<br>⚪⚫⚪⚪ |
| Shift                   | ⚫⚫⚫⚪<br>⚪⚪⚪⚫ |
| Shift Lock              | ⚪⚪⚫⚪<br>⚪⚪⚫⚪ |
| Caps Lock               | ⚪⚪⚪⚫<br>⚫⚫⚫⚪ |
| Control                 | ⚫⚪⚪⚪<br>⚪⚪⚪⚫ |
| Alt                     | ⚫⚪⚪⚪<br>⚪⚫⚪⚪ |
| GUI                     | ⚫⚪⚪⚪<br>⚪⚪⚫⚪ |
| Escape                  | ⚪⚪⚫⚫<br>⚫⚪⚪⚪ |
| Navigation Layer        | ⚪⚪⚫⚪<br>⚪⚫⚪⚫ |
| Mouse Layer             | ⚪⚫⚪⚫<br>⚪⚪⚫⚪ |
| BT Layer                | ⚫⚪⚪⚫<br>⚫⚪⚪⚫ |
| Clear Bluetooth Profile | ⚪⚫⚫⚪<br>⚪⚫⚫⚪ |

## Default/Base Layer Actions

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| S   | T   | R   | A   |
| O   | I   | Y   | E   |

_Alphabetically Sorted_

| Action | Left                 |
| ------ | -------------------- |
| A      | ⚪⚪⚪⚫<br>⚪⚪⚪⚪ |
| B      | ⚪⚪⚪⚪<br>⚫⚪⚪⚫ |
| C      | ⚪⚪⚪⚪<br>⚪⚪⚫⚫ |
| D      | ⚪⚫⚫⚫<br>⚪⚪⚪⚪ |
| E      | ⚪⚪⚪⚪<br>⚪⚪⚪⚫ |
| F      | ⚪⚪⚫⚫<br>⚪⚪⚪⚪ |
| G      | ⚪⚫⚫⚪<br>⚪⚪⚪⚪ |
| H      | ⚪⚪⚪⚪<br>⚪⚫⚪⚫ |
| I      | ⚪⚪⚪⚪<br>⚪⚫⚪⚪ |
| J      | ⚫⚫⚪⚪<br>⚪⚪⚪⚪ |
| K      | ⚪⚪⚪⚪<br>⚫⚪⚫⚪ |
| L      | ⚪⚪⚪⚪<br>⚪⚫⚫⚫ |
| M      | ⚪⚪⚪⚪<br>⚫⚫⚫⚪ |
| N      | ⚪⚪⚪⚪<br>⚫⚫⚪⚪ |
| O      | ⚪⚪⚪⚪<br>⚫⚪⚪⚪ |
| P      | ⚪⚪⚪⚪<br>⚫⚫⚪⚫ |
| Q      | ⚫⚫⚪⚫<br>⚪⚪⚪⚪ |
| R      | ⚪⚪⚫⚪<br>⚪⚪⚪⚪ |
| S      | ⚫⚪⚪⚪<br>⚪⚪⚪⚪ |
| T      | ⚪⚫⚪⚪<br>⚪⚪⚪⚪ |
| U      | ⚪⚪⚪⚪<br>⚪⚫⚫⚪ |
| V      | ⚫⚪⚫⚪<br>⚪⚪⚪⚪ |
| W      | ⚫⚪⚪⚫<br>⚪⚪⚪⚪ |
| X      | ⚫⚫⚫⚪<br>⚪⚪⚪⚪ |
| Y      | ⚪⚪⚪⚪<br>⚪⚪⚫⚪ |
| Z      | ⚫⚫⚫⚫<br>⚪⚪⚪⚪ |
| ,      | ⚪⚪⚪⚫<br>⚪⚫⚪⚪ |
| !      | ⚪⚫⚪⚪<br>⚪⚫⚪⚪ |
| .      | ⚪⚪⚪⚫<br>⚪⚪⚫⚪ |
| '      | ⚪⚪⚪⚫<br>⚪⚫⚫⚪ |
| /      | ⚪⚪⚪⚫<br>⚫⚪⚪⚪ |

_Key Sorted:_

This list is sorted in this order:

1. Number of presses
2. Grouped by pattern if possible
3. Keys pressed, top left to bottom right

Spaces are left for open keys, for pattern familiarization.

| Action | Left                 | Notes |
| ------ | -------------------- |- |
| S      | ⚫⚪⚪⚪<br>⚪⚪⚪⚪ | |  
| T      | ⚪⚫⚪⚪<br>⚪⚪⚪⚪ | |
| R      | ⚪⚪⚫⚪<br>⚪⚪⚪⚪ | |
| A      | ⚪⚪⚪⚫<br>⚪⚪⚪⚪ | |
| O      | ⚪⚪⚪⚪<br>⚫⚪⚪⚪ | |
| I      | ⚪⚪⚪⚪<br>⚪⚫⚪⚪ | |
| Y      | ⚪⚪⚪⚪<br>⚪⚪⚫⚪ | |
| E      | ⚪⚪⚪⚪<br>⚪⚪⚪⚫ | |
| J      | ⚫⚫⚪⚪<br>⚪⚪⚪⚪ | |
| G      | ⚪⚫⚫⚪<br>⚪⚪⚪⚪ | Top two teeth, Gums |
| F      | ⚪⚪⚫⚫<br>⚪⚪⚪⚪ | Top of an F |
| N      | ⚪⚪⚪⚪<br>⚫⚫⚪⚪ | One less than M|
| U      | ⚪⚪⚪⚪<br>⚪⚫⚫⚪ | Top of the U|
| C      | ⚪⚪⚪⚪<br>⚪⚪⚫⚫ | Bottom of the C|
| V      | ⚫⚪⚫⚪<br>⚪⚪⚪⚪ | Like the top of the V |
| K      | ⚪⚪⚪⚪<br>⚫⚪⚫⚪ | Like the bottom of the K |
| H      | ⚪⚪⚪⚪<br>⚪⚫⚪⚫ | Like the bottom of an h|
| W      | ⚫⚪⚪⚫<br>⚪⚪⚪⚪ | Like the top corners of a W |
| B      | ⚪⚪⚪⚪<br>⚫⚪⚪⚫ | Two holes, on bottom |
| X      | ⚫⚫⚫⚪<br>⚪⚪⚪⚪ | It's like Z, but less keys|
| D      | ⚪⚫⚫⚫<br>⚪⚪⚪⚪ | Opposite of Low, "Down Low". Like L but on top.|
| M      | ⚪⚪⚪⚪<br>⚫⚫⚫⚪ | One more than N|
| L      | ⚪⚪⚪⚪<br>⚪⚫⚫⚫ | Like the long bottom of an L |
| Q      | ⚫⚫⚪⚫<br>⚪⚪⚪⚪ | |
| P      | ⚪⚪⚪⚪<br>⚫⚫⚪⚫ | |
| Z      | ⚫⚫⚫⚫<br>⚪⚪⚪⚪ | |
| !      | ⚪⚫⚪⚪<br>⚪⚫⚪⚪ | |
| /      | ⚪⚪⚪⚫<br>⚫⚪⚪⚪ | |
| .      | ⚪⚪⚪⚫<br>⚪⚪⚫⚪ | |
| ,      | ⚪⚪⚪⚫<br>⚪⚫⚪⚪ | |
| '      | ⚪⚪⚪⚫<br>⚪⚫⚫⚪ | |

## Parentheticals Layer Actions

To activate the parentheticals layer, hold `A`
| Key | Right                |
| --- | -------------------- |
| A   | ⚪⚪⚪🔘<br>⚪⚪⚪⚪ |

**Table View:**

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| {   | (   | )   | ⚫  |
| }   | [   | ]   | ⚪  |

**List View:**

| Character | Left                 |
| --------- | -------------------- |
| {         | ⚫⚪⚪🔘<br>⚪⚪⚪⚪ |
| (         | ⚪⚫⚪🔘<br>⚪⚪⚪⚪ |
| )         | ⚪⚪⚫🔘<br>⚪⚪⚪⚪ |
| }         | ⚪⚪⚪🔘<br>⚫⚪⚪⚪ |
| [         | ⚪⚪⚪🔘<br>⚪⚫⚪⚪ |
| ]         | ⚪⚪⚪🔘<br>⚪⚪⚫⚪ |

## Number Layer Actions

To activate the number layer, hold `S`
| Key | Right                |
| --- | -------------------- |
| S   | 🔘⚪⚪⚪<br>⚪⚪⚪⚪ |

**Table View:**

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| 🔘  | 3   | 2   | 1   |
| ⚪  | 6   | 5   | 4   |

**List View:**

| Character | Left                 |
| --------- | -------------------- |
| 1         | 🔘⚪⚪⚫<br>⚪⚪⚪⚪ |
| 2         | 🔘⚪⚫⚪<br>⚪⚪⚪⚪ |
| 3         | 🔘⚫⚪⚪<br>⚪⚪⚪⚪ |
| 4         | 🔘⚪⚪⚪<br>⚪⚪⚪⚫ |
| 5         | 🔘⚪⚪⚪<br>⚪⚪⚫⚪ |
| 6         | 🔘⚪⚪⚪<br>⚪⚫⚪⚪ |
| 7         | 🔘⚪⚫⚫<br>⚪⚪⚪⚪ |
| 8         | 🔘⚫⚫⚪<br>⚪⚪⚪⚪ |
| 9         | 🔘⚪⚪⚪<br>⚪⚪⚫⚫ |
| 0         | 🔘⚪⚪⚪<br>⚪⚫⚫⚪ |

## Custom Layer Actions

To activate the custom layer, hold `O`
| Action | Right                |
| ------ | -------------------- |
| O      | ⚪⚪⚪⚪<br>🔘⚪⚪⚪ |

**Table View:**

| C1  | C2          | C3           | C4          |
| --- | ----------- | ------------ | ----------- |
| ⚪  | Volume Up   | Insert       | Mute        |
| ⚪  | Volume Down | Print Screen | Right Shift |

**List View:**

| Character    | Left                  |
| ------------ | --------------------- |
| Volume Up    | ⚪⚫⚪⚪<br>🔘⚪⚪⚪ |
| Insert       | ⚪⚪⚫⚪<br>🔘⚪⚪⚪ |
| Mute         | ⚪⚪⚪⚫<br>🔘⚪⚪⚪ |
| Volume Down  | ⚪⚪⚪⚪<br>🔘⚫⚪⚪ |
| Print Screen | ⚪⚪⚪⚪<br>🔘⚪⚫⚪ |
| Right Shift  | ⚪⚪⚪⚪<br>🔘⚪⚪⚫ |

## Symbol Layer Actions

To activate the symbol layer, hold `E`

| Action | Right                |
| ------ | -------------------- |
| E      | ⚪⚪⚪⚪<br>⚪⚪⚪🔘 |

**Table View:**

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| \`  | ;   | \   | !   |
| =   | -   | ?   | ⚫  |

**List View:**

| Character | Left                  |
| --------- | --------------------- |
| \`        | ⚫⚪⚪⚪<br>⚪⚪⚪🔘 |
| ;         | ⚪⚫⚪⚪<br>⚪⚪⚪🔘 |
| \         | ⚪⚪⚫⚪<br>⚪⚪⚪🔘 |
| !         | ⚪⚪⚪⚫<br>⚪⚪⚪🔘 |
| =         | ⚪⚪⚪⚪<br>⚫⚪⚪🔘 |
| -         | ⚪⚪⚪⚪<br>⚪⚫⚪🔘 |
| ?         | ⚪⚪⚪⚪<br>⚪⚪⚫🔘 |

## Mouse Layer Actions

To toggle the Mouse layer, tap `T Y A`

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| ⚪  | ⚫  | ⚪  | ⚫  |
| ⚪  | ⚪  | ⚫  | ⚪  |

_Actions_

| C1         | C2       | C3   | C4       |
| ---------- | -------- | ---- | -------- |
| Wheel Up   | Button 2 | Up   | Button 1 |
| Wheel Down | Left     | Down | Right    |

## Navigation Layer Actions

To toggle the Navigation layer, tap `R I E`

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| ⚪  | ⚪  | ⚫  | ⚪  |
| ⚪  | ⚫  | ⚪  | ⚫  |

_Actions_

| C1        | C2   | C3   | C4    |
| --------- | ---- | ---- | ----- |
| Page Up   | Home | Up   | End   |
| Page Down | Left | Down | Right |

## Bluetooth Layer Actions

To toggle the Bluetooth layer, tap `S O A E`

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| ⚫  | ⚪  | ⚪  | ⚫  |
| ⚫  | ⚪  | ⚪  | ⚫  |

_Actions_

| C1         | C2        | C3        | C4        |
| ---------- | --------- | --------- | --------- |
| BT Output  | Profile 3 | Profile 2 | Profile 1 |
| USB Output | Profile 6 | Profile 5 | Profile 4 |

# Right Handed

## Right Layer Activation (Hold)

| C1                            | C2  | C3  | C4                    |
| ----------------------------- | --- | --- | --------------------- |
| Activate Parentheticals Layer | ⚪  | ⚪  | Activate Number Layer |
| Activate Symbol Layer         | ⚪  | ⚪  | Activate Custom Layer |

## Global Combos

| Action                  | Right                |
| ----------------------- | -------------------- |
| Space                   | ⚪⚪⚪⚪<br>⚫⚫⚫⚫ |
| Enter                   | ⚫⚪⚪⚪<br>⚫⚪⚪⚪ |
| Tab                     | ⚫⚫⚫⚪<br>⚪⚪⚪⚫ |
| Backspace               | ⚪⚫⚪⚪<br>⚫⚪⚪⚪ |
| Forward Delete          | ⚪⚫⚪⚪<br>⚪⚪⚫⚪ |
| Shift                   | ⚪⚫⚫⚫<br>⚫⚪⚪⚪ |
| Shift Lock              | ⚪⚫⚪⚪<br>⚪⚫⚪⚪ |
| Caps Lock               | ⚫⚪⚪⚪<br>⚪⚫⚫⚫ |
| Control                 | ⚪⚪⚪⚫<br>⚫⚪⚪⚪ |
| Alt                     | ⚪⚪⚪⚫<br>⚪⚪⚫⚪ |
| GUI                     | ⚪⚪⚪⚫<br>⚪⚫⚪⚪ |
| Escape                  | ⚫⚫⚪⚪<br>⚪⚪⚪⚫ |
| Navigation Layer        | ⚪⚫⚪⚪<br>⚫⚪⚫⚪ |
| Mouse Layer             | ⚫⚪⚫⚪<br>⚪⚫⚪⚪ |
| BT Layer                | ⚫⚪⚪⚫<br>⚫⚪⚪⚫ |
| Clear Bluetooth Profile | ⚪⚫⚫⚪<br>⚪⚫⚫⚪ |

## Default/Base Layer Actions

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| A   | R   | T   | S   |
| E   | Y   | I   | O   |

_Alphabetically Sorted_

| Action | Right                |
| ------ | -------------------- |
| A      | ⚫⚪⚪⚪<br>⚪⚪⚪⚪ |
| B      | ⚪⚪⚪⚪<br>⚫⚪⚪⚫ |
| C      | ⚪⚪⚪⚪<br>⚫⚫⚪⚪ |
| D      | ⚫⚫⚫⚪<br>⚪⚪⚪⚪ |
| E      | ⚪⚪⚪⚪<br>⚫⚪⚪⚪ |
| F      | ⚫⚫⚪⚪<br>⚪⚪⚪⚪ |
| G      | ⚪⚫⚫⚪<br>⚪⚪⚪⚪ |
| H      | ⚪⚪⚪⚪<br>⚫⚪⚫⚪ |
| I      | ⚪⚪⚪⚪<br>⚪⚪⚫⚪ |
| J      | ⚪⚪⚫⚫<br>⚪⚪⚪⚪ |
| K      | ⚪⚪⚪⚪<br>⚪⚫⚪⚫ |
| L      | ⚪⚪⚪⚪<br>⚫⚫⚫⚪ |
| M      | ⚪⚪⚪⚪<br>⚪⚫⚫⚫ |
| N      | ⚪⚪⚪⚪<br>⚪⚪⚫⚫ |
| O      | ⚪⚪⚪⚪<br>⚪⚪⚪⚫ |
| P      | ⚪⚪⚪⚪<br>⚫⚪⚫⚫ |
| Q      | ⚫⚪⚫⚫<br>⚪⚪⚪⚪ |
| R      | ⚪⚫⚪⚪<br>⚪⚪⚪⚪ |
| S      | ⚪⚪⚪⚫<br>⚪⚪⚪⚪ |
| T      | ⚪⚪⚫⚪<br>⚪⚪⚪⚪ |
| U      | ⚪⚪⚪⚪<br>⚪⚫⚫⚪ |
| V      | ⚪⚫⚪⚫<br>⚪⚪⚪⚪ |
| W      | ⚫⚪⚪⚫<br>⚪⚪⚪⚪ |
| X      | ⚪⚫⚫⚫<br>⚪⚪⚪⚪ |
| Y      | ⚪⚪⚪⚪<br>⚪⚫⚪⚪ |
| Z      | ⚫⚫⚫⚫<br>⚪⚪⚪⚪ |
| ,      | ⚫⚪⚪⚪<br>⚪⚪⚫⚪ |
| !      | ⚪⚪⚫⚪<br>⚪⚪⚫⚪ |
| .      | ⚫⚪⚪⚪<br>⚪⚫⚪⚪ |
| '      | ⚫⚪⚪⚪<br>⚪⚫⚫⚪ |
| /      | ⚫⚪⚪⚪<br>⚪⚪⚪⚫ |

_Key Sorted:_

This list is sorted in this order:

1. Number of presses
2. Grouped by pattern if possible
3. Keys pressed, top left to bottom right

Spaces are left for open keys, for pattern familiarization.

| Action | Right                 | Notes |
| ------ | -------------------- |- |
| A      | ⚫⚪⚪⚪<br>⚪⚪⚪⚪ | |
| R      | ⚪⚫⚪⚪<br>⚪⚪⚪⚪ | |
| T      | ⚪⚪⚫⚪<br>⚪⚪⚪⚪ | |
| S      | ⚪⚪⚪⚫<br>⚪⚪⚪⚪ | |  
| E      | ⚪⚪⚪⚪<br>⚫⚪⚪⚪ | |
| Y      | ⚪⚪⚪⚪<br>⚪⚫⚪⚪ | |
| I      | ⚪⚪⚪⚪<br>⚪⚪⚫⚪ | |
| O      | ⚪⚪⚪⚪<br>⚪⚪⚪⚫ | |
| F      | ⚫⚫⚪⚪<br>⚪⚪⚪⚪ | Top of an F |
| G      | ⚪⚫⚫⚪<br>⚪⚪⚪⚪ | Top two teeth, Gums |
| J      | ⚪⚪⚫⚫<br>⚪⚪⚪⚪ | |
| C      | ⚪⚪⚪⚪<br>⚫⚫⚪⚪ | Bottom of the C|
| U      | ⚪⚪⚪⚪<br>⚪⚫⚫⚪ | Top of the U|
| N      | ⚪⚪⚪⚪<br>⚪⚪⚫⚫ | One less than M|
| W      | ⚫⚪⚪⚫<br>⚪⚪⚪⚪ | Like the top corners of a W |
| B      | ⚪⚪⚪⚪<br>⚫⚪⚪⚫ | Two holes, on bottom |
| V      | ⚪⚫⚪⚫<br>⚪⚪⚪⚪ | Like the top of the V |
| K      | ⚪⚪⚪⚪<br>⚪⚫⚪⚫ | Like the bottom of the K |
| H      | ⚪⚪⚪⚪<br>⚫⚪⚫⚪ | Like the bottom of an h|
| D      | ⚫⚫⚫⚪<br>⚪⚪⚪⚪ | Opposite of Low, "Down Low". Like L but on top.|
| Q      | ⚫⚪⚫⚫<br>⚪⚪⚪⚪ | |
| X      | ⚪⚫⚫⚫<br>⚪⚪⚪⚪ | It's like Z, but less keys|
| L      | ⚪⚪⚪⚪<br>⚫⚫⚫⚪ | Like the long bottom of an L |
| P      | ⚪⚪⚪⚪<br>⚫⚪⚫⚫ | |
| M      | ⚪⚪⚪⚪<br>⚪⚫⚫⚫ | One more than N|
| Z      | ⚫⚫⚫⚫<br>⚪⚪⚪⚪ | |
| !      | ⚪⚪⚫⚪<br>⚪⚪⚫⚪ | |
| /      | ⚫⚪⚪⚪<br>⚪⚪⚪⚫ | |
| .      | ⚫⚪⚪⚪<br>⚪⚫⚪⚪ | |
| ,      | ⚫⚪⚪⚪<br>⚪⚪⚫⚪ | |
| '      | ⚫⚪⚪⚪<br>⚪⚫⚫⚪ | |

## Parentheticals Layer Actions

To activate the parentheticals layer, hold `A`
| Action | Right                |
| ------ | -------------------- |
| A      | 🔘⚪⚪⚪<br>⚪⚪⚪⚪ |

**Table View:**

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| 🔘  | (   | )   | {   |
| ⚪  | [   | ]   | }   |


**List View:**

| Character | Right                 |
| --------- | -------------------- |
| (         | 🔘⚫⚪⚪<br>⚪⚪⚪⚪ |
| )         | 🔘⚪⚫⚪<br>⚪⚪⚪⚪ |
| {         | 🔘⚪⚪⚫<br>⚪⚪⚪⚪ |
| [         | 🔘⚪⚪⚪<br>⚫⚪⚪⚪ |
| ]         | 🔘⚪⚪⚪<br>⚪⚫⚪⚪ |
| }         | 🔘⚪⚪⚪<br>⚪⚪⚫⚪ |


## Number Layer Actions

To activate the number layer, hold `S`
| Action | Right                |
| ------ | -------------------- |
| S      | ⚪⚪⚪🔘<br>⚪⚪⚪⚪ |

**Table View:**

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| 1   | 2   | 3   | 🔘  |
| 4   | 5   | 6   | ⚪  |

**List View:**

| Character | Right                 |
| --------- | --------------------- |
| 1         | ⚫⚪⚪⚪<br>⚪⚪⚪🔘 |
| 2         | ⚪⚫⚪⚪<br>⚪⚪⚪🔘 |
| 3         | ⚪⚪⚫⚪<br>⚪⚪⚪🔘 |
| 4         | ⚪⚪⚪⚪<br>⚫⚪⚪🔘 |
| 5         | ⚪⚪⚪⚪<br>⚪⚫⚪🔘 |
| 6         | ⚪⚪⚪⚪<br>⚪⚪⚫🔘 |
| 7         | ⚫⚫⚪⚪<br>⚪⚪⚪🔘 |
| 8         | ⚪⚫⚫⚪<br>⚪⚪⚪🔘 |
| 9         | ⚪⚪⚪⚪<br>⚫⚫⚪🔘 |
| 0         | ⚪⚪⚪⚪<br>⚪⚫⚫🔘 |

## Symbol Layer Actions

To activate the symbol layer, hold `E`
| Action | Right                |
| ------ | -------------------- |
| E      | ⚪⚪⚪⚪<br>🔘⚪⚪⚪ |

**Table View:**

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| !   | \   | ;   | \`  |
| 🔘  | ?   | -   | =   |

**List View:**

| Character | Right                 |
| --------- | --------------------- |
| !         | ⚫⚪⚪⚪<br>🔘⚪⚪⚪ |
| \         | ⚪⚫⚪⚪<br>🔘⚪⚪⚪ |
| ;         | ⚪⚪⚫⚪<br>🔘⚪⚪⚪ |
| \`        | ⚪⚪⚪⚫<br>🔘⚪⚪⚪ |
| ?         | ⚪⚪⚪⚪<br>🔘⚫⚪⚪ |
| -         | ⚪⚪⚪⚪<br>🔘⚪⚫⚪ |
| =         | ⚪⚪⚪⚪<br>🔘⚪⚪⚫ |

## Custom Layer Actions

To activate the custom layer, hold `O`
| Action | Right                |
| ------ | -------------------- |
| O      | ⚪⚪⚪⚪<br>⚪⚪⚪🔘 |

**Table View:**

| C1          | C2           | C3          | C4  |
| ----------- | ------------ | ----------- | --- |
| Mute        | Insert       | Volume Up   | ⚪  |
| Right Shift | Print Screen | Volume Down | 🔘  |


**List View:**

| Character    | Right                  |
| ------------ | --------------------- |
| Mute         | ⚫⚪⚪⚪<br>⚪⚪⚪🔘 |
| Insert       | ⚪⚫⚪⚪<br>⚪⚪⚪🔘 |
| Volume Up    | ⚪⚪⚫⚪<br>⚪⚪⚪🔘 |
| Right Shift  | ⚪⚪⚪⚪<br>⚫⚪⚪🔘 |
| Print Screen | ⚪⚪⚪⚪<br>⚪⚫⚪🔘 |
| Volume Down  | ⚪⚪⚪⚪<br>⚪⚪⚫🔘 |

## Navigation Layer Actions

To toggle the Navigation layer, tap `R I E`

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| ⚪  | ⚫  | ⚪  | ⚪  |
| ⚫  | ⚪  | ⚫  | ⚪  |

_Actions_

| C1   | C2   | C3    | C4        |
| ---- | ---- | ----- | --------- |
| Home | Up   | End   | Page Up   |
| Left | Down | Right | Page Down |

## Mouse Layer Actions

To toggle the Mouse layer, tap `T Y A`

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| ⚫  | ⚪  | ⚫  | ⚪  |
| ⚪  | ⚫  | ⚪  | ⚪  |

_Actions_

| C1       | C2   | C3       | C4         |
| -------- | ---- | -------- | ---------- |
| Button 1 | Up   | Button 2 | Wheel Up   |
| Left     | Down | Right    | Wheel Down |

## Bluetooth Layer Actions

To toggle the Bluetooth layer, tap `S O A E`

| C1  | C2  | C3  | C4  |
| --- | --- | --- | --- |
| ⚫  | ⚪  | ⚪  | ⚫  |
| ⚫  | ⚪  | ⚪  | ⚫  |

_Actions_

| C1        | C2        | C3        | C4         |
| --------- | --------- | --------- | ---------- |
| Profile 1 | Profile 2 | Profile 3 | BT Output  |
| Profile 4 | Profile 5 | Profile 6 | USB Output |

# Layout: big ardux (16-18 key)

The big form of ardux. It includes **all** of standard ardux with some extras to facilitate using mod keys like shift and control, symbols and F1-12.

Please refer to the standard ardux layout for the primary use and the below for the extra key mappings and addional layer detail.

## Left

### Left Default/Base Layer Actions

| C1   | C2  | C3    | C4      | C5      |
| ---- | --- | ----- | ------- | ------- |
| S    | T   | R     | A       | -       |
| O    | I   | Y     | E       | Shift   |
| Ctrl | @   | Del   | =       | Tab     |
|      |     | `SYM` | _Enter_ | _Space_ |

`SYM` activates the Symbol Layer

### Left Symbol Layer Actions

| C1   | C2  | C3    | C4      | C5      |
| --- | --- | --- | --- | --- |
| \`  | #   | {   | }   | ^   |
| \   | $   | (   | )   | &   |
| \|  | %   | [   | ]   | &   |
| ⚪  | ⚪  | ⚪  |     |     |

### Left Activate Function Layer Combo

| C1   | C2  | C3    | C4      | C5      |
| --- | --- | --- | --- | --- |
| ⚪  | ⚪  | ⚪  | ⚪  | ⚪  |
| ⚪  | ⚪  | ⚪  | ⚪  | ⚫  |
| ⚪  | ⚪  | ⚪  | ⚪  | ⚫  |
|     |     | ⚪  | ⚪  | ⚪  |

### Left Function Layer Actions - Single Taps

| C1   | C2  | C3    | C4      | C5      |
| --- | --- | --- | --- | --- |
| F4  | F3  | F2  | F1  | ⚪  |
| F8  | F7  | F6  | F5  | ⚪  |
| F12 | F11 | F10 | F9  | ⚪  |
|     |     | ⚪  | ⚪  | ⚪  |

## Right

### Right Default/Base Layer Actions

| C1      | C2      | C3    | C4  | C5   |
| ------- | ------- | ----- | --- | ---- |
| -       | A       | R     | T   | S    |
| Shift   | E       | Y     | I   | O    |
| Tab     | =       | Del   | @   | Ctrl |
| _Space_ | _Enter_ | `SYM` |     |      |

`SYM` activates the Symbol Layer

### Right Symbol Layer Actions

| C1   | C2  | C3    | C4      | C5      |
| --- | --- | --- | --- | --- |
| \`  | #   | {   | }   | ^   |
| \   | $   | (   | )   | &   |
| \|  | %   | [   | ]   | &   |
| ⚪  | ⚪  | ⚪  |     |     |

### Right Function Layer Actions

### Right Activate Function Layer Combo

| C1   | C2  | C3    | C4      | C5      |
| --- | --- | --- | --- | --- |
| ⚪  | ⚪  | ⚪  | ⚪  | ⚪  |
| ⚫  | ⚪  | ⚪  | ⚪  | ⚪  |
| ⚫  | ⚪  | ⚪  | ⚪  | ⚪  |
| ⚪  | ⚪  | ⚪  |     |     |

### Right Single Taps

| C1  | C2  | C3  | C4  | C5  |
| --- | --- | --- | --- | --- |
| ⚪  | F1  | F2  | F3  | F4  |
| ⚪  | F5  | F6  | F7  | F8  |
| ⚪  | F9  | F10 | F11 | F12 |
| ⚪  | ⚪  | ⚪  |     |     |

# Layout: 40% ardux (32-36 key)

This is the two handed form of ardux. It inclues _all_ of big ardux _and_ _all_ of standard ardux. This layout is designed to allow you to flip between one and two handed typing easly and using a single 40% keyboard.

Please refer to the standard and big ardux layout for the primary use and the below for the extra key mappings and addional layer detail.

## Base Layer Actions (QWERTY)

|                |     |     |     |     |     |     |     |     |     |     |     |     |                    |             |
| -------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ------------------ | ----------- |
| _Grave Escape_ | Q   | W   | E   | R   | T   |     |     |     | Y   | U   | I   | O   | P                  | _Backspace_ |
| _Tab_          | A   | S   | D   | F   | G   |     |     |     | H   | J   | K   | L   | ;                  | _Enter_     |
| _Control_      | Z   | X   | C   | V   | B   |     |     |     | N   | M   | ,   | .   | / <br> ~x3\ =\ \\~ | _'_         |

### Left Thumb Row

|     |     |     |         |       |         |     |     |     |                       |                    |                |     |     |     |
| --- | --- | --- | ------- | ----- | ------- | --- | --- | --- | --------------------- | ------------------ | -------------- | --- | --- | --- |
|     |     |     | MO(SYM) | _GUI_ | _Space_ |     |     |     | _Space_ <br> ~H\ Nav~ | _-_ <br> ~H\ Func~ | = <br> ~x3\ @~ |     |     |     |

### Right Thumb Row

|     |     |     |                |                    |                       |     |     |     |         |       |         |     |     |     |
| --- | --- | --- | -------------- | ------------------ | --------------------- | --- | --- | --- | ------- | ----- | ------- | --- | --- | --- |
|     |     |     | = <br> ~x3\ @~ | _-_ <br> ~H\ Func~ | _Space_ <br> ~H\ Nav~ |     |     |     | _Space_ | _GUI_ | MO(SYM) |     |     |     |

## Number/Symbol Layer Actions

|         |     |     |     |     |     |     |     |     |     |     |     |     |     |                |
| ------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | -------------- |
| _Grave_ | F1  | F2  | F3  | F4  | F5  |     |     |     | F6  | F7  | F8  | F9  | F10 | _Delete_       |
| ⚪      | 1   | 2   | 3   | 4   | 5   |     |     |     | 6   | 7   | 8   | 9   | 0   | _Insert_       |
| ⚪      | ⚪  | ⚪  | ⚪  | ⚪  | F11 |     |     |     | F12 | ⚪  | ⚪  | ⚪  | ⚪  | _Print Screen_ |
|         |     |     | Alt | ⚪  | ⚪  |     |     |     | ⚪  | ⚪  | Alt |     |     |                |

## Navigation Layer Actions

|           |           |      |      |       |     |     |     |     |     |      |      |       |           |          |
| --------- | --------- | ---- | ---- | ----- | --- | --- | --- | --- | --- | ---- | ---- | ----- | --------- | -------- |
| ⚪        | Page Up   | Home | Up   | End   | ⚪  |     |     |     | ⚪  | Home | Up   | End   | Page Up   | _Delete_ |
| _Tab_     | Page Down | Left | Down | Right | ⚪  |     |     |     | ⚪  | Left | Down | Right | Page Down | ⚪       |
| _Control_ | ⚪        | ⚪   | ⚪   | ⚪    | ⚪  |     |     |     | ⚪  | ⚪   | ⚪   | ⚪    | ⚪        | _Shift_  |
|           |           |      | ⚪   | ⚪    | ⚪  |     |     |     | ⚪  | ⚪   | ⚪   |       |           |          |
