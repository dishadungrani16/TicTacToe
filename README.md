# TicTacToe
A modern, visually appealing Tic-Tac-Toe game built with HTML, CSS (using Tailwind CSS), and JavaScript. It features a sleek, dark-themed design with glassmorphism and aurora-style background effects. The game includes score tracking, a smooth winning line animation on a canvas, and a result modal.

## Live Demo

Play the game live on Netlify\! [**[tictactoe-disha.netlify.app/]**](https://www.google.com/search?q=https://your-netlify-site-name.netlify.app) 🎮

-----

## Features

  - **Responsive Design**: Playable on both desktop and mobile devices.
  - **Modern UI/UX**: Uses **Tailwind CSS** for styling, with custom glassmorphism and animated aurora background effects.
  - **Interactive Gameplay**:
      - Clickable game board with hover effects.
      - Animated `X` and `O` marks.
  - **Game State Management**:
      - Tracks the current player and game status.
      - Automatically checks for a winner or a draw after each move.
  - **Winning Animation**: A dynamic line is drawn across the winning combination using the `<canvas>` API.
  - **Scoreboard**: Keeps a running tally of wins for Player `X` and Player `O`.
  - **Game End Modal**: A clean, animated modal appears to announce the winner or a draw.
  - **Easy Restart**: Buttons for "New Game" and "Play Again" to quickly reset the board while keeping the score.

## Technologies Used

  - **HTML5**: For the semantic structure of the game.
  - **CSS3**: Custom styles for animations, glassmorphism, and the aurora background.
  - **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
  - **JavaScript**: Powers the game logic, DOM manipulation, event handling, and canvas drawing.

## How to Play

1.  Open the live demo link.
2.  Player `X` goes first.
3.  Click on any empty cell to place your mark.
4.  The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins\!
5.  If all nine squares are full and no player has three marks in a row, the game is a draw.
6.  Click "New Game" or "Play Again" to start a new round.
