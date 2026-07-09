# Developer Achievement System | 開發者成就系統

🌐 **Languages**: [繁體中文](README.md) | [English](README.en.md)

An interactive milestone tracker, technology stack visualizer, and profile generator designed for software engineers, developers, and open-source contributors. Features a clean, editor-inspired tile aesthetic.

🔗 **Live App**: [https://ivanusto.github.io/developer-achievement-list/](https://ivanusto.github.io/developer-achievement-list/)

This is a fully static client-side web application. Your progress is saved automatically in your browser's local cache (LocalStorage). No signup or installation required!

---

## 🌟 Key Features

1. **Dashboard & Leveling System**: Calculates player levels (1 level per 10 achievements) and dynamic coder ranks (e.g., `🌱 Hello World Rookie`, `🐛 Bug Catcher`, `🌐 System Architect`, `🧙‍♂️ Software Arch-Mage`).
2. **22-Node Tech Stack Grid**: An interactive technology grid representing 5 core engineering domains (Frontend, Backend, DevOps, CS & AI, and Tools). Click a technology to "light it up" and calculate your domain coverage.
3. **Canvas Radar Chart**: Rendered natively on HTML5 Canvas without any external JS dependencies, visualizing your domain mastery.
4. **100 Relatable Milestones**: 100 achievements across 10 categories, ranging from basic syntax up to ultimate challenges (and Steam-style hidden achievements).
5. **10 Developer Badges**: Wall of honor badges like `⌨️ Keyboard Warrior`, `🎨 Pixel Perfect`, `💾 Database Guru`, and `🔥 Server Down Survivor` unlocked based on your accomplishments.
6. **One-Click Share Card (PNG)**: Dynamically renders an 800x1200 high-res card featuring your nickname, level, tech stack progress, radar profile, unlocked badges, and top-3 achievements for social sharing.
7. **Double Theme support**: Toggle between Cyberpunk IDE Dark mode (Default) and Code Editor Light mode.
8. **Backup & Restore**: Export/Import your progress as a simple JSON file for syncing across devices.
9. **Zero Server Backend**: 100% serverless static HTML loading instantly. Respects user privacy.
10. **Custom Achievements**: Create up to 10 of your own custom achievements and track them alongside official milestones.

---

## 🛠️ Technical Details

- **Core**: HTML5 / Vanilla CSS / Vanilla JavaScript (ES6)
- **Graphics/Export**: HTML5 Canvas API (adjusted for high-DPI/Retina screens)
- **Audio synthesis**: Web Audio API (programmatic retro synthesizer)
- **Animations**: CSS Keyframes + Canvas 2D Particle System (Confetti)
- **Storage**: LocalStorage API
- **Internationalization**: Integrated client-side i18n translation dictionary

---

## 📄 License

Licensed under the MIT License.
Inspired by and adapted from [taiwan-travel-achievement-list](https://github.com/ivanusto/taiwan-travel-achievement-list).
