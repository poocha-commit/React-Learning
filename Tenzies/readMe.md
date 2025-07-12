# 🎲 Tenzies Game

A simple and fun React-based implementation of the game **Tenzies**. The objective is to roll the dice until all values are the same. You can click on a die to "hold" its value between rolls. When all dice are held and match, you win — complete with confetti! 🎉

---


## 🚀 Features

- 🎲 Roll 10 dice with values from 1 to 6
- ✋ Click a die to "hold" it at its current value
- 🌀 Re-roll unheld dice
- 🏆 Win the game when all dice are the same and held
- 🎉 Celebrate with confetti animation using `react-confetti`
- ⚡ Smooth UI built with React and custom styling

---

## 🛠️ Built With

- [React](https://reactjs.org/)
- [nanoid](https://github.com/ai/nanoid) — unique IDs for dice
- [react-confetti](https://www.npmjs.com/package/react-confetti) — celebratory animation
- CSS Flex/Grid — responsive and clean layout

---

## 🧩 How to Play

1. Click the **Roll** button to roll all dice.
2. Click on dice to **hold** values you want to keep.
3. Keep rolling until all dice show the same number and are held.
4. When you win, 🎉 confetti appears and you can click **New Game** to play again.

---

## 📦 Installation

```bash
git clone https://github.com/your-username/tenzies-game.git
cd tenzies-game
npm install
npm start
