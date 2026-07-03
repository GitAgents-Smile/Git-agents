# Git Agents 🤖

### Deploy Autonomous AI Agents — Landing Page & Auth Demo

*A single-page marketing site for an AI agent deployment platform, with a working client-side login/register flow.*

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)
![Made with HTML/CSS/JS](https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-FF6A3D?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-34D399?style=for-the-badge)

[🌐 Live Preview](#-quick-start) · [🐛 Report Bug](../../issues/new?template=bug_report.md) · [💡 Request Feature](../../issues/new?template=feature_request.md)

---

## 📌 About

**Git Agents** is a self-contained landing page built to showcase a fictional platform for deploying autonomous AI agents. It includes:

- 🎨 A fully styled hero section, feature grid, live activity feed, and pricing section
- 🔐 A functional (client-side, in-memory) **Login / Register** modal system
- ⚡ Animated counters, scroll effects, and a hand-drawn "sticker" UI style
- 📱 Responsive layout for desktop and mobile navigation

> ⚠️ **Note:** Authentication in this demo is handled entirely in the browser with an in-memory JavaScript object — there is **no real backend, database, or password hashing**. Do not use this auth logic in production.

---

## 🚀 Quick Start

### Option 1 — Open directly

Just download `index.html` and open it in any modern browser. No build step, no dependencies.

### Option 2 — Clone & run locally

```bash
# Clone the repository
git clone https://github.com/<your-username>/Git-Agents.git
cd Git-Agents

# Serve locally (any static server works)
python -m http.server 8080
# then open http://localhost:8080
```

### Option 3 — GitHub Pages

This repo ships with `.nojekyll` so it can be deployed straight to GitHub Pages:

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://<your-username>.github.io/Git-Agents/`

---

## 📁 Project Structure

```
Git-Agents/
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
├── .gitignore
├── .nojekyll
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── SECURITY.md
└── index.html
```

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎨 **Sticker-style UI** | Hard-shadow "pop" buttons and cards inspired by modern meme-coin/product sites |
| 🔐 **Auth Modal** | Tabbed login/register modal with client-side validation |
| 📊 **Animated Counters** | Stats that count up when scrolled into view |
| 📡 **Live Activity Feed** | Simulated real-time agent deployment feed |
| 📱 **Mobile Nav** | Dedicated logged-in/logged-out states for mobile menu |
| ⌨️ **Keyboard UX** | `Enter` submits forms, `Esc` closes modal |

---

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

1. **Fork** this repository
2. **Create** your branch: `git checkout -b feat/your-feature`
3. **Commit**: `git commit -m 'feat: add your feature'`
4. **Push**: `git push origin feat/your-feature`
5. **Open a Pull Request**

---

## 📄 License

Licensed under the [MIT License](LICENSE) — free to use, modify, and distribute.

---

**⭐ If this project helps you, consider starring the repo!**
