# Language Writing Practice Tool

![Start Screen](/screenshots/startscreen.png)
![Example](/screenshots/example.png)
A browser-based language writing and typing practice tool built with vanilla JavaScript, HTML, and CSS.  
The application focuses on accuracy-based progression, timed completion, difficulty levels, and special character input for language learning.

This project emphasizes DOM manipulation, real-time input validation, and game-style feedback without using any frameworks.

---

## Features

- Multiple difficulty levels (Easy, Normal, Hard)
- Sentence-by-sentence typing progression
- Real-time character-level validation
- Visual feedback for correct and incorrect input
- Error tracking and scoring system
- Best-time tracking per session
- Support for special characters (German umlauts via keyboard shortcuts)
- Start, reset, and replay flow
- Clean, self-contained frontend logic

---

## Tech Stack

- JavaScript (ES6)
- HTML5
- CSS3
- No frameworks or external libraries

---

## Project Structure

```text
public/
├── index.js        # Core game logic and input handling
├── style.css       # Styling and UI states
└── index.html      # Application markup
```

---

## How the Tool Works

1. The user selects a difficulty level.
2. A predefined set of sentences is loaded.
3. Each sentence is rendered character-by-character.
4. User input is validated in real time.
5. Errors must be corrected before continuing.
6. Content progresses only when a sentence is typed correctly.
7. Completion time and score are calculated at the end.
8. Best completion time is tracked per session.

---

## Difficulty Modes

- Easy  
  Full sentences are visible while typing.

- Normal  
  Sentences gradually fade after several characters.

- Hard  
  Full sentence visibility is limited, increasing memory and accuracy difficulty.

---

## Special Character Input

The tool supports German umlauts using keyboard shortcuts:

- \a → ä
- \A → Ä
- \o → ö
- \O → Ö
- \u → ü
- \U → Ü

These sequences are converted automatically while typing.

---

## Key Concepts Demonstrated

### DOM Manipulation

- Dynamic character rendering
- Real-time class toggling for correctness
- UI state transitions without frameworks

### Game Logic

- Error-based progression control
- Score calculation based on accuracy
- Time measurement and comparison

### Input Handling

- Character-level comparison
- Custom keyboard shortcuts
- Controlled progression flow

---

## Getting Started

### Run Locally

This project does not require any build tools.

```bash
git clone https://github.com/your-username/language-writing-tool.git
cd language-writing-tool
open index.html
```

For best results, use a local development server.

---

## Possible Improvements

- Persistent high scores using localStorage
- Custom text input by the user
- Additional languages
- Mobile-friendly layout
- Refactoring into modular JavaScript files

---

## What This Project Demonstrates

- Strong vanilla JavaScript skills
- Real-time input validation
- State management without frameworks
- Interactive UI design
- Language-learning focused UX logic

---

## License

This project is open source and available under the MIT License.
