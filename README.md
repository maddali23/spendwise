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
