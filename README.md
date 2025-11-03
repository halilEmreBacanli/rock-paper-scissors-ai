# Rock-Paper-Scissors AI Game

**CENG 3511 - Artificial Intelligence Midterm Project**

Rule-based AI opponent for Rock-Paper-Scissors game

---

## 📖 Description

This project implements a Rock-Paper-Scissors game with an intelligent AI opponent that uses rule-based strategies to predict and counter player moves.

### AI Strategies:
1. **Pattern Recognition** - Detects when player repeats same move 3 times
2. **Frequency Analysis** - Counters player's most-used move

---

## 🚀 Setup Instructions

### Requirements
- Python 3.x (no external libraries needed)

### How to Run

1. **Download the file:**
```bash
   git clone https://github.com/halilEmrebacanli/rock-paper-scissors-ai.git
   cd rock-paper-scissors-ai
```

2. **Run the game:**
```bash
   python rock_paper_scissor_ai_game.py
```

3. **Play:**
   - Enter number of rounds
   - Type your choice: `rock`, `paper`, or `scissors`
   - View your statistics at the end

---

## 🎮 Game Rules

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
- Win: +1 point | Loss: -1 point | Tie: 0 points

---

## 🤖 AI Logic

- **First 2 rounds:** Random moves (collecting data)
- **Round 3+:** AI analyzes your history and uses strategies
- **Priority:** Pattern Recognition → Frequency Analysis → Random

---

## 📊 Features

- Input validation
- Move history tracking
- Win rate calculation (excluding ties)
- Round-by-round score display

---

## 👤 Author

Halil Emre Bacanlı  
CENG 3511 - Artificial Intelligence  
Fall 2025

---

## 📄 License

This project is for educational purposes.
