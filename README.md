# ល្បែងសិក្សា សាលាបឋមសិក្សា ស្រែរាជ (srereach School)
## Wordwall-Style Interactive Educational Suite with Direct Google Gemini AI

An interactive educational platform designed for Cambodian primary school teachers and students. Runs 100% client-side in any modern web browser without server dependencies.

---

### ✨ Features & Capabilities

1. **🌿 4 Switchable Themes**:
   - **Jungle Forest** (Default): Emerald green & amber gold tones.
   - **Classic Colorful**: Educational slate navy & deep blue.
   - **Cosmic Space**: Deep midnight nebula with neon cyan & purple.
   - **Arcade Neon**: Cyberpunk dark with high-contrast electric green and pink.

2. **🔊 Zero-Dependency Web Audio API Synthesizer (`js/audio.js`)**:
   - Procedurally synthesizes bubble pop, card flip swoosh, chime match chords, wrong buzzer, mystery box fanfare, wheel ratchet clicks, wooden mallet whack thuds, and victory celebrations.

3. **🎉 HTML5 Canvas Particle Confetti (`js/particles.js`)**:
   - Smooth 60fps physics engine with dual celebration cannons.

4. **🇰🇭 / 🇬🇧 Bilingual Internationalization (`js/i18n.js`)**:
   - Instant 1-click language switching between Khmer and English across all UI elements and games.

5. **🎮 7 Interactive Game Engines**:
   - 🃏 **Matching Pairs (បណ្ណផ្គូផ្គង)**: 3D flip cards, preview all mode, deck reshuffling.
   - 🧩 **Match Up (ផ្គូផ្គង)**: Split interactive columns with animated red strikethrough and checkmark badges.
   - 🎯 **Quiz Gameshow (សំណួរចម្លើយ)**: Big-screen question cards, countdown timer, lives, and streak multiplier.
   - 🎁 **Open The Box (បើកប្រអប់អាថ៌កំបាំង)**: 3D numbered mystery boxes with hidden answers and confetti reveals.
   - 🎡 **Student Wheel Picker & Team Maker (កង់ចាប់ឈ្មោះសិស្ស & ចែកក្រុម)**: High-resolution Canvas roulette with customizable duration (slider, direct input, unit selector, chips), and animal mascot group generator with clipboard copy.
   - 🔠 **Word Search Grid (ស្វែងរកពាក្យក្នុងតារាង)**: 8x8 Khmer syllable matrix strictly preserving Khmer consonants, sub-consonant subscripts (ជើង), dependent vowels, and diacritics.
   - 🔨 **Whack-a-Mole (វាយសត្វកណ្តុរ)**: 3x3 burrows with pop-up animation, mallet thud sound, combos, and direct Whack Studio launcher.

6. **✨ Direct Google Gemini AI Studio Quiz & Vision Generator (BYOK)**:
   - Generate quizzes directly using Google Gemini 2.0 Flash / 1.5 Flash.
   - Multimodal inputs: Text prompts with presets, Textbook Camera Photo OCR (Vision), and PDF lesson uploads.

7. **🎨 Activity Creator Studio & Dedicated Whack Studio**:
   - Create, edit, export, and import lesson activities in `.json` format.
   - Auto-saves to `localStorage`.

---

### 🚀 Quick Start & Local Hosting

Simply open `index.html` in any modern browser (Chrome, Edge, Safari, Firefox), or run a lightweight local static server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .
```

### 🌐 Deploying to GitHub Pages

1. Push all files to your GitHub repository.
2. In your repository on GitHub, go to **Settings** > **Pages**.
3. Under **Branch**, select `main` (or `master`) and folder `/ (root)`.
4. Click **Save**. Your educational suite is live!
