# 📊 Finance Formula Encyclopedia

A comprehensive, self-contained web application featuring **147 financial formulas** with detailed explanations, practical use cases, and interpretation guidance — all rendered with beautiful LaTeX equations.

## 🚀 Quick Start

Open `index.html` in any modern browser. No build step, no dependencies, no server required.

```bash
# Just open it
open index.html

# Or serve locally
python3 -m http.server 8080
```

## 📐 What's Included

| # | Category | Formulas | Description |
|---|---|---|---|
| 📈 | Financial Ratios & Metrics | 44 | Profitability, liquidity, efficiency, leverage, valuation ratios |
| 🏦 | Banking & Interest | 14 | APY, compound/continuous interest, loan payments, LTV, DTI |
| 🌍 | Financial Markets | 2 | Inflation rate, real rate of return |
| 📊 | Stocks & Bonds | 30 | CAPM, P/E, P/B, DDM, bond yields, YTM, zero-coupon bonds |
| 🏢 | Corporate Finance | 26 | NPV, FCFE/FCFF, DuPont components, working capital |
| ⏱️ | General Finance & TVM | 30 | Annuities, perpetuities, growing cash flows, doubling time |

Each formula includes:
- **📖 What It Measures** — Clear conceptual explanation
- **💼 Practical Application** — Real-world use cases
- **🔍 How to Interpret** — What the numbers actually mean

## ✨ Features

- **Full-text search** with `Ctrl+K` / `Cmd+K` shortcut
- **Dark/Light theme** toggle with localStorage persistence
- **Collapsible sidebar** navigation by category
- **Color-coded tags** (profitability, liquidity, efficiency, valuation, leverage, banking, time-value)
- **MathJax** rendering for all LaTeX equations
- **Responsive design** — works on desktop, tablet, and mobile
- **Symbol legend** with variable definitions
- **Back-to-top** button
- **Expand/Collapse all** controls
- **Highlight animation** when navigating to a formula

## 🧪 Verification

All 147 formulas have been verified against authoritative financial sources:

- Corporate Finance Institute (CFI)
- CFA Institute curriculum
- Aswath Damodaran (NYU Stern)
- US Treasury regulations (31 CFR 356)
- GAAP/IFRS accounting standards
- OpenStax Accounting

## 📁 Project Structure

```
casifin-formula/
├── index.html          # Main application (self-contained)
├── fin-formula.md      # Source formula reference
└── README.md           # This file
```

## 🛠️ Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Custom properties, flexbox, responsive design
- **Vanilla JavaScript** — No frameworks
- **MathJax 3** — LaTeX equation rendering (CDN)

## 📄 License

MIT — Use freely for education, reference, or as a base for your own finance tools.
