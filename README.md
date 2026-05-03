# ตออบขี้ Clicking Simulator 🎮

A fun and addictive clicking game where you make the text "ตออบขี้" grow bigger with every click until it EXPLODES! 💥

**Live Demo:** [https://garuh143.github.io/clicking-simulator](https://garuh143.github.io/clicking-simulator)

## Features

✨ **Core Gameplay**
- Click to make "ตออบขี้" text grow bigger
- Text explodes when too big, giving bonus currency
- Track your total clicks and currency
- Beautiful particle effects on clicks
- Floating animation for the text

🛒 **Upgrade Shop**
- **Click Upgrades** - Boost your click power (Basic, Double, Triple, Super, Mega, Ultra)
- **Text Colors** - Customize text color (White, Yellow, Pink, Cyan, Orange, Green)
- **Background Themes** - Beautiful gradient backgrounds (Purple, Blue, Red, Green, Dark, Rainbow)
- **Custom Cursors** - Change your cursor style (Default, Hand, Crosshair, Grab, Emoji)

💰 **Progression System**
- Earn currency with every click
- Spend currency on upgrades
- Auto-save progress to browser
- Explosion count tracking
- Exponential difficulty curve

## How to Play

1. **Click** the "ตออบขี้" text to make it grow
2. **Earn** currency with each click
3. **Open the shop** (🛒 button) to buy upgrades
4. **Upgrade** your click power to earn faster
5. **Customize** colors, backgrounds, and cursors
6. **Watch** the text explode and earn bonus currency!

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS (via CDN)
- **Vanilla JavaScript** - Game logic
- **localStorage** - Progress persistence
- **CSS Animations** - Smooth effects

## Local Development

Simply open `index.html` in your browser - no build process required!

```bash
# Clone the repo
git clone https://github.com/garuh143/clicking-simulator.git

# Open in browser
open index.html

# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## Deployment

This project is hosted on **GitHub Pages**. 

**How to deploy:**
1. Push changes to the `master` branch
2. GitHub Pages automatically builds and deploys
3. Site available at: `https://garuh143.github.io/clicking-simulator`

**GitHub Pages Settings:**
- Source: Deploy from a branch
- Branch: `master` → `/ (root)`

## Game Mechanics

### Click Power Formula
```
Total Power = Base Click Power + All Upgrade Bonuses
```

### Currency Formula
```
Currency Earned = Click Power × Number of Clicks
```

### Explosion Bonus
```
Bonus = 100 × Explosion Count
```

### Economy Balancing
- **Early Game**: ~10-20 clicks for first upgrade
- **Mid Game**: ~50-100 clicks per upgrade
- **Late Game**: ~500-1000 clicks per upgrade

### Upgrade Costs
| Upgrade | Cost | Power |
|---------|------|-------|
| Basic Click | 10 | +1 |
| Double Click | 50 | +2 |
| Triple Click | 150 | +3 |
| Super Click | 500 | +5 |
| Mega Click | 2,000 | +10 |
| Ultra Click | 10,000 | +25 |

## Project Structure

```
clicking-simulator/
├── index.html          # Complete game (HTML + CSS + JS)
└── README.md           # This file
```

**Simple and lightweight - no build process needed!**

## Features Breakdown

### 🎨 Visual Effects
- Floating animation on text
- Pulse effect on clicks
- Explosion animation
- Particle effects (stars, sparkles, emojis)
- Smooth transitions

### 🛍️ Shop Categories

**⚡ Upgrades (6 items)**
- Increase click power
- Progressive costs
- Exponential scaling

**🎨 Colors (6 items)**
- White, Yellow, Pink, Cyan, Orange, Green
- Instant text color change

**🌈 Backgrounds (6 items)**
- Purple Dream, Ocean Blue, Sunset Red
- Forest Green, Dark Mode, Rainbow
- Beautiful gradients

**🖱️ Cursors (5 items)**
- Default, Hand Pointer, Crosshair, Grab, Emoji
- Custom cursor styles

### 💾 Persistence
- Auto-saves to localStorage
- Resumes where you left off
- No login required

## Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers

## Performance

- **Load time**: < 1 second
- **File size**: ~20 KB (HTML only)
- **No dependencies** (Tailwind via CDN)
- **Optimized animations** (CSS transforms)

## Tips for Players

1. **Start with upgrades** - Boost your click power early
2. **Trigger explosions** - Get bonus currency at 200px text size
3. **Customize your game** - Make it look how you want
4. **Keep clicking** - Progress saves automatically
5. **Aim for Ultra Click** - The ultimate power upgrade!

## Future Enhancements

Possible features to add:
- Auto-clicker upgrades
- Multiplier system
- Achievement system
- Leaderboard
- More themes and colors
- Sound effects
- Mobile app version

## Contributing

This is a personal project, but feel free to:
- Fork the repository
- Make improvements
- Submit pull requests

## License

Made with 💜 by garuh143

---

**Enjoy the game!** 🎮✨
