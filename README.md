# ⚡ FitGenius.ai

> **AI-Powered Fitness & Macro Intelligence**  
> Progressive Web App (PWA) with 80-rank leveling, workout logger, audio rest timer, and USDA-verified nutrition tracking.

---

## 📱 Install on Android (PWA / WebAPK)

FitGenius is built with modern PWA standards. On Android, Chrome installs it as a **native WebAPK** with its own icon in your App Drawer:

1. Open the live app link in **Google Chrome** on your Android phone:
   👉 **`https://pangnathani.github.io/fitgenius/`**
2. Chrome will show an **"Install FitGenius"** bar at the bottom, OR:
   - Tap the **three vertical dots (⋮)** in the top right corner.
   - Tap **"Install app"** or **"Add to Home screen"**.
   - Tap **Install**.
3. FitGenius is now installed as a standalone app on your Android phone!

---

## 🍏 Install on iPhone (iOS)

1. Open **`https://pangnathani.github.io/fitgenius/`** in **Safari**.
2. Tap the **Share button** (square with upward arrow ⬆️).
3. Scroll down and tap **"Add to Home Screen"**.
4. Tap **Add** in the top right.

---

## 🚀 Key Features

* **🎮 80-Tier Rank Progression**: From Recruit $\rightarrow$ Bronze $\rightarrow$ Silver $\rightarrow$ Gold $\rightarrow$ Platinum $\rightarrow$ Diamond $\rightarrow$ Master $\rightarrow$ Titan $\rightarrow$ Cyber Immortal.
* **⏱️ Interactive Workout Rest Timer**:
  * 3-2-1 Web Audio countdown beeps + celebratory ascending chime on set completion.
  * Instant rest adjusters (`+15s`, `-15s`, `SKIP REST ⚡`).
  * Floating `+XP` popup animation on every completed set.
* **🥗 Precision USDA Nutrition Tracking**:
  * Grounded in USDA FoodData Central (SR Legacy / Foundation Foods).
  * Mifflin-St Jeor TDEE Macro Calculator for Cut, Maintain, or Lean Bulk.
  * AI Meal Solver ("✨ WHAT TO EAT"): suggests meals based on remaining daily calories & protein.
  * AI Camera Food Scanner via Gemini 2.0 Flash multimodal vision.
* **🤖 5 Specialized AI Coach Personas**:
  * *Sergeant Iron* (No-excuse military)
  * *Dr. Wellness* (Warm, science-backed)
  * *Hype Lord* (Maximum chaos & energy)
  * *Master Zen* (Mindful flow)
  * *Data Coach* (Evidence-based periodization)
* **☁️ Cloud & Local Storage**:
  * Seamless sign-in with Google, Apple, or Email.
  * Offline-capable with Service Worker pre-caching.

---

## 🛠️ Local Development

Clone the repository and launch a local web server:

```bash
git clone https://github.com/pangnathani/fitgenius.git
cd fitgenius
python3 -m http.server 8877
```

Open `http://localhost:8877` in your browser.
