# 4Game

A fun and engaging 4-in-a-row game (Connect Four style) built with modern web technologies. Play against the computer or challenge a friend!

## 📋 Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features
- 🎮 Single-player mode (play against AI)
- 👥 Two-player mode (local multiplayer)
- 🤖 Smart AI opponent with difficulty levels
- 🎨 Responsive and intuitive UI
- ⚡ Real-time game state updates
- 📱 Mobile-friendly design
- 🔊 Sound effects and animations

## 🎮 Demo
Play the game online: [4Game Live Demo](#)

## 🚀 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Clone the Repository
```bash
git clone https://github.com/romankhanal4/4game.git
cd 4game
```

### Install Dependencies
```bash
npm install
```

### Run the Application
```bash
npm start
```

The app will open in your browser at `http://localhost:3000`

## 🎯 Usage

1. **Start Game**: Click "New Game" button
2. **Select Mode**: Choose between Single Player or Two Player
3. **Play**: Click on columns to drop your piece
4. **Win**: First player to get 4 pieces in a row (horizontal, vertical, or diagonal) wins!
5. **Reset**: Click "Reset" to start a new game

### Game Controls
- **Mouse Click**: Select column to place piece
- **Keyboard**: Use arrow keys to select column (optional)

## 📖 Game Rules

1. The game board is 7 columns × 6 rows
2. Players alternate turns dropping pieces from the top
3. Pieces fall to the lowest available position in the column
4. First player to connect 4 pieces in a row wins
5. If board fills up with no winner, the game is a draw

## 💻 Technologies

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Game Logic**: Minimax Algorithm for AI
- **Build Tool**: Webpack
- **Testing**: Jest

## 📁 Project Structure
```
4game/
├── src/
│   ├── index.html
│   ├── styles/
│   │   └── style.css
│   ├── js/
│   │   ├── game.js
│   │   ├── ai.js
│   │   └── ui.js
│   └── assets/
│       ├── sounds/
│       └── images/
├── public/
├── package.json
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Roman Khanal**
- GitHub: [@romankhanal4](https://github.com/romankhanal4)

## 📞 Support

For support, email your-email@example.com or open an issue on GitHub.

---

Made with ❤️ by Roman Khanal
