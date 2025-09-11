# Rock-Paper-Scissors Game

A simple browser-based Rock-Paper-Scissors game where you can play against the computer. The game features animated hand gestures, score tracking, and an intuitive interface.

## Project Description

This project implements the classic Rock-Paper-Scissors game with a clean user interface. Players can choose between rock, paper, or scissors, and compete against a computer that makes random choices. The game keeps track of scores and announces the winner of each round.

## Installation

### Prerequisites

- Node.js (v20.1.0 or later recommended)
- Browser-sync (for development server)

### Setup Instructions

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/rock-paper-scissors.git
   cd rock-paper-scissors
   ```

2. Install browser-sync globally:
   ```
   npm install -g browser-sync
   ```

## Running the Development Server

To start the development server with live reloading:

```
browser-sync start --server --no-notify --files "**/*.css, **/*.html, **/*.js"
```

Alternatively, if you're using 1024tools, simply click the "Run" button which is configured to start the server with the appropriate settings.

## Project Structure

- `index.html` - Main HTML structure of the game
- `style.css` - Styling for the game interface
- `script.js` - Game logic and animations
- `assets/` - Directory containing images and sounds:
  - `石头.png` - Rock hand gesture image
  - `剪刀.png` - Scissors hand gesture image
  - `布.png` - Paper hand gesture image
  - `music.mp3` - Background audio file

## How to Play

1. Click the "开始" (Start) button to begin the game
2. Choose your move by clicking one of the three buttons: "石头" (Rock), "布" (Paper), or "剪刀" (Scissors)
3. Watch the animated hand gestures and see who wins the round
4. The score is updated automatically at the top of the screen

## Credits

- Hand gesture images used in this project were created specifically for this game
- Background music: music.mp3