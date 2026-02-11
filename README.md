🥔 Brotato-Style Mini Clone (HTML5 Canvas)

A lightweight Brotato-inspired survival shooter built using pure HTML, CSS, and JavaScript (no frameworks, no external libraries).

This project recreates core mechanics of wave-based arena survival games including:

Auto-firing weapons

Multiple weapon types

Wave progression

Enemy scaling

Between-wave shop system

Modular game architecture

🎮 Features
⚔️ Combat System

Auto-targeting weapons

Multiple simultaneous weapons

Projectile spread (Shotgun)

High fire-rate weapons (SMG)

Enemy HP scaling per wave

🧱 Weapon Types
Weapon	Damage	Cooldown	Special Trait
Pistol	Medium	Medium	Balanced
SMG	Low	Fast	Rapid fire
Shotgun	Medium	Slow	Multi-projectile spread

Weapons stack — you can own multiple at once.

🌊 Wave System

20-second waves

Increasing enemy HP and speed per wave

Automatic shop phase between waves

🛒 Shop System

Opens automatically between waves

Spend materials earned from kills

Buy additional weapons

Weapons immediately added to your loadout

🧠 Architecture

The game is structured in modular OOP style:

Game
 ├── Player
 │    ├── Weapons[]
 │
 ├── Enemy[]
 ├── Bullet[]
 └── Shop System

Core Classes

Game → Main loop, wave control, enemy spawning

Player → Movement, health, money, inventory

Weapon → Fire logic, cooldown, projectile generation

Enemy → AI movement & scaling

Bullet → Projectile physics & collision

This structure makes it easy to extend with:

Boss waves

Weapon rarities

Stats system (crit, lifesteal, etc.)

Item merging

New enemy types

🕹 Controls
Key	Action
W	Move Up
A	Move Left
S	Move Down
D	Move Right

Weapons fire automatically.

🚀 How To Run

Create a file called:

index.html


Paste the full game code into it.

Open it in your browser.

That’s it. No build tools required.

📦 Tech Stack

HTML5 Canvas

Vanilla JavaScript (ES6 classes)

CSS for UI styling

No external dependencies.

🔥 Possible Improvements

If you want to take it further, here are expansion ideas:

Weapon rarity system (Common / Rare / Epic)

Merge mechanic (combine duplicates)

Passive stat upgrades

Boss enemies

Particle effects

Sound effects

Save system (localStorage)

Procedural item pool

Better enemy AI

Mobile support

Gamepad support

📜 License

Free to use and modify for learning or portfolio projects.

💡 Inspiration

Inspired by arena survival games like Brotato and similar auto-shooter roguelites.
