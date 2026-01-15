# Dice Roller

Simple web-based dice roller built with HTML, CSS and JavaScript.

# Dice Roller

Small, dependency-free web dice roller with support for multiple dice and animated rolls.

Preview

- Choose a dice type (d4/d6/d8/d10/d12/d20), set a count, then click the dice area or the "Roll the Dice" button.

Features

- Multi-dice support: roll 1–20 dice at once.
- Variety of dice types: d4, d6, d8, d10, d12, d20.
- Animated rolling with friendly result messages.
- Shows individual die results and the total.
- No external dependencies — plain HTML/CSS/JS.

Files

- [index.html](index.html) — UI and controls.
- [style.css](style.css) — layout and animations.
- [main.js](main.js) — roll logic, UI wiring, and messages.
- [README.md](README.md) — this file.

Run locally

1. Open `index.html` directly in your browser, or serve the folder and open it:

```bash
# from the project folder
python -m http.server 8000
# then open http://localhost:8000
```

Quick usage

- Select the dice type from the dropdown.
- Set how many dice to roll in the Count input.
- Click any die or the "Roll the Dice" button to start the animated roll.

Customization

- Default UI values: edit the dice `<select>` and the count `<input>` in [index.html](index.html).
- Timing: change `ROLL_DURATION` and `ROLL_INTERVAL` in [main.js](main.js) to speed up/slow down the animation.
- Messages: update the `MESSAGES` array in [main.js](main.js).
- Maximum dice: adjust the validation in [main.js](main.js) and the `max` attribute on the count input in [index.html](index.html).

Development notes

- The app is intentionally small and framework-free for portability.
- For charts or persistent history, consider adding Chart.js and localStorage respectively.

License

- Public domain — use and modify freely.
  License

- Public domain / use however you like.
