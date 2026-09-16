# English Learning Games

A single-file, no-build web app with four classroom games for practicing English vocabulary and grammar. Everything — data, logic, and styling — lives in [`index.html`](index.html); no server or build step required.

## Play it

Just open `index.html` in a browser (desktop, tablet, or phone). Nothing to install.

## Game modes

### 🕵 Who Am I?
Two teams, each secretly picks a character. Teams take turns asking yes/no questions (eye color, hair, glasses, height, etc.) to narrow down the other team's pick, cross suspects off the board, and guess the rival's character first to win.

### 🎭 What Am I?
A Heads-Up-style charades game. Stick the phone to your forehead (tilt controls) or pass a tablet around (button controls) — friends describe the word on screen in English and you guess it before time runs out. Categories: People, Animals, Objects, Food, Verbs, or Mixed.

### 🎯 Simon Says
Only follow a command if it starts with "Simon says" — miss that and you're out. Commands mix physical actions, speaking English phrases, Turkish↔English translation, spelling words out loud, and quick math questions. Last player standing wins.

### 🚫 Taboo
One player describes the word on screen in English without saying the word itself — or any of the banned words listed below it. Teammates shout out guesses before time runs out.

## Tech

Plain HTML/CSS/JavaScript, no dependencies or frameworks. Sound effects are synthesized in-browser with the Web Audio API — no audio files needed.
