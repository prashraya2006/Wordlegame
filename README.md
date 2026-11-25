# Wordle Clone (React + Vite)

## Run
```
npm install
npm run dev
```
Open the printed localhost URL.

## Structure
- `src/App.jsx` – central state (solutionWord, currentGuess, pastGuesses, gameStatus), input handlers, keydown listener
- `src/components/` – GameBoard, Row, Tile, Keyboard, Modal
- `src/utils/evaluate.js` – green/yellow/gray scoring (handles duplicate letters) and keyboard status merging
- `src/utils/words.js` – solution word list
- `src/styles.css` – conditional `.correct` / `.present` / `.absent` classes
