# 🎲 Dice Roll Simulator

A simple dice roll simulator built with HTML, CSS, and vanilla JavaScript. Click the button to roll the dice, and every roll gets added to a history list with its dice image.

<img width="897" height="882" alt="image" src="https://github.com/user-attachments/assets/37918d1a-e2af-4ba4-9b20-7a3b3c165ee4" />


## Features

- Roll a die with one click
- Dice face image updates to match the result
- Roll history: each roll is added to a list as `Roll 1: 🎲`, `Roll 2: 🎲`, and so on
- Built with no libraries or frameworks

## How it works

1. Clicking the button generates a random number from 1 to 6 using `Math.random()`.
2. The dice image on the page is swapped to the matching face.
3. A new `<li>` is created with the roll number and the dice image, then appended to the history list using DOM manipulation.

## Tech used

- HTML
- CSS
- JavaScript (DOM manipulation, event listeners)

## Run it locally

```bash
git clone https://github.com/your-username/dice-roll-simulator.git
cd dice-roll-simulator
```

Then open `index.html` in your browser, or use the VS Code Live Preview extension.

## What I learned

- Generating random numbers with `Math.random()` and `Math.floor()`
- Creating and appending elements with `document.createElement()`
- Handling click events

## Ideas for improvement

- Roll multiple dice at once
- Add a rolling animation
- Show the total of all rolls
- Add a button to clear the history
