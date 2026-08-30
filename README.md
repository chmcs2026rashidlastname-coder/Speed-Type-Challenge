# ⌨️ Speed Type Challenge

A browser-based typing speed game that allows two players to compete against each other across multiple difficulty levels.

The game measures typing speed, accuracy, and completion time, then compares both players' results to determine the winner.

## 🎮 Features

- 👥 Two-player typing competition
- 🎯 Four difficulty levels:
  - Easy
  - Medium
  - Hard
  - Expert
- ⏱️ Different time limits for each difficulty level
- 📊 Real-time WPM (Words Per Minute) calculation
- 🎯 Real-time typing accuracy calculation
- 🏆 Player vs Player result comparison
- 🥇 Automatic winner determination
- 📋 Top 10 leaderboard
- 🔄 Replay / New Match functionality
- 📱 Responsive design for different screen sizes
- ✨ Interactive typing feedback with correct/incorrect character highlighting

## 🕹️ How to Play

1. Enter the names of Player 1 and Player 2.
2. Click **Start Match**.
3. Select a difficulty level.
4. Click **Start Test**.
5. Type the displayed text as accurately and quickly as possible.
6. Once Player 1 finishes, Player 2 takes their turn.
7. After both players finish, their:
   - WPM
   - Accuracy
   - Time Taken
   are compared.
8. The game displays the final winner.

## 🎯 Difficulty Levels

| Level | Time Limit |
|-------|------------|
| Easy | 60 seconds |
| Medium | 45 seconds |
| Hard | 30 seconds |
| Expert | 20 seconds |

Each level contains different typing passages with increasing difficulty.

## 📊 Game Statistics

The game tracks:

- **WPM** — Words Per Minute
- **Accuracy** — Percentage of correctly typed characters
- **Time Taken** — Time required to complete the challenge
- **Time Remaining** — Countdown based on the selected difficulty

WPM is calculated using the standard typing measurement of **5 characters = 1 word**.

## 🏆 Winner Calculation

The game compares both players based on:

1. Completion time
2. Typing accuracy

If one player is both faster and more accurate, that player wins.

If the players have different strengths (for example, one is faster while the other is more accurate), a combined score is used to determine the winner.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- DOM Manipulation
- JavaScript Event Handling
- Responsive Web Design

## 📁 Project Structure

```text
Speed-Type-Challenge/
│
└── Speed_Type_Challenge.html
