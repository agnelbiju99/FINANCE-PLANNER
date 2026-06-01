# 💰 Finance Productivity Planner
### by [Wiz DesignStore](https://www.etsy.com/shop/WizDesignStore)

A complete personal finance planner built as a single HTML file. No installs, no sign-ups, no backend. Just open it in any browser and start tracking your money.

---

## ✨ Features

### ☀️ Daily Planner
- Log daily spends with categories (Food, Transport, Shopping, Health, Entertainment)
- Set a daily budget and track against it in real time
- Top 3 money tasks checklist
- Money mood tracker (😰 😕 😐 🙂 😄 🤑)
- Daily affirmations — 15 built-in, rotates daily
- Daily savings nudge — 8 rotating financial tips
- Daily notes field
- Budget check — "Did I stick to my budget today?"
- Navigate any past or future day

### 📅 Weekly Overview
- Income & expenses table with type badges
- Bills due this week — mark as paid checklist
- Live savings progress bars pulled from your goals
- Weekly reflection — win, lesson, next focus
- 7-day mini calendar with activity dots

### 🗓️ Monthly Dashboard
- Budget planner by category — visual progress bars
- Net worth snapshot — assets vs liabilities
- Monthly goals with progress sliders
- Monthly reflection — win, improvement, priority
- Save rate calculation

### 🎯 Savings Goals
- Add unlimited savings goals
- Track: goal amount, saved amount, monthly contribution, target date
- Live progress bars (color-coded)
- "+ Add Savings" button for quick contributions
- **Milestone celebrations** — confetti 🎉 + toast at 25%, 50%, 75%, 100%

### 📊 Smart Insights
- Auto-generated analysis from your real data
- 8 insight types: streak, budget health, top spending, savings timeline, net worth, weekly summary, unpaid bills, motivational fallback
- One-click refresh

### 🧠 AI Money Coach
- Rule-based coach that reads your actual logged data
- Personalized responses — not generic advice
- 8 quick-prompt buttons for instant answers
- Free-text chat with typing animation
- No API key needed — works 100% offline

### 💸 Payday Mode
- Enter your salary → instant 50/30/20 allocation
- Shows your exact monthly goal contributions
- One click applies income to monthly tracker

### 🔥 Streak Tracker
- Counts consecutive days you've logged data
- Live badge in header
- 28-day visual grid in AI Coach tab
- Motivational messages based on streak length

### 🌙 Dark Mode
- Full dark green theme
- Persists across sessions

### 💾 Data Management
- **Auto-save** — every change saved instantly to localStorage
- **Backup** — download full data as JSON
- **Restore** — upload any previous backup
- **Clear** — reset with confirmation modal

---

## 🚀 Getting Started

No installation required.

**Option 1 — Use online:**
Visit the live URL and start using immediately.

**Option 2 — Use offline:**
1. Download `index.html`
2. Open it in any browser (Chrome, Safari, Firefox)
3. That's it — works completely offline

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | Pure CSS3 with CSS Variables |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | localStorage |
| Fonts | Google Fonts — Fraunces + Plus Jakarta Sans |
| Charts / Libraries | None — zero dependencies |

---

## 🎨 Design System

| Token | Value |
|---|---|
| Primary accent | `#2DBD6E` |
| Primary accent dark | `#1A9E56` |
| Violet | `#7C5CBF` |
| Amber | `#F59E0B` |
| Coral | `#F4645F` |
| Background | `#F4F9F4` |
| Surface | `#FFFFFF` |
| Text | `#1A2B1A` |

Fonts: **Fraunces** (display/numbers) + **Plus Jakarta Sans** (UI text)

---

## 📁 Repository Structure

```
finance-productivity-planner/
└── index.html        ← entire app (HTML + CSS + JS in one file)
└── README.md         ← this file
```

---

## 💡 How Data is Stored

All data is saved in the browser's `localStorage` — nothing is sent to any server.

| Data | Storage Key Format |
|---|---|
| Daily logs | `daily_YYYY-MM-DD` |
| Weekly data | `weekly_YYYY-MM-DD` (Monday) |
| Monthly data | `monthly_YYYY-MM` |
| Savings goals | `savings_goals` (array) |
| Milestones fired | `ms_goalname` |
| Dark mode pref | `dk` |

> ⚠️ Clearing browser data / cache will delete your planner data.
> Use the **Backup** button regularly to save a copy.

---

## 📱 Mobile Support

Fully responsive. Optimised for mobile browsers with:
- Collapsible header menu (⋮) on small screens
- Touch-friendly tap targets
- `font-size: 16px` on inputs (prevents iOS auto-zoom)
- Horizontal scrollable nav tabs
- Single-column layout on mobile

---

## 🔒 Privacy

- **No data leaves your device** — ever
- No analytics, no tracking, no ads
- No account required
- No internet needed after first load (except Google Fonts)

---

## 🛒 Get the Full Product

This planner is available as a digital download on Etsy — includes the HTML app + printable PDF versions (A4 & US Letter).

👉 **[Buy on Etsy — Wiz DesignStore](https://www.etsy.com/shop/WizDesignsStore?ref=dashboard-header)**

---

## 📄 License

This project is for personal use only.
© Wiz DesignStore. All rights reserved.
Do not redistribute, resell, or claim as your own work.

---

<div align="center">
  Made with ❤️ by <strong>Wiz DesignStore</strong><br>
  <em>"Save intentionally. Reach your goals."</em>
</div>
