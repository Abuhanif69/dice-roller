# Dice Roller

Simple web-based dice roller built with HTML, CSS and JavaScript.

Preview

- Click the dice square or the "Roll the Dice" button to roll a die.

Features

- Single die roll (defaults to a 6-sided die).
- Small rolling animation and friendly message after each roll.

Files

- [index.html](index.html) — main UI and structure.
- [style.css](style.css) — styling and animation.
- [main.js](main.js) — roll logic and UI interactions.

Run locally

1. Open `index.html` directly in your browser, or serve the folder and open it:

```bash
# from the project folder
python -m http.server 8000
# then open http://localhost:8000
```

Customization

- Change the number of sides by editing the `DICE_SIDES` constant in [main.js](main.js).
- Adjust animation timing with `ROLL_DURATION` and `ROLL_INTERVAL` in [main.js](main.js).

Notes

- The project is deliberately tiny and dependency-free.
- If you want multiple dice or other enhancements, see the TODO ideas in the project issues or ask me to implement them.

License

- Public domain / use however you like.
