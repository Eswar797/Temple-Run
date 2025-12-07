# 🏛️ Temple Run - Web Edition

A web-based implementation of the popular Temple Run game built with HTML5 Canvas, CSS3, and vanilla JavaScript.

![Temple Run](https://img.shields.io/badge/Game-Temple%20Run-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎮 Game Features

- **Auto-Running Character**: Your character automatically runs forward through the temple
- **3-Lane Movement**: Switch between left, center, and right lanes to avoid obstacles
- **Jumping Mechanics**: Jump over obstacles to stay alive
- **Obstacle System**: Various obstacles including normal and tall obstacles
- **Coin Collection**: Collect coins scattered throughout the path for bonus points
- **Progressive Difficulty**: Game speed increases as you progress, making it more challenging
- **Score System**: Track your score, coins collected, and distance traveled
- **Responsive Design**: Works on both desktop and mobile devices
- **Touch Controls**: Swipe gestures supported for mobile gameplay

## 🎯 How to Play

1. **Start the Game**: Click the "START GAME" button on the welcome screen
2. **Move Left/Right**: 
   - Desktop: Use `←` `→` arrow keys or `A`/`D` keys
   - Mobile: Swipe left or right
3. **Jump**: 
   - Desktop: Press `SPACE` or `↑` arrow key
   - Mobile: Swipe up
4. **Objective**: 
   - Avoid obstacles (hitting one ends the game)
   - Collect coins for bonus points
   - Run as far as possible to achieve a high score

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required!

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Eswar797/Temple-Run.git
cd Temple-Run
```

2. Open `index.html` in your web browser:
   - Simply double-click the file, or
   - Use a local server (recommended):
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

3. Navigate to `http://localhost:8000` in your browser

## 📁 Project Structure

```
Temple-Run/
│
├── index.html      # Main HTML file with game structure
├── style.css       # Styling and UI design
├── game.js         # Game logic and mechanics
└── README.md       # This file
```

## 🎨 Game Mechanics

### Player Movement
- The player automatically runs forward
- Movement is restricted to 3 lanes (left, center, right)
- Smooth lane transitions with easing

### Physics
- Gravity-based jumping system
- Collision detection for obstacles and coins
- Progressive speed increase every 500 frames

### Scoring
- **Distance Score**: Increases as you run further
- **Coin Bonus**: Each coin adds 10 points
- **Final Score**: Distance + (Coins × 10)

## 🛠️ Technologies Used

- **HTML5**: Structure and canvas element
- **CSS3**: Modern styling with gradients and animations
- **JavaScript (ES6+)**: Game engine and logic
- **Canvas API**: 2D rendering for game graphics

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎮 Controls Reference

| Action | Desktop | Mobile |
|--------|---------|--------|
| Move Left | `←` or `A` | Swipe Left |
| Move Right | `→` or `D` | Swipe Right |
| Jump | `SPACE` or `↑` | Swipe Up |

## 🐛 Known Issues

- None at the moment! If you find any, please open an issue.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Created as a fun web game project.

## 🙏 Acknowledgments

- Inspired by the original Temple Run game
- Built with vanilla JavaScript for performance and simplicity

---

**Enjoy the game and see how far you can run! 🏃‍♂️💨**
