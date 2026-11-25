# Pennywise Expense Tracker

A responsive React expense tracker with separate sign-in, account creation, and dashboard pages. Your account, expenses, and monthly budget are saved in this browser using `localStorage`; no backend or cloud sync is used.

## Run locally

1. Install Node.js.
2. From this folder, run `npm install`.
3. Run `npm run dev` and open the local URL printed by Vite.
4. Create an account to start tracking expenses.

Run `npm run build` to create a production build in `dist/`.

## GitHub Pages deployment

Enable GitHub Pages once in the repository settings by selecting **Settings →
Pages → Build and deployment → Source → GitHub Actions**. The workflow then
deploys every push to `main` at
https://chinnipillishravan-coder.github.io/Expense-Tracker-Project/.

## Included

- Sign up and sign in, with locally stored PBKDF2 password hashes.
- Overview dashboard with spending totals, monthly budget progress, category breakdown, and a six-month spending chart.
- Add, edit, delete, search, and filter expenses by category and month.
- CSV export for all expenses or the currently filtered transaction list.
- Private on-device AI insights and assistant for budgets, spending trends, category totals, and unusual purchases.
- Automatic expense category suggestions based on purchase notes and previous expenses.
- Natural-language and browser voice capture for splitting multiple purchases into separate expenses.
- SMS/email text parsing for Indian debit alerts, with merchant, amount, date, and category extraction.
- Recurring expense patterns and conversational questions for categories, last-month food spending, budgets, trends, and anomalies.
- Safe-to-spend, AI burn-rate, net cash-flow, month-end forecast, and proactive insight dashboard widgets.
- Monthly income, fixed-bill, and savings-goal planning stored locally.
- Receipt screenshot OCR capture powered by Tesseract.js in the browser.
- Demo persona, privacy blur, command palette, what-if forecast controls, voice/split-bill capture, mandate watchdog, and behavioral AI badges.
- Specialized sidebar views for Splits & IOUs, Recurring & Bills, Goals & Vaults, plus a dynamic AI Pulse card and utility strip.
- Responsive navigation and layouts for desktop and mobile.

## Local data note

This is a frontend-only project. Passwords are stored as salted hashes, but expense and account data live in browser storage on this device. They are not encrypted at rest, synchronized to a server, or protected from someone with access to this browser profile. Clearing browser storage removes the saved account and expense data.
