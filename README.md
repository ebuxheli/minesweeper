# Classic Minesweeper - Built+Documented Using Claude

A nostalgic recreation of the Windows XP Minesweeper game with modern enhancements and classic gameplay.

![Minesweeper Game](https://img.shields.io/badge/Game-Minesweeper-blue)
![Version](https://img.shields.io/badge/Version-1.0-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

![image](https://github.com/user-attachments/assets/4ebe47f4-115a-4098-89c5-801b8eca9345)

## 🚀 Getting Started

Download the `minesweeper.html` file from the repo in any modern web browser. I promise there is no spam-ware.

## 🕹️ How to Play

### Basic Controls
- **Left Click**: Reveal a square
- **Right Click**: Place or remove a flag
- **Click on Number**: Auto-reveal adjacent squares if the correct number of flags are placed
- **Spacebar**: Quick flag (hover over covered square) or chord click (hover over number)

### Game Elements
- **Numbers**: Show count of adjacent mines (1-8)
- **Flags**: Mark suspected mine locations
- **Mine Counter**: Displays remaining unflagged mines
- **Timer**: Tracks solving time (max 999 seconds)
- **Face Button**: 
  - 🙂 Normal
  - 😎 Victory
  - 😵 Game Over

### No dependencies required!
This game is built with vanilla HTML, CSS, and JavaScript - no frameworks or libraries needed.


## 🎯 Strategy Tips

1. **Corners and edges** are great starting points - they have fewer adjacent squares
2. **Use the chord click** feature to quickly clear areas once you've flagged correctly
3. **Save hints** for when you're truly stuck - they're limited!
4. **Master the spacebar** for speed playing - hover and tap for lightning-fast gameplay
5. **Pattern recognition** - learn common mine patterns like 1-2-1 or 1-2-2-1

## 🎮 Features

### Classic Gameplay
- **Three difficulty levels**: Beginner (9x9, 10 mines), Intermediate (16x16, 40 mines), Expert (30x16, 99 mines)
- **Authentic Windows XP styling** with beveled borders and classic gray theme
- **Smart mine placement** - first click is always safe
- **Cascade revealing** - clicking empty squares automatically reveals adjacent areas
- **Chord clicking** - click on numbers with correct flags to reveal remaining adjacent squares

### Modern Enhancements
- **🎯 Smart Hint System**: 3 hints per game that intelligently find the most helpful squares
- **🏅 Medal System**: Earn medals based on performance
  - 🥇 Gold: Win with 0 hints
  - 🥈 Silver: Win with 1 hint  
  - 🥉 Bronze: Win with 2 hints
  - 🙂 Participation: Win with 3 hints
- **🎵 Sound Effects**:
  - Victory trumpet fanfare for wins
  - Sad trombone "duh duuuuuhh" for losses
  - Underwhelming sound for participation trophy
- **🎊 Visual Effects**:
  - Confetti animation on victory
  - Dramatic face animation on game over
  - Medal presentation with custom styling

### Speed Play Features
- **Spacebar functionality** for professional-level speed playing:
  - Quick flag/unflag on covered squares
  - Instant chord click on revealed numbers
- **Hover detection** - no clicking required with spacebar
- **Prevented page scroll** during gameplay

## 🏆 Features Breakdown

### Intelligent Hint System
The hint system uses a sophisticated algorithm to find the most helpful square:
- Prioritizes squares that will reveal large empty areas
- Considers proximity to your active playing area
- Weights squares based on how much information they'll provide
- Never wastes a hint on isolated corners when you're working elsewhere

### Audio System
- Built-in Web Audio API synthesis - no external files needed
- Victory fanfare: ascending C-E-G-C trumpet notes
- Game over: descending "duh duuuuhh" trombone sound
- Participation: underwhelming two-note acknowledgment

### Visual Polish
- Authentic Windows XP theming with proper borders and shadows
- Color-coded numbers matching the original (blue 1s, green 2s, red 3s, etc.)
- Smooth animations for all interactions
- Proper z-index layering for effects

## 🛠️ Technical Details

### Browser Compatibility
- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- Mobile: Touch controls supported (tap for left click, long press for flag)

### Performance
- Efficient rendering using CSS Grid
- Minimal DOM manipulation
- Optimized event handling
- Smooth 60fps animations

## 📝 License

This project is licensed under the MIT License - feel free to use, modify, and distribute.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 🎮 Credits

Inspired by the classic Windows Minesweeper game created by Robert Donner and Curt Johnson at Microsoft.

---

**Enjoy the game and chase that perfect gold medal run! 🥇**
