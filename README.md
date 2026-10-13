# 🚲 TrailTuned AI

**Precision Mountain Bike Setup & Trail Advisor**  
*An offline-first, keyless Progressive Web App (PWA) powered by on-device browser AI (WebGPU & WebLLM).*

![TrailTuned AI Banner](https://images.unsplash.com/photo-1576435728678-68d0fbf94e91?auto=format&fit=crop&w=1200&q=80)

## ✨ Features

- **100% Keyless & Serverless:** Runs entirely on-device inside modern mobile and desktop browsers using WebGPU. No API keys, no subscriptions, and no cloud server bottlenecks.
- **Offline-First PWA:** Install it directly to your phone's home screen (Android Chrome or iOS Safari). Once the lightweight model downloads on first launch, it works completely offline out on deep mountain trails with zero cell service.
- **Structured Tuning & Tables:** Generates clear, easy-to-read spec tables and bulleted configuration breakdowns for suspension air pressure, sag percentages, clicker settings, and tire pressures.
- **Quick Bike Presets:** Instantly load geometries and component builds for modern bikes (e.g., Intense Tazer e-MTB, Specialized Kenevo SL, Trek Fuel EX, Intense Tracer).
- **GPS Trail Location Detection:** Automatically detects your riding location via device GPS or manual input.
- **Trailside Mechanic Chat:** Ask follow-up questions about high-speed compression, rebound damping, or cockpit ergonomics right from the trail.

---

## 🚀 Getting Started

1. Visit the live app: [Link to your GitHub Pages URL]
2. Select a quick preset or enter your bike specs and rider weight in full gear.
3. Tap **"Tune Ride"** to initialize the on-device AI. *(Note: The first launch downloads a lightweight, quantized ~1GB model securely into your browser's local IndexedDB cache. Subsequent loads are instant.)*
4. View your custom side-by-side suspension tables and head out to the trail!

---

## 🛠️ Tech Stack

- **Frontend:** Tailwind CSS, Alpine.js
- **AI Engine:** WebLLM (`Llama-3.2-1B-Instruct`) running via WebGPU
- **Storage:** Browser `localStorage` & IndexedDB
- **Hosting:** GitHub Pages

---

## 📄 License

MIT License &copy; 2026 TrailTuned AI
Step 3: Announcing the Update to Users
If you are sharing this update with friends, riding buddies, or community groups (like on Reddit, local MTB groups, or Discord), you can use this clean announcement template:

🚀 Major Update to TrailTuned AI: Now 100% Keyless & Offline!

I’ve completely rebuilt TrailTuned AI to run entirely on-device using WebGPU and WebLLM.

No more API keys or frustrating "High Demand" server errors.

Runs on mobile (Android Chrome and iOS Safari).

Works completely offline—once you load it once, you can take it out to remote trailheads with zero cell reception.

Clean Spec Tables: The AI now outputs clean, side-by-side suspension tables and bullet points so you can check your clickers and PSI instantly at the trailhead.

Give it a spin at and let me know how it handles your local trails!
