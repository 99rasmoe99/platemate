📘 PlateMate — Fast vs Healthy Builder
Smart, visual meal comparison for real‑world eating decisions
PlateMate is a lightweight, cinematic nutrition tool that lets users compare Fast Food vs Healthy Plates side‑by‑side using a clean, animated UI. Built for speed, clarity, and real‑life decision‑making, PlateMate helps users instantly see calories, macros, and health scores — all powered by a JSON‑driven architecture.

✨ Features
🔄 Fast vs Healthy Plate Comparison  
Instantly compare two meals with calories, macros, and health scoring.

🥗 Smart Visual UI  
Animated arrows, gold glow highlights, micro‑badges, and clean macro bars.

📊 Accurate Macro Engine  
Uses real numbers — no NaN, no undefined values.

🧩 Modular Architecture  
All data is JSON‑driven, making it easy to expand or swap food items.

📱 Responsive Layout  
Works smoothly on desktop, tablet, and mobile.

🎨 Cinematic Dark Premium Theme  
Designed to match the ETHIO•KCAL ecosystem with Royal Ethiopian Gold accents.

📂 Project Structure
Code
root/
│── index.html
│── styles.css
│── script.js
│── foods.json
│── assets/
│     ├── icons/
│     ├── images/
│     └── ui/
Key Files
index.html — Main UI layout

styles.css — Dark Premium + Gold theme

script.js — Logic for comparison, scoring, and UI updates

foods.json — Centralized food dataset (clean, normalized, 86 items)

🧠 How It Works
PlateMate reads from foods.json, loads two selected meals, and calculates:

Total Calories

Protein / Carbs / Fat

Health Score (0–100)

Visual comparison indicators

Fast vs Healthy winner

All calculations are done client‑side for speed and privacy.

📦 Installation
No dependencies. No build tools.
Just clone and run.

bash
git clone https://github.com/your-repo/platemate.git
cd platemate
open index.html
Or drag the folder into your browser.

🛠️ Customization
Add or Edit Foods
Open foods.json and add items using the schema:

json
{
  "id": 1,
  "name": "Grilled Chicken",
  "category": "Healthy",
  "calories": 220,
  "protein": 35,
  "carbs": 0,
  "fat": 8,
  "description": "Lean grilled chicken breast with clean macros."
}
Change UI Theme
Modify variables in styles.css:

css
:root {
  --gold: #d4af37;
  --dark-bg: #0d0d0d;
  --card-bg: #1a1a1a;
}
📸 Screenshots (Optional Section)
You can add screenshots later:

Code
/assets/screenshots/
🚀 Roadmap
Add Plate A/B image upload

Add share/export feature

Add macro rings + animated score meter

Add multi‑plate comparison mode

Add ETHIO•KCAL integration bridge

🤝 Contributing
Pull requests are welcome.
For major changes, open an issue to discuss what you’d like to improve.

📜 License
MIT License — free to use, modify, and build on.

💛 Credits
Designed & developed by Mohammed  
Part of the ETHIO•KCAL ecosystem — a premium, culturally authentic nutrition experience.