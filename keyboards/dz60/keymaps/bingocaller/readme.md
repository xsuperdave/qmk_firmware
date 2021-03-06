# MacOS standard 60% keymap with Vim-like arrows

This is a MacOS-specific keymap for DZ60 configured in a standard 60% ANSI layout, with a stepped Caps Lock:

[![](https://i.imgur.com/lFP2O41.png)](http://www.keyboard-layout-editor.com/#/gists/4b156fdf2c1426bffc82fadd2b1c5634)

**[Fully assembled 60% keyboard from KBDfans](https://kbdfans.cn/collections/fully-assembled-keyboard/products/fully-assembled-plastic-case-mechanical-keyboard)**

## Base Layer

```
,-----------------------------------------------------------------------------------------.
|  `  |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  |  0  |  -  |  =  | Backspace |
|-----------------------------------------------------------------------------------------+
|   Tab  |  Q  |  W  |  E  |  R  |  T  |  Y  |  U  |  I  |  O  |  P  |  [  |  ]  |   \    |
|-----------------------------------------------------------------------------------------+
| Ctrl/Esc |  A  |  S  | D/L1 |  F  |  G  |  H  |  J  |  K  |  L  |  ;  |  '  |   Enter   |
|-----------------------------------------------------------------------------------------+
|   Shift/(   |  Z  |  X  |  C  |  V  |  B  |  N  |  M  |  ,  |  .  |  /  |    Shift/)    |
|-----------------------------------------------------------------------------------------+
| Hyper |  Alt  |  Cmd  |             Space/L3             |  Cmd  |  Alt  |  L4  | Hyper |
`-----------------------------------------------------------------------------------------'
```

* Space Cadet shifts (parentheses on tap)
* Caps Lock is Control on hold, Esc on tap
* Hyper/Caps Lock on Control
* Hold D to activate layer 1
* Hold Space to activate layer 3 (Mouse keys)
* Hold FN to activate layer 4

## `L1`

```
,-----------------------------------------------------------------------------------------.
|     |     |     |     |     |     |     |     |     |     |     |     |     |           |
|-----------------------------------------------------------------------------------------+
|        |     |  W→  |     |     |     |     | ⏮ | ⏯ | ⏭ |  🔇 |  🔉 |  🔊 |         |
|-----------------------------------------------------------------------------------------+
|          |     |     |     |  L2  |     |  ←  |  ↓  |  ↑  |  →  |     |     |           |
|-----------------------------------------------------------------------------------------+
|             |     |     |     |     |  W←  |  ⌫  |  ⌦  |     |     |     |              |
|-----------------------------------------------------------------------------------------+
|       |       |       |                                 |       |       |       |       |
`-----------------------------------------------------------------------------------------'
```

* Vim arrows (HJKL)
* Vim-like move across words with W(ord), and B(eginning)
* Media controls (fine volume controls using Option+Shift)
* Backspace/Del on N/M
* Hold F to activate layer 2

## `L2`

```
,-----------------------------------------------------------------------------------------.
|     |     |     |     |     |     |     |     |     |     |     |     |     |           |
|-----------------------------------------------------------------------------------------+
|        |     |  W⌦  |     |     |     |     |     |     |     |     |     |     |       |
|-----------------------------------------------------------------------------------------+
|          |     |      |     |     |     |  ↖  |  ⇞  |  ⇟  |  ↘︎  |     |     |           |
|-----------------------------------------------------------------------------------------+
|             |     |     |     |     |  W⌫  |     |     |     |     |     |              |
|-----------------------------------------------------------------------------------------+
|       |       |       |                                 |       |       |       |       |
`-----------------------------------------------------------------------------------------'
```

* Home, End, Page Up, Page Down
* Delete word forward/back on W/B

## `L3`

```
,-----------------------------------------------------------------------------------------.
|     |     |     |     |     |     |     |     |     |     |     |     |     |           |
|-----------------------------------------------------------------------------------------+
|        |     |     |     | MWU |     |     |     |     |     |     |     |     |        |
|-----------------------------------------------------------------------------------------+
|           |     | M3  | M2  | M1  |     | M←  | M↓  | M↑  | M→  |     |     |           |
|-----------------------------------------------------------------------------------------+
|             |     |     |     | MWD |     |     |     |     |     |     |               |
|-----------------------------------------------------------------------------------------+
|       |       |       |                                 |       |       |       |       |
`-----------------------------------------------------------------------------------------'
```

* Mouse keys
    * Cursor movement: HJKL
    * MB 1, 2, and 3 on F, D, and S, respectively
    * Mouse wheel: Up (R) and Down (V)

## `L4`

```
,-----------------------------------------------------------------------------------------.
|     | F1  | F2  | F3  | F4  | F5  | F6  | F7  | F8  | F9  | F10 | F11 | F12 |     ⌦     |
|-----------------------------------------------------------------------------------------+
|       |RGB_T|RGB_M|RGB_H+|RGB_H-|RGB_S+|RGB_S-|RGB_V+|RGB_V-|   |   |   |   |   RESET   |
|-----------------------------------------------------------------------------------------+
|           |     |     |     |     |     |     |     |     |     |     |     |           |
|-----------------------------------------------------------------------------------------+
|             | 🔅 | 🔆 |     |     |     |     |     |     |     |      |                |
|-----------------------------------------------------------------------------------------+
|       |       |       |                                 |       |       |       |       |
`-----------------------------------------------------------------------------------------'
```

* F1-12
* Del on backspace
* RGB (underglow) controls
* RESET firmware on backspace
* Screen brightness: Z (decrease), X (increase)
