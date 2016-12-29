# tawm

Minimal window manager written in Python.

The screen is split into 4 fields. Each field has corresponding keyboard key:

```
.-------.    .-------.
| 1 | 2 |    | Q | W |
|---+---| -> |---+---|
| 3 | 4 |    | A | S |
'-------'    '-------'
```

# Key bindings

Key | Action
----|-------
Mod + Q, W, A, S | switch to next window in field 1, 2, 3, 4
Mod + Shift + Q, W, A, S | move window to field 1, 2, 3, 4
Mod + Control + Q, W, A, S | set window size to 1x1, 2x1, 1x2, 2x2
Mod + Tab | switch to next window
Mod + Shift + Tab | switch to previous window
Mod + Escape | kill window
Mod + Shift + Escape | exit

# Usage

Default keys:
```
tawm
```
Custom keys:
```
tawm u i j k
```
