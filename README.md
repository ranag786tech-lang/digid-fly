# 🚀 DIGID FLY

> **Infinite Jetpack Runner** — A fast-paced 2D browser game with stages, boss battles, and unlockable characters.

![DIGID FLY](https://img.shields.io/badge/DIGID%20FLY-v1.0-00ffff?style=for-the-badge&labelColor=010208)
![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-bf00ff?style=for-the-badge&labelColor=010208)
![License](https://img.shields.io/badge/License-MIT-00ff88?style=for-the-badge&labelColor=010208)

---

## 🎮 Play Now

🔗 **[Play DIGID FLY](https://YOUR-USERNAME.github.io/digid-fly)**

> Replace `YOUR-USERNAME` with your actual GitHub username after deployment.

---

## 📖 About the Game

DIGID FLY is a Jetpack Joyride / Mario-style 2D runner built entirely in HTML5 Canvas. No downloads, no installs — play instantly in your browser on desktop or mobile.

**The pilot flies through a neon cyberpunk world**, dodging electric zappers, laser beams, and homing missiles — with epic Boss Battles every 5 stages!

---

## 🕹️ How to Play

| Control | Action |
|---------|--------|
| **Hold SPACEBAR** | Jetpack UP |
| **Release SPACEBAR** | Fall down |
| **Hold Screen (mobile)** | Jetpack UP |
| **Release Screen** | Fall down |

**Goal:** Fly as far as possible, collect coins, clear stages, and defeat bosses!

---

## ✨ Features

### 🎯 Core Gameplay
- Smooth jetpack physics with gravity
- 3 obstacle types: **Zapper Walls**, **Missiles**, **Laser Beams**
- Coin collection with multiple patterns (lines, arcs, singles)
- Increasing difficulty per stage

### 🗺️ Stage System
- Unlimited stages with progressive difficulty
- **Every 5th stage = BOSS BATTLE**
- Stage Clear screen with score summary
- Distance progress bar

### 👹 Boss Battles
- Massive neon drone boss with rotating arms
- **Phase 1:** Single targeted projectiles
- **Phase 2 (50% HP):** Triple spread shots
- Survive the boss to advance!

### 🔓 4 Unlockable Characters
| Character | Unlock | Special Ability |
|-----------|--------|-----------------|
| 🔵 **BLAZE** | Default | Standard runner |
| 🟡 **VOLT** | Stage 3 | +20% speed boost |
| 🟣 **PHANTOM** | Stage 6 | 30% chance to dodge hits |
| 🔴 **NOVA** | Stage 10 | Coin magnet range |

### 💰 Monetization Ready
- **Google AdSense** placeholder (easy to activate)
- **Ad Banner** at top of game
- Privacy Policy & Terms pages included

---

## 🚀 Deploy to GitHub Pages

### Step 1: Upload Files
```bash
# Upload all files to your repository:
index.html
privacy-policy.html
terms.html
README.md
```

### Step 2: Enable GitHub Pages
1. Go to your repo **Settings**
2. Click **Pages** in the left sidebar
3. Source: **Deploy from a branch**
4. Branch: **main** → **/ (root)**
5. Click **Save**

### Step 3: Your game is live!
```
https://YOUR-USERNAME.github.io/REPO-NAME
```

---

## 💵 Setup Google AdSense

### Step 1: Apply for AdSense
1. Visit [adsense.google.com](https://adsense.google.com)
2. Sign in with Gmail
3. Enter your GitHub Pages URL
4. Wait 2-4 weeks for approval

### Step 2: Add AdSense Code to `index.html`
Find this comment in `index.html` and replace it:

```html
<!-- FIND THIS (around line 20): -->
<!--
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=YOUR_PUBLISHER_ID" crossorigin="anonymous"></script>
-->

<!-- REPLACE WITH YOUR CODE: -->
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
```

### Step 3: Add Ad Unit in the Banner
Find `id="adTop"` and replace the comment with your ad unit:

```html
<ins class="adsbygoogle"
     style="display:inline-block;width:728px;height:50px"
     data-ad-client="ca-pub-XXXXXXXXXXXXXXXXX"
     data-ad-slot="XXXXXXXXXXXXXXXXX"></ins>
<script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
```

---

## 🏗️ Project Structure

```
digid-fly/
├── index.html          ← Main game (all-in-one HTML file)
├── privacy-policy.html ← Privacy Policy page (required for AdSense)
├── terms.html          ← Terms & Conditions page
└── README.md           ← This file
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5 Canvas** | Game rendering |
| **Vanilla JavaScript** | Game engine, physics, AI |
| **CSS3** | UI, animations, neon effects |
| **Google Fonts** | Orbitron + Rajdhani |
| **localStorage** | Save data (scores, unlocks) |
| **Google AdSense** | Monetization |

---

## 📊 Revenue Potential

| Players/Month | Avg Ad Revenue | Annual |
|---------------|----------------|--------|
| 1,000 | ~$5–15 | ~$60–180 |
| 10,000 | ~$50–150 | ~$600–1,800 |
| 100,000 | ~$500–1,500 | ~$6,000–18,000 |

> *Estimates vary based on audience geography and ad CTR*

---

## 🔧 Customization

### Change Game Speed
In `index.html`, find:
```javascript
const G = 0.36;        // Gravity strength
const LIFT = -0.72;    // Jetpack power
let spd = 3;           // Starting scroll speed
```

### Change Stage Length
```javascript
const STAGE_DIST = 4200;  // Pixels per stage
```

### Add/Change Boss Stages
```javascript
const BOSS_STS = new Set([5,10,15,20,25,30]);  // Boss at these stage numbers
```

### Change Boss Duration
```javascript
const BOSS_HP_T = 28 * 60;  // 28 seconds × 60fps
```

---

## 📜 License

MIT License — Free to use, modify, and distribute.

---

## 🤝 Credits

Built with ❤️ using pure HTML5, Canvas API, and JavaScript.

**Game:** DIGID FLY v1.0  
**Engine:** Custom Canvas2D  
**Font:** Orbitron by Matt McInerney  

---

> *"The sky is not the limit — it's just the beginning."* 🚀
