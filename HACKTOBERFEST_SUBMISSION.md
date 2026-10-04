*This is a submission for the [Hacktoberfest Weekend Challenge: Build for a Friend](https://dev.to/challenges/hacktoberfest-weekend-2026-10-01)*

# SpendWise AI — A Smart, Privacy-First Financial Companion Built for a Friend

---

## What I Built

My close friend Alex is a talented freelance developer and designer. While Alex excels at building client projects, managing personal finances was a continuous source of anxiety. Alex's income arrives in irregular milestones, and between juggling multiple SaaS subscriptions, cloud servers, groceries, and frequent takeout during late-night coding sessions, Alex was always asking:
* *"Where did my paycheck actually go this month?"*
* *"Can I afford this trip or workstation upgrade right now?"*
* *"Am I accidentally paying for subscriptions I forgot to cancel?"*

Traditional expense trackers were either bloated, riddled with intrusive ads, demanded linking private bank credentials, or required entering tedious manual form fields every single time a coffee was purchased.

To solve this, I built **SpendWise AI** — an intelligent, privacy-first personal expense tracker and financial copilot that understands spending behavior, detects anomalies, audits recurring bills, and delivers tailored savings advice.

### 🌟 Key Features
- **🧠 SpendWise Copilot (Conversational Financial AI)**: Alex can type natural queries like *"Coffee at Blue Bottle $6.50"* or *"Spent $45 on groceries at Trader Joe's yesterday"*. SpendWise parses the merchant, amount, category, date, and payment method instantly with one-click confirmation. Alex can also ask questions like *"How much did I spend on dining out this month?"* or *"Can I afford a $400 weekend getaway?"*.
- **📊 Real-Time Financial Health Score & Burn Rate**: Evaluates monthly savings velocity, cashflow surplus/deficit, and projects month-end burn rate based on daily spending momentum.
- **🚨 Automated Anomaly & Spike Detection**: Automatically flags unusual category surges (e.g., +45% jump in dining out), identifies statistical purchase outliers, and warns if budget velocity will cause month-end overages before they happen.
- **🔄 Recurring Subscriptions Audit**: Identifies active subscriptions, calculates annualized costs, and detects underutilized or redundant services with actionable recommendations.
- **🎯 Smart Savings Goals & Category Budgets**: Sets monthly spending caps per category and tracks tangible goals (Emergency Fund, Tokyo Vacation, M-Series Workstation) with celebratory milestone feedback.
- **🧾 Neural Receipt OCR Scanner**: Allows Alex to drag-and-drop or upload paper receipts and invoices to automatically extract merchants, itemized line items, tax, and totals into the ledger.
- **🔒 100% Local & Privacy-Preserving**: All transaction data is stored safely on the device via local storage with JSON backup and CSV export capabilities. Zero tracking, zero telemetry.

---

## Demo

- **Live Application**: [https://spendwise-ai.pages.dev](https://spendwise-ai.pages.dev) *(Replace with your deployed URL)*
- **Local Dev Server**: Run `npm run dev` to view on `http://localhost:5173/`

### 📸 Highlights & UI Experience
- **Futuristic Glassmorphic Dark UI**: Tailored with an indigo-to-violet iridescent design system, subtle micro-interactions, and glowing status pills.
- **Interactive Visualizations**: Dynamic Donut charts with category drill-downs, cashflow trend bar charts, and weekday vs. weekend heat distribution.
- **Web Audio & Confetti**: Gentle synthesized sound feedback and celebratory confetti showers when hitting savings milestones.

---

## Code

The complete source code is available on GitHub:

- **GitHub Repository**: [https://github.com/your-username/spendwise-ai](https://github.com/your-username/spendwise-ai) *(Replace with your GitHub repo URL)*

### Tech Stack
- **Core Architecture**: HTML5, Vanilla JavaScript (ES Modules), Vite
- **Styling**: Pure Bespoke Vanilla CSS (CSS variables, fluid typography, dark/light theme engine, glassmorphic layout)
- **Data & Charts**: Chart.js for responsive visualizations, Canvas-Confetti for reward psychology
- **Audio Feedback**: Web Audio API native synth tones
- **Intelligence Layer**: Client-side Natural Language Parser + rule-based financial reasoning engine (with optional Google Gemini API key support)

---

## How I Built It

I designed **SpendWise AI** from the ground up to be lightweight, instantaneous, and accessible offline without depending on mandatory cloud backends.

1. **Client-Side Financial Reasoning Engine (`aiEngine.js`)**:
   Instead of forcing every keystroke through a remote server, SpendWise AI features a modular local analytics engine that evaluates:
   - Category spend shifts and statistical variance across 90-day historical cycles.
   - Day-of-month velocity projections: `(currentSpend / daysElapsed) * totalDaysInMonth`.
   - Discretionary vs. Essential ratios based on the popular 50/30/20 framework.
   - Subscription utilization audits highlighting inactive or low-engagement recurring charges.

2. **Natural Language Intent Extraction**:
   Built a flexible regex and heuristic tokenizer that extracts currency symbols, floating-point amounts, relative dates (*"yesterday"*, *"today"*), transaction types, and automatically assigns categories based on lexical merchant dictionaries (e.g., *"Starbucks"*, *"Whole Foods"*, *"Delta"*, *"Uber"*).

3. **Hybrid AI Architecture**:
   SpendWise AI is fully functional right out of the box with zero setup. For users seeking open-ended generative advisory conversations, they can optionally provide their own Google Gemini API key in the settings drawer to unlock deep LLM reasoning.

4. **Simulated Neural Vision Receipt Scanner (`receiptOcrService.js`)**:
   Created a multi-stage document scanner pipeline that walks users through perspective normalization, text detection, and itemization extraction with confidence scores.

---

## Why Does Open Innovation Matter?

Personal finances are among the most intimate and sensitive data a person owns.

In the corporate software landscape, personal finance apps frequently commodify user privacy:
- Banking aggregators often sell anonymized transaction data and shopping habits to advertisers.
- Closed platforms trap your transaction history in proprietary silos and charge monthly subscriptions just to view basic category charts.
- When closed services shut down, your financial history disappears with them.

**Open innovation changes everything:**
- **Data Sovereignty**: Open tools keep user data strictly in their hands. Alex can use SpendWise AI completely offline, export to CSV anytime, and know that no third-party algorithm is profiling their spending.
- **Transparency**: With open source code, every calculation—from how your financial health score is computed to how subscription savings are estimated—is auditable and honest.
- **Customizability**: Anyone can fork the code to add regional currencies, custom tax brackets, or specialized categories tailored to their unique freelancing or family needs.

Building with open technologies gave me the freedom to create a fast, beautiful, and respectful product that puts my friend's financial peace of mind first.

---

## My Agent Session

*Optional: If you recorded your interactive development session or agent workflow using DevRelay / Antigravity, embed or link your session here:*

<!-- {% agent_session YOUR_SESSION_ID %} -->

---

## Prize Categories

- **Build for a Friend**
- **Personal Productivity & AI Tools**
