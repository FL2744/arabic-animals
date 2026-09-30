<p align="center"><img src="assets/arabic-animals-logo.png" alt="Fox illustration from the Arabic Animals game" width="180"></p>

# Arabic Animals

An HTML Language Game for Arabic, created for **AI and Global Languages** at Virginia Tech.

**[Open the Game](https://l1001.vt.domains/arabic-animals.html)** · [Course website](https://l1001.vt.domains/)

## How to play

Look at the animal illustration and choose its Arabic name from four options. English clues appear only after you answer, along with the correct Arabic word and a transliteration.

- Play 50 rounds with one point for each correct answer.
- See immediate feedback and your running score.
- Review your final score, then play again with shuffled animals and answer choices.

The game uses common Modern Standard Arabic animal names and includes a mythical animal. Illustrations are emoji, so their appearance may vary across devices.

## Run locally

Download this repository and open `arabic-animals.html` in a modern browser. Keep `l1001-home.svg` beside it so the home button displays correctly.

No installation, API key, or server is required. The game logic runs in the browser.

## Files

- `arabic-animals.html` — the complete game, including styles, vocabulary, and JavaScript.
- `l1001-home.svg` — the home button linking to the course website.
- `assets/fox.png` — the fox illustration shown above, captured from the game.

## Teaching and customization

This project demonstrates how a small HTML application can support language practice. Students can inspect the code, evaluate the vocabulary and feedback, and adapt the idea to other topics or languages.

The `animals` array in `arabic-animals.html` contains each animal’s emoji, Arabic name (`ar`), English name (`en`), and transliteration (`tr`). If you change the number of entries, also update the fixed round and score totals in the interface.
