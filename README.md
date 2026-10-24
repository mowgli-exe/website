# mowgli

An interactive single-page web application featuring a modern, dark-themed **Bio Portfolio** and an integrated **Mini-Casino** with multiple playable games, level/XP progression, sound effects, dynamic canvas animations, and a real-time global leaderboard powered by Firebase.

## 🌐 Live Demo & Community
* **Website:** [litecoinwallet.netlify.app](https://litecoinwallet.netlify.app/)
* **Discord Community:** [Join our Discord](https://discord.com/invite/36EAyW5Z4F)
* **TikTok:** [@quzeria](https://www.tiktok.com/@quzeria)
* **Guns.lol:** [guns.lol/tpa](https://guns.lol/tpa)

---

## ✨ Features

### 👤 Bio Profile
* **Glassmorphism UI:** Modern frosted-glass aesthetics with mouse-reactive light cones, glowing borders, and animated backgrounds.
* **Tactical ESP Canvas:** Built-in dynamic 3D-style tactical shooter wallhack background.
* **Background Audio Player:** Integrated custom media player with interactive play/pause, volume control, audio equalizer, and smooth track controls.
* **One-Click Links:** Direct links to social platforms and a fast "click to copy" Discord tag button.

### 🎰 Mini-Casino Games
A full play-money casino featuring multiple interactive games:
* 🎰 **Slots:** Multi-line reel slot machine with dynamic payout tables.
* 🎡 **Roulette:** European-style wheel with color, odd/even, and direct number betting options.
* 🃏 **Blackjack:** Standard dealer vs. player blackjack (3:2 payout, double down support).
* 📈 **Crash:** Real-time exponential multiplier line graph — cash out before it crashes!
* 💣 **Mines:** 5x5 grid-based minefield sweeper with customizable bomb counts.
* 🔴 **Plinko:** Multi-tier risk ball drop with realistic pin bounce canvas physics.
* 🎲 **Dice:** Adjustable win probability slider with real-time payout multipliers.
* 🪙 **Coin Flip:** Fast-paced heads/tails flip with streak counters.
* 🎡 **Lucky Wheel:** Wheel-of-fortune spin for instant coin rewards.

### 🏆 Economy & Progression
* **XP & Level System:** Earn XP with every game round to level up.
* **Daily Bonus & Rescue System:** Claim daily rewards or receive rescue coin refills if you run low.
* **Global Leaderboard:** Real-time Firebase Firestore leaderboard tracking players by **Peak Coins**, **Best Win**, or **Level**.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Styling:** CSS Custom Properties, Glassmorphism backdrop-filters, custom `@keyframes` animations
* **Fonts:** `Chakra Petch` & `JetBrains Mono` (Google Fonts)
* **Graphics & FX:** HTML5 Canvas API (3D grid rendering, confetti particles, ambient dust)
* **Audio:** Web Audio API (procedural sound effects) + HTML5 Audio Player
* **Backend / Database:** Firebase Firestore (Realtime Leaderboards)
* **Hosting:** Netlify

---

## 📂 Project Structure

```text
├── index.html        # Main HTML layout, CSS styles, and JS logic (Single File Setup)
├── music.mp3         # Background audio track
├── pfp.jpg           # Profile picture / avatar asset
└── README.md         # Repository documentation
```

---

## 🚀 Getting Started Locally

Since the application is self-contained in `index.html`, running it locally is simple:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
   cd YOUR_REPOSITORY_NAME
   ```

2. **Open `index.html`:**
   * Double-click `index.html` to open it in any modern web browser.
   * Or use an extension like **Live Server** in VS Code for local web server preview.

---

## 🤝 Community & Support

Have feedback, questions, or feature requests? Feel free to open an issue or connect with us on Discord:

[![Discord Banner](https://img.shields.io/discord/100000000000000000?color=5865F2&label=Discord&logo=discord&logoColor=white)](https://discord.com/invite/36EAyW5Z4F)

---

## ⚠️ Disclaimer

*This project is built purely for **entertainment purposes**. All casino games use virtual play money with no real-world monetary value.*
