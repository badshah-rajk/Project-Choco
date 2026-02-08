# Project-Choco
Cocoa-GPT 🍫 is an AI-powered digital chocolate box. It uses Three.js for 3D pulsing hearts, Gemini AI to write custom Hinglish poetry, and TTS to whisper them aloud. Wrapped in a "Dark Cocoa" glassmorphism UI with buttery-smooth scrolling, it’s a high-tech love letter that never melts. ✨💖
# 🍫 Chocolate Day: AI-Powered Romantic Experience 💖

A premium, interactive web experience designed for that special someone. This project blends 3D graphics, smooth animations, and Artificial Intelligence to create a digital chocolate box that never empties.

---

## ✨ Features

* 🎨 **3D Visuals:** A floating, pulsing 3D heart rendered using **Three.js** with a metallic gold and silk pink finish.
* 🤖 **AI Poet:** Integrated with **Gemini 1.5 Flash** to generate unique, soulful romantic poetry on demand.
* 🎙️ **AI Voice:** A "Listen" feature that converts the generated poem into a warm, gentle voice using Gemini TTS.
* ✨ **Particle Magic:** Interactive floating emojis (🍫, 💖, ✨) creating a dreamlike atmosphere.
* 🎵 **Ambient Sound:** Integrated background music (Warm Acoustic Guitar) with custom glassmorphism controls.
* 📱 **Responsive Design:** Fully optimized for both desktop and mobile "Angels."

---

## 🚀 Getting Started (Run on your PC)

Follow these steps to get the magic running locally:

### 1. Setup the Folder 📂
1. Create a folder named `ChocolateDay`.
2. Save the code as `index.html` inside that folder.
3. Place your music file (e.g., `music.mp3`) in the same folder.

### 2. Get your AI Magic (API Key) 🔑
1. Visit [Google AI Studio](https://aistudio.google.com/).
2. Click **Get API Key**.
3. In `index.html`, find `const apiKey = "..."` (Line 144) and paste your key there.

### 3. Launch the Experience 🌐
Since the project uses external APIs and 3D libraries, it’s best to run it through a local server:
* **VS Code Users:** Install the **Live Server** extension, right-click `index.html`, and select "Open with Live Server."
* **Python Users:** Open your terminal in the folder and type `python -m http.server 8000`, then go to `localhost:8000` in your browser.

---

## 🛠️ Customization Guide

### 🎵 Changing the Music
To change the vibe, find the `<audio>` tag and update the source:
```html
<audio id="bg-music" loop>
    <source src="your-song-name.mp3" type="audio/mpeg">
</audio>
✍️ Editing the MessageSearch for the romantic-msg class in the code to change the Hinglish text or the main greeting. You can make it as personal as you want!🎨 Changing ColorsThe "Chocolate" theme is defined at the top under :root. You can swap the Cocoa brown for her favorite color:--dark-cocoa: Background--gold-accent: Buttons and Headers--glow-pink: The 3D Heart📦 Tech StackComponentTechnologyEngineHTML5, CSS3, JavaScript (ES6+)3D GraphicsThree.jsAnimationsAnime.js & Lenis ScrollIntelligenceGoogle Gemini APIStylingBootstrap 5📜 LicenseMade with ❤️ and 🍫 for a very special person.“Duniya mein kitni bhi chocolate kyun na ho, par mere liye sabse meethi cheez tumhari smile hai.”
Would you like me to help you write a specific **system prompt** for the Gemini API to ensure the poet
