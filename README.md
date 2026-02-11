# 🥔 BROTATO - Enhanced Wave Survival

A browser-based wave survival game inspired by Brotato, featuring intense action, multiple characters, diverse weapons, and strategic upgrades.

![Game Type](https://img.shields.io/badge/Type-Wave%20Survival-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Browser-blue)
![Status](https://img.shields.io/badge/Status-Playable-success)

## 🎮 About

Survive waves of enemies as a brave potato warrior! Each wave lasts 40 seconds, after which you can purchase weapons and upgrades in the shop. Choose your character wisely, manage your resources, and build the ultimate potato warrior.

## ✨ Features

### 🎭 6 Unique Characters
- **🥔 Brotato** - Balanced all-rounder with standard stats
- **🏹 Ranger** - Fast ranged attacks with low HP and high dodge
- **🛡️ Tank** - High HP and armor but slow movement
- **🍀 Lucky** - High crit chance and dodge for risky players
- **🔧 Engineer** - Starts with extra materials for early advantage
- **🐂 Bull** - Massive damage output at the cost of speed

### ⚔️ 11 Different Weapons
- **Melee Weapons**: Stick, Knife, Hammer, Wrench, Club
- **Ranged Weapons**: Pistol, SMG, Shotgun
- **Special Weapons**: Rocket Launcher, Laser, Flamethrower

Each weapon has unique stats:
- Damage
- Attack Speed
- Range
- Pierce (how many enemies projectiles pass through)
- Spread (accuracy)
- Projectile count (shotgun fires 5 pellets!)

### 👾 5 Enemy Types
- **👾 Basic** - Standard balanced enemy
- **💨 Runner** - Fast but fragile
- **🛡️ Tank** - Slow but very tanky
- **💣 Exploder** - Explodes on death, dealing area damage
- **🎯 Shooter** - Fires projectiles at you from range

### ⬆️ 12 Upgrades
- **❤️ Max HP+** - Increase maximum health
- **👟 Speed+** - Move faster
- **💪 Damage+** - Deal more damage
- **⚡ Attack Speed+** - Attack faster
- **🛡️ Armor+** - Reduce incoming damage
- **💨 Dodge+** - Chance to avoid damage
- **💥 Crit Chance+** - Deal double damage
- **🎯 Range+** - Increase weapon range
- **🔱 Pierce+** - Bullets pierce more enemies
- **🩸 Lifesteal** - Heal on hit
- **🌾 Harvesting** - More materials per kill
- **💚 HP Regen** - Regenerate health over time

## 🎯 How to Play

### Controls
- **W/A/S/D** or **Arrow Keys** - Move your character
- **Mouse** - Aim (weapons auto-fire at nearest enemy)

### Gameplay Loop
1. **Select Your Character** - Choose from 6 unique characters
2. **Survive the Wave** - Last 40 seconds against enemy hordes
3. **Shop Phase** - Spend materials on weapons and upgrades
4. **Repeat** - Each wave gets progressively harder

### Strategy Tips
- **Balance your build** - Don't neglect defense for pure damage
- **Manage your materials** - Save for expensive weapons or spend on upgrades
- **Know your weapons** - Shotguns excel close-range, lasers for pierce
- **Positioning matters** - Keep moving to avoid being surrounded
- **Reroll wisely** - Shop rerolls cost 20 materials
- **Character synergy** - Match weapons to your character's strengths

## 🔧 Technical Details

### Built With
- **HTML5 Canvas** - For rendering
- **Vanilla JavaScript** - No frameworks, pure JS
- **CSS3** - Modern styling with gradients and animations
- **Google Fonts** - Press Start 2P and Outfit fonts

### Game Systems
- **Entity System** - Player, enemies, bullets, particles
- **Collision Detection** - Circle-based collision
- **Weapon System** - Auto-targeting with cooldowns
- **Upgrade System** - Stat multipliers and bonuses
- **Wave Scaling** - Enemy HP/damage scales with wave number
- **Particle Effects** - Visual feedback for hits and deaths
- **Screen Shake** - Impact feedback
- **Damage Numbers** - Floating combat text

## 🚀 Installation & Usage

### Method 1: Direct Download
1. Download `brotato_enhanced.html`
2. Open the file in any modern web browser
3. Start playing!

### Method 2: Local Server (Recommended)
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Then navigate to:
# http://localhost:8000/brotato_enhanced.html
```

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Recommended resolution: 1920x1080 or higher

## 🎨 Customization

### Modify Game Constants
Edit these values in the JavaScript section:

```javascript
const WAVE_DURATION = 40000; // Wave length in milliseconds
```

### Add New Characters
Add to the `CHARACTERS` object:

```javascript
newchar: {
  name: 'New Char',
  icon: '🎮',
  desc: 'Description here',
  maxHp: 100,
  speed: 3.5,
  // ... other stats
}
```

### Add New Weapons
Add to the `WEAPON_DEFS` object:

```javascript
newgun: {
  name: 'New Gun',
  icon: '🔫',
  cost: 30,
  desc: 'Description',
  damage: 10,
  speed: 1.5,
  // ... other stats
}
```

### Add New Upgrades
Add to the `UPGRADE_POOL` array:

```javascript
{
  name: 'New Upgrade',
  icon: '⭐',
  desc: 'Description',
  apply: p => { /* modify player stats */ }
}
```

## 🐛 Known Issues

- None currently reported

## 🗺️ Roadmap

Potential future features:
- [ ] Boss enemies every 5 waves
- [ ] More characters and weapons
- [ ] Power-ups that drop from enemies
- [ ] High score system with localStorage
- [ ] Sound effects and music
- [ ] Mobile touch controls
- [ ] Endless mode after wave 20
- [ ] Character unlocks based on achievements

## 📝 Version History

### v1.0.0 (Current)
- Initial release
- 6 characters
- 11 weapons
- 5 enemy types
- 12 upgrades
- Complete shop system
- Visual effects and polish

## 🤝 Contributing

Feel free to fork and modify! Some ideas for contributions:
- Add new characters with unique mechanics
- Design new weapons with special effects
- Create boss enemies with attack patterns
- Add visual themes or skins
- Implement difficulty modes
- Add achievements system

## 📄 License

This is a fan project inspired by Brotato. Free to use and modify for personal and educational purposes.

## 🙏 Acknowledgments

- Inspired by **Brotato** by Blobfish
- Uses **Press Start 2P** font by CodeMan38
- Uses **Outfit** font by Rodrigo Fuenzalida

## 📧 Contact

For bugs, suggestions, or improvements, feel free to open an issue or submit a pull request.

---

**Enjoy the game and may your potato reign supreme! 🥔👑**
