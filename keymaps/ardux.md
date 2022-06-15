---
title: ardux
description: General documentation for the ardux keymap
published: true
date: 2022-06-15T00:02:07.852Z
tags: ardux, keymap, comingsoon
editor: markdown
dateCreated: 2022-04-20T14:58:35.235Z
---

# What is ardux?

ardux is a keyboard layout designed to be used one handed with as few as 8 keys or as many as 36 keys or two handed. The layout is setup to be a consistent way to type one handed that scales up or down based on need, environment and more.

ardux aims to facilitate one handed typing (mobile needs, physical needs, etc) while also helping users to be efficient (>50wpm is possible one handed) as typists, even if they only use one hand for typing. The layout can be ultra-mobile (only 8 keys) or 'desk sized' (16-18 keys) or a full one *or* two handed layout (32-36 keys).

## ardux has three major forms

- **standard ardux**: 8 keys and ultra mobile and ultra accessible. this is fundamental form of ardux and is available in *all* ardux layouts ; if you're looking for mobile or general one handed typing, this is the form to look into
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

We *encourage* users of ardux to change the layout if desired and make it their own.

If you have a remix, we welcome posts about how you've remixed on our Discord.

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

### *Italic* function names

We use *italics* to denote a key / function that is *optional* for inclusion on a physical keyboard. There are a number of keyboard options available in similar sizes. Due to clustering of keyboard sizes, the big and 40% ardux layouts make certain functions *optional* to be compatible with more keyboards.

### Subscripts

We use subscripts to denote secondary functions assigned to keys. If there is a `x` preceeding a number then `=` and a value ; it means you tap that key the number of times and youll get the value after the `=`. We have setup multi-tap functions for some keys.

We also use subscripts with an `H` at the start. This means to hold the key to get the shown function. We also have setup hold-tap functions for some keys.

## Key Icons

We use the `⚪` symbol to denote a key that is *not* pressed and a `⚫` symbol to denote a pressed key.

We also use the `⚪` symbol to denote a key that is *not* mapped to a function.

# Layout: Standard ardux (8 key)

This is the standard form of ardux. This layout is 100% present in both big ardux and 40% ardux.

## Global Actions

### Combos

| Action | Left | Right |
| ------ | ---- | ----- |
| Space | ⚪⚪⚪⚪<br>⚫⚫⚫⚫ | ⚪⚪⚪⚪<br>⚫⚫⚫⚫ |
| Enter | ⚪⚪⚪⚫<br>⚪⚪⚪⚫ | ⚫⚪⚪⚪<br>⚫⚪⚪⚪ |
| Tab | ⚪⚫⚫⚫<br>⚫⚪⚪⚪ | ⚫⚫⚫⚪<br>⚪⚪⚪⚫ |
| Backspace | ⚪⚪⚫⚪<br>⚪⚪⚪⚫ | ⚪⚫⚪⚪<br>⚫⚪⚪⚪ |
| Forward Delete | ⚪⚪⚫⚪<br>⚪⚫⚪⚪ | ⚪⚫⚪⚪<br>⚪⚪⚫⚪ |
| Shift | ⚫⚫⚫⚪<br>⚪⚪⚪⚫ | ⚪⚫⚫⚫<br>⚫⚪⚪⚪ |
| Shift Lock | ⚪⚪⚫⚪<br>⚪⚪⚫⚪ | ⚪⚫⚪⚪<br>⚪⚫⚪⚪ |
| Caps Lock | ⚪⚪⚪⚫<br>⚫⚫⚫⚪ | ⚫⚪⚪⚪<br>⚪⚫⚫⚫ |
| Control | ⚫⚪⚪⚪<br>⚪⚪⚪⚫ | ⚪⚪⚪⚫<br>⚫⚪⚪⚪ |
| Alt | ⚫⚪⚪⚪<br>⚪⚫⚪⚪ | ⚪⚪⚪⚫<br>⚪⚪⚫⚪ |
| GUI | ⚫⚪⚪⚪<br>⚪⚪⚫⚪ | ⚪⚪⚪⚫<br>⚪⚫⚪⚪ |
| Escape | ⚪⚪⚫⚫<br>⚫⚪⚪⚪ | ⚫⚫⚪⚪<br>⚪⚪⚪⚫ |
| Navigation Layer | ⚪⚪⚫⚪<br>⚪⚫⚪⚫ | ⚪⚫⚪⚪<br>⚫⚪⚫⚪ |
| Mouse Layer | ⚪⚫⚪⚫<br>⚪⚪⚫⚪ | ⚫⚪⚫⚪<br>⚪⚫⚪⚪ |
| BT Layer | ⚫⚪⚪⚫<br>⚫⚪⚪⚫ | ⚫⚪⚪⚫<br>⚫⚪⚪⚫ |
| Clear Bluetooth Profile | ⚪⚫⚫⚪<br>⚪⚫⚫⚪ | ⚪⚫⚫⚪<br>⚪⚫⚫⚪ |

