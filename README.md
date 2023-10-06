# alty key map

Non-modal keymap for text editors.

## Concept

- Non-modal editing
  - Every shortcut should be available without mode change.
  - Every shortcut can be used with a single stroke with modifiers
- Use alt key mainly
  - Since every alt key can be pressed with thumbs, prevent RSI...
  - Most common shortcuts are not using alt key. Live together with them...!
- Easy to move cursor without moving hands from qwerty area.
  - Use `hjkl` for cursor movement, as vim does.
  - Use `yuio,.<>`, which are near to `hjkl` for additional cursor movement.
- Selection without arrow key
  - All cursor movement shortcuts use left alt and right Alphabet keys.
  - Just press shift additionaly to select range.
- Inherit common shortcuts
  - For example, `C-z`, `C-x`, `C-c`, `C-v`, `C-a`, `C-f` from common apps.
  - Palette shortcuts `C-p` and `C-S-p` from Atom, VSCode, zed, etc.
- Pane shortcuts
  - Use `A-\`, `A-'`, `A-|` for pane toggle.

## Shortcut list

See key-list.md

## Installation

Open each editors and append the contents of keymap file.
