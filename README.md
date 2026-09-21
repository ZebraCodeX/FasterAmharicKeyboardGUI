# FasterAmharicKeyboardGUI

A desktop keyboard for typing Amharic (Ge'ez) quickly, built with **PyQt5**.
Each key exposes the vowel orders of its fidel family (e.g. ሀ → ሁ ሂ ሃ ሄ ህ ሆ), so
words can be composed with fewer keystrokes.

## Run

```bash
pip install PyQt5
python keyboardAM/board.py
```

## Layout

- `keyboardAM/board.py` — the keyboard window and key layout
- `keyboardAM/board_controller.py` — input handling
