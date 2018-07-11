# Shortcuts

Below are my custom shortcuts. I developed these based off of what functions I use the most frequently, and how close I can get to working mouse-free. If you are familiar with the text editor Vim, I tried to emulate the feel of working in Vim. The general concept of each set of shortcuts is described below. SunVox can also use option, control, and modifier combinations, but I'm trying to keep it simple and immediate (also why I don't use funtion keys.) You can load these and modify them to your liking by loading the xx file.

If anyone wishes to format and contribute the default SunVox shortcuts that the app ships with to be included here, or their own custom shortcuts, please do so.

SunVox doesn't delete bindings (trying to will just assign `delete` to the action you're trying to remove) - instead, overwrite an existing shortcut with a key you don't plan to use. In my case, when I want to disable shortcuts, I will assign them to `F12`.

In the shortcuts listed below, a `(P)` indicates the shortcut applies to the pattern section of SunVox, an `(M)` indicates the module section, a `(C)` indicates the controllers section, and a `(T)` indicates the timeline. `SC:` indicates that a shortcut is listed as a "Special Command".

## MAIN

In the main set of shortcuts, ie. without any modifier keys, the short cuts in the bottom 2 rows of the keyboard allow you to navigate quickly through the pattern and module sections apply actions as well as handle start/stop/transport commands, while the top two rows are used as a two octave keyboard for inputting note data and playing modules.

| 1 `{C1}` | 2 `{c1}` | 3 `{D1}` | 4 `{d1}` | 5 `{E1}` | 6 `{F1}` | 7 `{f1}` | 8 `{G1}` | 9 `{g1}` | 0 `{A1}` | - `{a1}` | + `{B1}` |  delete `Delete (P)` |
|---|
| __Q__ `{C0}` | __W__ `{c0}` | __E__ `{D0}` | __R__ `{d0}` | __T__ `{E0}` | __Y__ `{F0}` | __U__ `{f0}` | __I__ `{G0}` | __O__ `{g0}` | __P__ `{A0}` | __[__ `{a0}` | __]__ `{B0}` | __\__ `Random Mod Ctrls (C)` |
| __A__ `Unmute All (M)` | __S__ `Left (P)` | __D__ `Right (P)` | __F__ `Up (P)` | __G__ `Page Up (P)` | __H__ `Go to Start (P)` | __J__ `Prev Vert (M)` | __K__ `Prev Horiz (M)` | __L__ `Next Horiz (M)` | __;__ `Play From Beginning (T)` | __'__ `Go to Beginnging (T)` |
| __Z__ `Bypass (M)` | __X__ `Mute (M)` | __C__ `Solo (M)` | __V__ `Down (P)` | __B__ `Page Down (P)` | __N__ `Go to End (P)` | __M__ `Next Vert (M)` | __,__ `Play Pattern (T)` | __.__ `Stop (T)` | __/__ `Record (T)` |