## Default/Base Layer Actions

### Left Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| S | T | R | A |
| O | I | Y | E |

### Left Hold Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| Activate Number Layer | ⚪ | ⚪ | Activate Parentheticals Layer |
| Activate Custom Layer | ⚪ | ⚪ | Activate Symbol Layer |

### Right Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| A | R | T | S |
| E | Y | I | O |

### Right Hold Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| Activate Parentheticals Layer | ⚪ | ⚪ | Activate Number Layer |
| Activate Symbol Layer | ⚪ | ⚪ | Activate Custom Layer |

### Combos

| Action | Layer | Left | Right |
| --------- | ----- | ---- | ----- |
| , | ⚪⚪⚪⚫<br>⚪⚫⚪⚪ | ⚫⚪⚪⚪<br>⚪⚪⚫⚪ |
| ! | ⚪⚫⚪⚪<br>⚪⚫⚪⚪ | ⚪⚪⚫⚪<br>⚪⚪⚫⚪ |
| . | ⚪⚪⚪⚫<br>⚪⚪⚫⚪ | ⚫⚪⚪⚪<br>⚪⚫⚪⚪ |
| ' | ⚪⚪⚪⚫<br>⚪⚫⚫⚪ | ⚫⚪⚪⚪<br>⚪⚫⚫⚪ |
| / | ⚪⚪⚪⚫<br>⚫⚪⚪⚪ | ⚫⚪⚪⚪<br>⚪⚪⚪⚫ |
| B | ⚪⚪⚪⚪<br>⚫⚪⚪⚫ | ⚪⚪⚪⚪<br>⚫⚪⚪⚫ |
| C | ⚪⚪⚪⚪<br>⚪⚪⚫⚫ | ⚪⚪⚪⚪<br>⚫⚫⚪⚪ |
| D | ⚪⚫⚫⚫<br>⚪⚪⚪⚪ | ⚫⚫⚫⚪<br>⚪⚪⚪⚪ |
| F | ⚪⚪⚫⚫<br>⚪⚪⚪⚪ | ⚫⚫⚪⚪<br>⚪⚪⚪⚪ |
| G | ⚪⚫⚫⚪<br>⚪⚪⚪⚪ | ⚪⚫⚫⚪<br>⚪⚪⚪⚪ |
| H | ⚪⚪⚪⚪<br>⚪⚫⚪⚫ | ⚪⚪⚪⚪<br>⚫⚪⚫⚪ |
| J | ⚫⚫⚪⚪<br>⚪⚪⚪⚪ | ⚪⚪⚫⚫<br>⚪⚪⚪⚪ |
| K | ⚪⚪⚪⚪<br>⚫⚪⚫⚪ | ⚪⚪⚪⚪<br>⚪⚫⚪⚫ |
| L | ⚪⚪⚪⚪<br>⚪⚫⚫⚫ | ⚪⚪⚪⚪<br>⚫⚫⚫⚪ |
| M | ⚪⚪⚪⚪<br>⚫⚫⚫⚪ | ⚪⚪⚪⚪<br>⚪⚫⚫⚫ |
| N | ⚪⚪⚪⚪<br>⚫⚫⚪⚪ | ⚪⚪⚪⚪<br>⚪⚪⚫⚫ |
| P | ⚪⚪⚪⚪<br>⚫⚫⚪⚫ | ⚪⚪⚪⚪<br>⚫⚪⚫⚫ |
| Q | ⚫⚫⚪⚫<br>⚪⚪⚪⚪ | ⚫⚪⚫⚫<br>⚪⚪⚪⚪ |
| U | ⚪⚪⚪⚪<br>⚪⚫⚫⚪ | ⚪⚪⚪⚪<br>⚪⚫⚫⚪ |
| V | ⚫⚪⚫⚪<br>⚪⚪⚪⚪ | ⚪⚫⚪⚫<br>⚪⚪⚪⚪ |
| W | ⚫⚪⚪⚫<br>⚪⚪⚪⚪ | ⚫⚪⚪⚫<br>⚪⚪⚪⚪ |
| X | ⚫⚫⚫⚪<br>⚪⚪⚪⚪ | ⚪⚫⚫⚫<br>⚪⚪⚪⚪ |
| Z | ⚫⚫⚫⚫<br>⚪⚪⚪⚪ | ⚫⚫⚫⚫<br>⚪⚪⚪⚪ |

