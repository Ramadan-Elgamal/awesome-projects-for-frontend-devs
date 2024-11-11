# 🎯 WordWiz
> A fun, interactive Hangman game to guess words and track scores.

## 📋 Project Scale: Small
Expected timeline: 1-2 weeks

## 🎯 Core Purpose
WordWiz is a Hangman game that allows users to guess a hidden word letter by letter. The game tracks scores, displays remaining attempts visually, and provides real-time feedback with animations. This project will focus on game state management, word-guessing logic, and SVG animations for visual feedback.

## ⚡ Features Breakdown

### Phase 1 (Essential - Start Here)
- [ ] **Word Generation** - Create a pool of words and select one randomly for each new game.
- [ ] **Letter Guessing Logic** - Implement logic to check if guessed letters are correct and update the word display.
- [ ] **Game State Management** - Track and update remaining attempts and display game over messages.

### Phase 2 (Near Future - Next 1-2 weeks)
- [ ] **SVG Animations** - Use SVG graphics to visually display parts of the Hangman with each wrong guess.
- [ ] **Score Tracking** - Keep a score of games won/lost and display it on the screen.
- [ ] **Keyboard Input** - Add an on-screen keyboard for mobile-friendliness, and highlight guessed letters.
- [ ] **Game Reset** - Implement a button to restart the game with a new word and reset states.

### Phase 3 (Future Expansion)
- [ ] **Difficulty Levels** - Add options for easy, medium, and hard levels, adjusting word length or attempts.
- [ ] **Hints** - Allow players to use a hint that reveals a letter at the cost of an attempt.
- [ ] **Leaderboard** - Track high scores locally or via a backend to display a leaderboard.

### Libraries to try
- [ ] **react-spring** - For smooth animations when letters are guessed correctly or incorrectly.
- [ ] **react-svg** - For easier management of SVG graphics for Hangman drawings.
- [ ] **zustand or Redux** - For game state management across components.

## 📚 Implementation Resources
- [ ] [react-spring documentation](https://react-spring.io/docs)
- [ ] [SVG Basics on MDN](https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial)
- [ ] [zustand documentation](https://docs.pmnd.rs/zustand/getting-started/introduction)

## 💡 Live Examples
• [Hangman Online](https://hangmanwordgame.com/): A simple Hangman game with score tracking.
• [Coolmath Games Hangman](https://www.coolmathgames.com/0-hangman): A beginner-friendly Hangman game with hints and animations.