| __esc__ `Exit` | __`__ `Find a Module (M)` | __Space__ `Edit` |
|---|


## SHIFT +

These shortcuts are executed created by introducing the modifier `shift`. The bottom two rows are all commands that create or edit data in the pattern section, while the top two rows extend the keyboard to the third octave, as well as let you change the base octave that `C0-B0` in the main set of shortcuts begins from. (So `C0` is not absolute `C0` - its relative to what octave you have chosen to start at.)


| 1 `Octave1` | 2 `Octave2` | 3 `Octave3` | 4 `Octave4` | 5 `Octave5` | 6 `Octave6` | 7 `Octave7` | 8 `Octave8` | 9 | 0 `Remap (P)`  | - `Octave -` | + `Octave +` |
|---|
| __Q__ `{C2}` | __W__ `{c2}` | __E__ `{D2}` | __R__ `{d2}` | __T__ `{E2}` | __Y__ `{F2}` | __U__ `{f2}` | __I__ `{G2}` | __O__ `{g2}` | __P__ `{A2}` | __[__ `{a2}` | __]__ `{B2}` | __\__ `Paste and Mix (P)` |
| __A__ `Select All (P)` | __S__ `Prev Track* (P)` | __D__ `Next Track* (P)` | __F__ `Inc Pattern Edit Step (P)` | __G__ `Transpose +12 (P)` | __H__ `Transpose +1 (P)` | __J__ `SC: Set Pitch (P)` | __K__ `SC: Prev Track (P)` | __L__ `SC: Note Off (P)` | __;__ `Insert (P)` | __'__ `Back (P)` |
| __Z__ `Select Track (P)`| __X__ `Selection Begin (P)` | __C__ `Selection End (P)` | __V__ `Dec Pattern Edit Step (P)` | __B__ `Transpose -12 (P)` | __N__ `Transpose -1 (P)` | __M__ `SC: Previous Track` | __,__ `Place Evenly (P)` | __.__ `Interpolate XXYY (P)` | __/__ `Interpolate VV (P)` |

| __Space__ `Play/Stop (T)` |
|---|

_* These don't seem to be assignable, but rather become enabled when the four arrow keys are deactivated_


## OPTION +

These are project wide and standard main menu app shortcuts.


| __A__ | __S__ `Save` | __D__ `Duplicate` | __F__ | __G__ | __H__ | __J__ | __K__ | __L__ `Load Project` |
|---|
| __Z__ `Undo (+ shift: Redo)` | __X__ `Cut` | __C__ `Copy` | __V__ `Paste` | __B__ `Save Backup` | __N__ `New` |


## Other

**Exit :** Escape

**Insert :** ?

**Delete :** Backspace

**Backspace :** Backspace


## Pattern Editor

**Move Left :**  S  |  Left Arrow

**Move Right :**  D  |  Right Arrow

**Move Up :**  F  |  Up Arrow

**Move Down :**  V  |  Down Arrow

**Page Up :**  G

**Page Down :**  B

**Next Track :**  Tab

**Previous Track :**  Shift + Tab

**Pattern Edit ON/OFF :**  Space

**Select All :**  A  |  CTRL + A

**Select Track :** Ctrl + T

**Selection Begin :** Ctrl + 9

**Selection End :** Ctrl + 0

**Increase Pattern Edit Step :**  Ctrl + =

**Decrease Pattern Edit Step :**  Ctrl + -

**Special Cmd: Note OFF :** '

**Special Cmd: Set Pitch :**  K

**Special Cmd: Previous Track :**  Shift + K

**Interpolate XXYY :**  Ctrl + I

**Interpolate VV :**  Ctrl + U

**Remap :** ?

**Place Evenly :**  Ctrl + P


## Keyboard

**Octave 1...7 :**  F1...F7

**Octave + :**  Shift + 0

**Octave - :**  Shift + 9

**Notes C0...B0 :**  Q...]

**Notes C1...B1 :**  1...=

**Transpose +1 :**  Shift + =

**Transpose -1 :**  Shift + -

**Transpose +12 :**  Shift + ]

**Transpose -12 :**  Shift + [


## Module Window

**Next Module :** Shift + .

**Previous Module :** Shift + ,

**Next Synth :** Ctrl + .

**Previous Synth :** Ctrl + ,

**Next Module Horizontally :** L

**Previous Module Horizontally :** K

**Next Module Vertically :** M

**Previous Module Vertically :** J

**Toggle Bypass :** Z

**Toggle Mute :** X

**Toggle Solo :** C

**Unmute All Modules :** Ctrl + 4

**Find a Module :** Ctrl + F

## Timeline

**Play/Stop :**  Shift + Space

**Stop :**  Shift + Space

**Play From Beginning :**  Ctrl + Space

**Play Pattern :**  Alt + Space

**Record :**  Shift + F9

**Go to Beginnging :**  Shift + F12

**Go to Start (Home) :** ?

**Go to End :** ?
