# GroupB-ScoreBroad 🏆

A Python program that simulates and analyzes match results for **Group B** of the FIFA World Cup.  
It calculates each team's wins, losses, draws, goal difference, and points, then ranks them based on official tournament rules.

---

## 📊 Features

- Input match results via terminal (e.g. `1-2`)
- Automatically updates team statistics:
  - Wins
  - Losses
  - Draws
  - Goal Difference
  - Points
- Sorts teams by:
  1. Points
  2. Wins
  3. Alphabetical order
- Displays final standings in a clean, readable format

---

## ⚙️ How It Works

1. The program prompts the user to enter scores for 6 matches:
   - Iran vs Spain
   - Iran vs Portugal
   - Iran vs Morocco
   - Spain vs Portugal
   - Spain vs Morocco
   - Portugal vs Morocco

2. Each input should follow the format: `ScoreA-ScoreB`  
   Example: `Iran vs Spain: 1-2`

3. After all inputs, the program calculates and prints the final standings like this:


---

## 🚀 Getting Started

### 🔧 Requirements
- Python 3.x

### ▶️ Run the program

```bash
python main.py


GroupB-ScoreBroad/
│
├── main.py           # Main script to run the program
├── README.md         # Project documentation
└── .gitignore        # (Optional) Ignore unnecessary files
