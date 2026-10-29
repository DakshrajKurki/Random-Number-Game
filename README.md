# 🎲 Random Number Guessing Game

A browser game where you guess a secret number between **1 and 100** in **5 attempts**, with "too high / too low" hints. The page is served by a small HTTP server written in **Java** (a Python server is included as an alternative).

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)

## Features

- Random target number each round
- Input validation (1–100 only)
- Attempt counter, win / game-over messages and a restart button

## Project structure

```
Random Number Guessing/src/
├── Main.java     # Java HttpServer that serves the game on port 8000
├── server.py     # alternative Python server
├── index.html    # game page
├── script.js     # game logic
└── style.css     # styling
```

## Run it

**With Java** (from the `Random Number Guessing` folder):
```bash
javac src/Main.java -d out && java -cp out Main
```
**Or with Python** (from `src`):
```bash
python3 server.py
```
Then open http://localhost:8000.

---
**Dakshraj Singh Chandawat** · [GitHub](https://github.com/DakshrajKurki) · [LinkedIn](https://www.linkedin.com/in/dakshraj-singh-chandawat-0a6349314)
