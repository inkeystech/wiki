---
title: ardux
description: General documentation for the ardux keymap
published: true
date: 2022-06-14T22:07:49.296Z
tags: ardux, keymap, comingsoon
editor: markdown
dateCreated: 2022-04-20T14:58:35.235Z
---

# ardux
`#comingsoon`

# Known Issues

- what is ardux and how this works?
- define single tap conventions
- define hold tap conventions
- define combo conventions
- add map for big ardux
- add map for 40% ardux

# Source Code

All source code is available on GitHub at [https://github.com/arduxio/](https://github.com/arduxio/)

# Supported Keyboards

ardux is available for a number of keyboards. We currently have both [zmk](https://zmkfirmware.dev/) and [qmk](https://qmk.fm/) ports available. These ports include support for different keyboards. Please check either the [zmk-ardux](https://github.com/arduxio/zmk-ardux/) or [qmk-ardux](https://github.com/arduxio/qmk-ardux) release pages for current keyboard support.

# Layout: Standard (8 key) ardux

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
| Number Layer | ⚪ | ⚪ | Parentheticals Layer |
| Custom Layer | ⚪ | ⚪ | Symbol Layer |

### Right Single Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| A | R | T | S |
| E | Y | I | O |

### Right Hold Taps

| C1 | C2 | C3 | C4 |
| -- | -- | -- | -- |
| Parentheticals Layer | ⚪ | ⚪ | Number Layer |
| Symbol Layer | ⚪ | ⚪ | Custom Layer |

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
