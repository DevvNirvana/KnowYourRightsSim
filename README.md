# ⚖️ Know Your Rights: Elite Simulator

> **Tactical Legal Simulator** > *An immersive, educational simulation designed to teach United States Constitutional rights through high-stakes, gamified scenarios.*

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🔗 Live Demo

**[Play the Live Simulation](https://know-your-rights-sim.vercel.app/)**

---

## 📖 About The Project

**Know Your Rights: Elite Simulator** bridges the gap between legal education and interactive gaming. In real-world encounters with law enforcement or employers, split-second decisions matter. 
This simulator allows users to practice those decisions in a safe environment, providing immediate feedback on the legality and strategic effectiveness of their choices.

Built with a **mobile-first "Cyberpunk" aesthetic**, the app transforms dry legal text into an engaging experience using high-fidelity visual effects, sound design, and responsive UI.

### Core Philosophy
* **Education First:** Every scenario is grounded in real legal principles (4th, 5th, 6th Amendments, FLSA, OSHA).
* **Tactical Decision Making:** Users must balance asserting their rights with de-escalation strategies.
* **Accessibility:** Fully bilingual (English/Spanish) to reach a wider audience.

---

## 🚀 Key Features

### 🛡️ 4 Tactical Modules
1.  **Law Enforcement:** Navigate traffic stops, street encounters, and interrogations (Terry stops, Miranda rights).
2.  **Home Privacy:** Handle warrantless knocks, landlord intrusions, and "plain view" risks (Castle Doctrine).
3.  **Civil Rights:** Exercise First Amendment rights regarding public recording and peaceful protest.
4.  **Workplace:** Identify and resist wage theft, harassment, and unsafe working conditions (OSHA/FLSA).

### 🌍 Bilingual Support (New in v2.0)
* **Real-Time Localization:** Instantly toggle between **English** and **Spanish** (`EN / ES`) without reloading the page.
* **Localized Content:** All scenarios, feedback, and UI elements are fully translated.

### 📱 "Smart Layout" Responsive Design
* **Mobile-First Architecture:** * **Mobile:** Compact, touch-friendly "Strip Layout" prevents scrolling and maximizes screen real estate.
    * **Desktop:** Expands into a spacious, premium "Card Grid" layout.
* **Glitch-Free Experience:** Optimized CSS handling eliminates unwanted scrollbars and visual overflow.

### ⚡ Immersive Visuals & Audio
* **Electric Border Engine:** Custom HTML5 Canvas animation creates dynamic neon sparks that react to the module category (Blue, Green, Red, Yellow).
* **Atmospheric Backgrounds:** Features rotating "Light Bacjground" (Three.js) and cinematic "CRT Signal Noise" text effects.
* **Soundscape:** Integrated `Tone.js` audio engine for UI interactions and ambient tension.

### 📚 Legal Resource Integration
* **Dashboard Library:** Direct access to external resources from the **ACLU**, **OSHA**, and **Department of Labor**.
* **Contextual Learning:** The "Mission Report" provides specific legal citations relevant to the mistakes made during gameplay.

---

## 🛠️ Tech Stack

This project is built with vanilla web technologies, requiring no build steps or heavy frameworks.

* **Core:** HTML5, JavaScript (ES6+), CSS3
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN)
* **Visuals:** * [Three.js](https://threejs.org/) (3D Background FX)
    * HTML5 Canvas (Electric Borders & Fuzzy Text)
* **Audio:** [Tone.js](https://tonejs.github.io/) (Synthesized Sound FX)
* **Fonts:** Orbitron, Rajdhani, Share Tech Mono (Google Fonts)

---

## 📦 Installation & Setup

Since this is a static web application, you can run it instantly.

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/yourusername/know-your-rights-sim.git](https://github.com/yourusername/know-your-rights-sim.git)
    ```

2.  **Run the Application**
    * Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, Safari).
    * *Recommended:* For the best experience (to avoid local CORS issues with textures/audio), run it via a local server like the **VS Code "Live Server" extension**.

---

## 🎮 How to Play

1.  **Initialize:** Enter your "Codename" to boot up the system.
2.  **Select a Module:** Choose a category (e.g., Law Enforcement).
3.  **Survive the Encounter:** Read the scenario prompt and select the best legal response before the timer runs out.
    * **Correct:** +100 Points (Green Flash) - Legally sound and strategic.
    * **Neutral:** +50 Points (Yellow Flash) - Legal, but maybe not the smartest tactic.
    * **Wrong:** -1 Life (Red Flash) - Illegal action, rights waiver, or dangerous escalation.
4.  **Review:** Receive a Mission Grade (S, A, B, F) and review relevant legal precedents to learn from mistakes.

---

## ⚠️ Disclaimer

> **This application is an educational simulation based on general United States Constitutional principles.** >
> Laws vary significantly by state, local jurisdiction, and specific circumstances.
> This application **does not constitute legal advice**. Users should always consult with a qualified attorney for specific legal counsel.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👨‍💻 Author

**TTR**
* GitHub: [@DevvNirvana](https://github.com/DevvNirvana)
* Live App: [know-your-rights-sim.vercel.app](https://know-your-rights-sim.vercel.app/)