## Number Layer Actions

### Left Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| ⚪ | 3 | 2 | 1 |
| ⚪ | 6 | 5 | 4 |

### Right Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| 1 | 2 | 3 | ⚪ |
| 4 | 5 | 6 | ⚪ |

### Combos

| Character | Left | Right |
| --------- | ---- | ----- |
| 7 | ⚪⚪⚫⚫<br>⚪⚪⚪⚪ | ⚫⚫⚪⚪<br>⚪⚪⚪⚪ |
| 8 | ⚪⚫⚫⚪<br>⚪⚪⚪⚪ | ⚪⚫⚫⚪<br>⚪⚪⚪⚪ |
| 9 | ⚪⚪⚪⚪<br>⚪⚪⚫⚫ | ⚪⚪⚪⚪<br>⚫⚫⚪⚪ |
| 0 | ⚪⚪⚪⚪<br>⚪⚫⚫⚪ | ⚪⚪⚪⚪<br>⚪⚫⚫⚪ |

## Symbol Layer Actions

### Left Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| \` | ; | \ | ! |
| = | - | ? | ⚪ |

### Right Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| ! | \ | ; | \` |
| ⚪ | ? | - | = |

## Parentheticals Layer Actions

### Left Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| { | ( | ) | ⚪ |
| } | [ | ] | ⚪ |

### Right Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| ⚪ | ( | ) | { |
| ⚪ | [ | ] | } |

## Navigation Layer Actions

### Left Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| Page Up | Home | Up | End |
| Page Down | Left | Down | Right |

### Right Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| Home | Up | End | Page Up |
| Left | Down | Right | Page Down |

## Mouse Layer Actions

### Left Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| Wheel Up | Button 2 | Up | Button 1 |
| Wheel Down | Left | Down | Right |

### Right Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| Button 1 | Up | Button 2 | Wheel Up |
| Left | Down | Right | Wheel Down |

## Custom Layer Actions

### Left Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| ⚪ | Volume Up | Insert | Mute |
| ⚪ | Volume Down | Print Screen | Right Shift |

### Right Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| Mute | Insert | Volume Up | ⚪ |
| Right Shift | Print Screen | Volume Down | ⚪ |

## Bluetooth Layer Actions

### Left Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| BT Output | Profile 3 | Profile 2 | Profile 1 |
| USB Output | Profile 6 | Profile 5 | Profile 4 |

### Right Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| Profile 1 | Profile 2 | Profile 3 | BT Output |
| Profile 4 | Profile 5 | Profile 6 | USB Output |

# Layout: big ardux (16-18 key)

The big form of ardux. It includes **all** of standard ardux with some extras to facilitate using mod keys like shift and control, symbols and F1-12.

Please refer to the standard ardux layout for the primary use and the below for the extra key mappings and addional layer detail.

## Default/Base Layer Actions

### Left Single Taps

||||||
|-|-|-|-|-|
| S | T | R | A | - |
| O | I | Y | E | Shift |
| Ctrl | @ | Del | = | Tab
| | |MO(1)|*Enter*|*Space*|

### Right Single Taps

||||||
|-|-|-|-|-|
| - | A | R | T | S |
| Shift | E | Y | I | O |
| Tab | = | Del | @ | Ctrl |
| *Space* | *Enter* | MO(1) | | |

