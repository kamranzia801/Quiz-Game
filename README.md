# Quiz-Game
I used copilot ai for the documentation

# Quiz Game

A simple browser quiz app built with HTML, CSS, and JavaScript. It shows multiple-choice questions, tracks the player's score, and displays a final result message.

## Features
- Start screen and restart flow
- Multiple-choice answers
- Correct/incorrect answer highlighting
- Live score update
- Progress bar
- Responsive layout

## Project files
- `index.html` — app structure and screens
- `style.css` — design and responsive styling
- `script.js` — quiz logic, questions, scoring, and screen transitions

## How it works
1. The app loads the start screen.
2. Clicking Start begins the quiz.
3. Each question is rendered dynamically from the `quizQuestions` array.
4. When a user selects an answer, the script checks it and updates the score.
5. After a short delay, the next question loads.
6. After the last question, the result screen shows the final score and a performance message.

## Customize questions
Edit the `quizQuestions` array in `script.js`:

```js
const quizQuestions = [
  {
    question: "What is the capital of France?",
    answers: [
      { text: "London", correct: false },
      { text: "Paris", correct: true }
    ]
  }
];
```

## Run it
Open `index.html` directly in a browser, or serve the folder locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes
This is a beginner-friendly frontend project and does not store data permanently.
