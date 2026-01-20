# 🎣 WA Fishing Companion

A **Progressive Web App (PWA)** for Western Australian saltwater anglers. 
Provides **tide predictions**, **AI-powered fish intel**, **photo identification**, and **catch logging** — all wrapped in a modern, installable **dark-mode** interface.

## ✨ Features

| Feature | Description | Status |
| :--- | :--- | :---: |
| **🌊 BoM Tides** | Live tide data for 12 major WA ports (Broome to Albany). | ✅ |
| **🧠 AI Fish Intel** | Generates location-specific advice for Day/Night & Shore/Boat using Google Gemini 2.5 Flash. | ✅ |
| **📷 Fish ID** | Take a photo to identify species using AI vision analysis. | ✅ |
| **📓 Catch Log** | Save catches locally with photos, length, and details (offline capable). | ✅ |
| **📱 Installable** | Full PWA support — install to home screen on iOS/Android. | ✅ |
| **🎨 Glass UI** | Modern dark mode with sticky headers and glassmorphism effects. | ✅ |

## 🚀 How to Use

### 1. Installation (iOS/Android)
This is a web app that behaves like a native app.
1. Visit the hosted URL (e.g., `yourusername.github.io/repo-name`).
2. **iOS (Safari):** Tap **Share** → **Add to Home Screen**.
3. **Android (Chrome):** Tap **Menu (⋮)** → **Install App**.

### 2. Setup (AI Features)
To use **Fish Intel** and **Fish ID**, you need a free Google Gemini API key.
1. Get a key at [aistudio.google.com](https://aistudio.google.com/app/apikey).
2. Open the app → Tap **⚙️ Keys** (top right).
3. Paste your key and save. (Stored locally on your device only).

## 🛠️ Development / Deployment

### Structure
- `index.html`: Main app logic and UI.
- `manifest.json`: PWA metadata (icons, colors).
- `sw.js`: Service Worker for offline caching.

### Deploying to GitHub Pages
1. Push code to `main` branch.
2. Go to **Settings** → **Pages**.
3. Set **Source** to `Deploy from a branch` → `main` / `(root)`.
4. Your live URL will appear at the top.

## 🔒 Privacy
- **API Key:** Stored in your browser's `localStorage`. Never sent to any server other than Google's API.
- **Photos/Logs:** Stored locally on your device.

---
*Built for WA Anglers.* 🐟
