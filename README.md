# Simple Quiz Game

A lightweight **Question & Answer** quiz game built using **only HTML, CSS, and JavaScript** — no frameworks, no build tools. Perfect for beginners, classroom demos, or embedding in small websites.

---

## Demo

Open `questifys.netlify.app/` in your browser to run the quiz locally.

---

## Features

* Pure **HTML / CSS / JS** (vanilla JavaScript)
* Multiple-choice questions
* Score counting
* Next / Previous question navigation
* Simple timer (optional)
* Responsive, minimal UI

---

## Getting Started

1. Download or clone the project.
2. Open `index.html` in any modern browser.

---

## File Structure

```
simple-quiz/
├── index.html        # Main HTML file
├── style.css         # Styling
├── script.js         # Game logic
└── README.md         # This file
```

---

## index.html (what it contains)

* A container for the quiz
* Elements for question text, choices, controls (Next, Previous, Submit)
* A results screen to show the final score

---

## script.js (high-level)

* An array of question objects: `{ question, options: [], answerIndex }`
* Functions to: render a question, handle option selection, advance questions, calculate score, and show results
* Optional: timer that counts down per question

---

## Example Question Object

```js
{
  question: "What is the capital of France?",
  options: ["London", "Berlin", "Paris", "Rome"],
  answerIndex: 2
}
```

---

## Customization Tips

* Add new categories by organizing multiple question arrays.
* Persist scores with `localStorage` for a simple leaderboard.
* Improve UX: highlight correct/incorrect answers, animate transitions, add sound effects.
* Make it into a multiplayer live quiz later by integrating WebSocket or Firebase (advanced).

---

## Accessibility

* Use semantic HTML (`button`, `ul`, `li`) so keyboard users can navigate choices.
* Ensure focus styles are visible and color contrast is sufficient.

---

## License

This project is released under the **MIT License**. Feel free to copy, modify, and use.

---

## Want Starter Files?

If you want, I can also generate a ready-to-use `index.html`, `style.css`, and `script.js` with a small set of sample questions so you can run the game immediately. Just tell me to create them and I'll add them to the canvas.
