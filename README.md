# 💎 SpendWise AI — Smart Expense Tracker & Financial Intelligence

[![GitHub Repository](https://img.shields.io/badge/GitHub-maddali23%2Fspendwise-blue?logo=github)](https://github.com/maddali23/spendwise)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Hacktoberfest Challenge](https://img.shields.io/badge/Hacktoberfest-Build%20for%20a%20Friend-purple.svg)](https://dev.to/challenges/hacktoberfest-weekend-2026-10-01)

> An intelligent, privacy-preserving personal financial companion that tracks expenses, analyzes spending patterns, audits recurring subscriptions, and provides actionable recommendations to accelerate your savings.

---

## ✨ Key Features

- **🧠 SpendWise Copilot (Conversational Financial AI)**:
  - Natural language transaction capture (e.g., *"Dinner with client $85 on Amex yesterday"*).
  - Conversational financial query answering (*"How much did I spend on groceries?"*, *"Can I afford a $350 flight?"*).
  - Built-in client-side financial reasoning engine + optional Google Gemini API support.
- **📊 Real-Time Financial Health & Cashflow**:
  - Live Financial Health Score (0–100) based on savings rate and budget discipline.
  - Net cashflow, daily burn velocity, and projected month-end spend.
- **🚨 Automated Anomaly & Spike Detection**:
  - Detects statistical category surges (+35% spikes vs. prior period).
  - Identifies single outlier purchases and velocity overspend warnings.
- **🔄 Recurring Subscriptions & Bills Audit**:
  - Calculates monthly and annualized recurring burden.
  - Flags underutilized or forgotten subscriptions to save hundreds annually.
- **🎯 Category Budgets & Smart Savings Goals**:
  - Visual monthly budget caps with Safe / Warning / Overbudget color-coded meters.
  - Interactive savings milestones with celebratory confetti showers upon fund deposits.
- **🧾 Neural Receipt OCR Scanner Simulation**:
  - Upload physical receipts or test pre-loaded samples (Supermarket, Bistro, Tech accessories) to auto-extract merchant, items, taxes, and totals into your ledger.
- **🔒 100% Local & Privacy First**:
  - All data stays strictly on your device via client-side storage.
  - Full CSV export and JSON backup/restore capabilities. Zero trackers.

---

## 🛠️ Tech Stack

- **Core**: Vanilla HTML5, Modern ES6+ JavaScript Modules
- **Build Tooling**: Vite
- **Styling**: Bespoke Vanilla CSS (CSS variables, dark/light themes, glassmorphism, responsive grid)
- **Data Visualizations**: Chart.js
- **Audio Synthesizer**: Web Audio API
- **Celebration Effects**: Canvas-Confetti

---

## 🚀 Quick Start

### Prerequisites
- Node.js (v18+)

### Installation
```bash
# Clone the repository
git clone https://github.com/maddali23/spendwise.git
cd spendwise

# Install dependencies
npm install

# Start local development server
npm run dev
```

Visit `http://localhost:5173/` in your browser.

### Production Build
```bash
npm run build
npm run preview
```

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|:---:|:---|
| <kbd>N</kbd> or <kbd>+</kbd> | Open **Record Transaction** modal |
| <kbd>C</kbd> | Toggle **SpendWise Copilot** AI drawer |
| <kbd>/</kbd> | Focus **Global Search** bar |
| <kbd>Esc</kbd> | Close active modal or drawer |

---

## 📄 Submission

Built for the **[Hacktoberfest Weekend Challenge: Build for a Friend](https://dev.to/challenges/hacktoberfest-weekend-2026-10-01)**.  
See [HACKTOBERFEST_SUBMISSION.md](./HACKTOBERFEST_SUBMISSION.md) for the complete DEV.to article submission.

---

## 📜 License

MIT License © 2026 [maddali23](https://github.com/maddali23)