## Symbol Layer Actions

### Left Single Taps

||||||
|-|-|-|-|-|
| ^ | { | } | # | \` |
| & | ( | ) | $ | \ |
| * | [ | ] | % | \| |
| | | ⚪ | ⚪ | ⚪ |

### Right Single Taps

||||||
|-|-|-|-|-|
| \` | # | { | } | ^ |
| \ | $ | ( | ) | & |
| \| | % | [ | ] | & |
| ⚪ | ⚪ | ⚪ | | |

## Function Layer Actions

### Activate Function Layer Combo

#### Left

||||||
|-|-|-|-|-|
| ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| ⚪ | ⚪ | ⚪ | ⚪ | ⚫ |
| ⚪ | ⚪ | ⚪ | ⚪ | ⚫ |
| | | ⚪ | ⚪ | ⚪ |

#### Right

||||||
|-|-|-|-|-|
| ⚪ | ⚪ | ⚪ | ⚪ | ⚪ |
| ⚫ | ⚪ | ⚪ | ⚪ | ⚪ |
| ⚫ | ⚪ | ⚪ | ⚪ | ⚪ |
| ⚪ | ⚪ | ⚪ | | |


### Left Single Taps

||||||
|-|-|-|-|-|
| F4 | F3 | F2 | F1 | ⚪ |
| F8 | F7 | F6 | F5 | ⚪ |
| F12 | F11 | F10 | F9 | ⚪ |
| | | ⚪ | ⚪ | ⚪ |

### Right Single Taps

||||||
|-|-|-|-|-|
| ⚪ | F1 | F2 | F3 | F4 |
| ⚪ | F5 | F6 | F7 | F8 |
| ⚪ | F9 | F10 | F11 | F12 |
| ⚪ | ⚪ | ⚪ | | |

# Layout: 40% ardux (32-36 key)

This is the two handed form of ardux. It inclues *all* of big ardux *and* *all* of standard ardux. This layout is designed to allow you to flip between one and two handed typing easly and using a single 40% keyboard.

Please refer to the standard and big ardux layout for the primary use and the below for the extra key mappings and addional layer detail.

## Base Layer Actions (QWERTY)

||||||||||||||||
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| *Grave Escape* | Q | W | E | R | T | | | | Y | U | I | O | P | *Backspace* |
| *Tab* | A | S | D | F | G | | | | H | J | K | L | ; | *Enter* |
| *Control* | Z | X | C | V | B | | | | N | M | , | . | / <br> ~x3\ =\ \\~ | *'* |

### Left Thumb Row

||||||||||||||||
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| | | | MO(SYM) | *GUI* | *Space* | | | | *Space* <br> ~H\ Nav~ | *-* <br> ~H\ Func~ | = <br> ~x3\ @~ | | | |

### Right Thumb Row

||||||||||||||||
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| | | | = <br> ~x3\ @~ | *-* <br> ~H\ Func~ | *Space* <br> ~H\ Nav~ | | | | *Space* | *GUI* | MO(SYM) | | | |

## Number/Symbol Layer Actions

||||||||||||||||
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| *Grave* | F1 | F2 | F3 | F4 | F5 | | | | F6 | F7 | F8 | F9 | F10 | *Delete* |
| ⚪ | 1 | 2 | 3 | 4 | 5 | | | | 6 | 7 | 8 | 9 | 0 | *Insert* |
| ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | F11 | | | | F12 | ⚪ | ⚪ | ⚪ | ⚪ | *Print Screen* |
| | ||Alt|⚪|⚪||||⚪|⚪|Alt||||

## Navigation Layer Actions

||||||||||||||||
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
| ⚪ | Page Up | Home | Up | End | ⚪ | | | | ⚪ | Home | Up | End | Page Up | *Delete* |
| *Tab* | Page Down | Left | Down | Right | ⚪ | | | | ⚪ | Left | Down | Right | Page Down | ⚪ |
| *Control* | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | | | | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | *Shift* |
| | | | ⚪ | ⚪ | ⚪ | | | | ⚪ | ⚪ | ⚪ | | | |