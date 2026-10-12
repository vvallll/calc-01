# Calc—01

A calculator in a single HTML file: keys styled after the Apple Magic Keyboard, frosted glass operators, an acrylic "folder" display held by screws, and a paper tape that keeps your history.

**Open it:** https://vvallll.github.io/calc-01/

## Features

- Order of operations and brackets (nested; unclosed ones close themselves), power `^`, factorial `!`, percent, `√`, `x²`, `±`.
- Pressing `=` again repeats the last step: `2 + 3 = 5`, then `8`, `11`…
- History on a paper tape: pull it out, scroll through it, tap a row to reuse its result. The `clear ×` button wipes the tape.
- Click the display to copy the number.
- Light and dark themes, key sounds, works on phones.

## Keyboard

| Keys | Action |
|---|---|
| `0–9`, `.` or `,` | enter a number |
| `+` `−` `*` `/` | operators |
| `Shift` + `1` `5` `6` `8` `9` `0` | `!` `%` `^` `*` `(` `)` |
| `Enter` or `=` | calculate |
| `Backspace` | erase the last digit |
| `Esc` | clear everything |
| `F1`–`F4` | `±` `%` `√` `x²` |
| `Cmd`/`Ctrl` + `C` | copy the result |
| `T` `S` `H` `G` | theme, sound, tape, grid |

On a phone, long-press a key to enter the symbol printed above its digit.

## How it's built

One `index.html` file with no build step and no dependencies; the Martian Mono typeface loads from Google Fonts. To run it locally, just open the file in a browser.
