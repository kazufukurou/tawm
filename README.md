# tawm

Minimal window manager written in Python.

The screen is split into 4 fields. Each field has corresponding keyboard key:

```
.-------.    .-------.
| 1 | 2 |    | U | I |
|---+---| -> |---+---|
| 3 | 4 |    | J | K |
'-------'    '-------'
```

# Default key bindings

Key | Action
----|-------
Mod4 + U, I, J, K | switch to next window in field 1, 2, 3, 4
Mod4 + Shift + U, I, J, K | move window to field 1, 2, 3, 4
Mod4 + Control + U, I, J, K | set window size to 1x1, 2x1, 1x2, 2x2
Mod4 + Escape | kill window
Mod4 + Shift + Escape | exit

# Usage

Default keys:
```
tawm
```
Custom keys, (1 = Mod1):
```
tawm 1 u i j k
```
