# RSS Puzzle 🧩

An interactive linguistic mini-game designed to enhance English language skills through gamified sentence assembly. Players piece together scrambled words to form correct sentences, progressively uncovering hidden classic artwork masterpieces. Built entirely from scratch using pure TypeScript.

🔗 **[Live Demo](https://morevna.github.io/rss-puzzle/)**

---

## 🛠️ Tech Stack & Architecture

- **Language & Tooling:** TypeScript (strict mode configuration), Vite bundler.
- **UI & Graphics:** Native HTML5 Canvas API (dynamic image slicing), responsive semantic layout.
- **Interactivity:** Native HTML5 Drag-and-Drop API, Web Audio APIs.
- **Architecture:** Modular component-based design without third-party UI frameworks.

---

## 🚀 Key Technical Features

- **Dynamic Canvas Puzzle Slicing:** Engineered an automated puzzle engine using HTML5 Canvas. The application programmatically splits classic artwork images into responsive word-card shards based on dynamic sentence and text metrics.
- **Fluid Drag-and-Drop Pipeline:** Implemented seamless, barrier-free word-card drag-and-drop mechanics to support intuitive layout sorting, manual reordering, and snap-to-grid slot assembly.
- **Multi-Tiered Interactive Hints:** Integrated synchronized media sub-systems including dynamic audio pronunciation tracking, client-side translation overlays, and background picture contrast toggles.
- **State Persistence & Progression:** Linked a custom user authorization portal backed by browser `localStorage` to securely track user profiles, state progress across 6 core difficulty levels (3,600 total phrases), and round achievements.
- **Rich Interactive Statistics:** Developed a comprehensive results viewport categorizing correctly/incorrectly solved phrases, rendering on-the-fly audio replays, and displaying original artwork metadata upon round completion.
