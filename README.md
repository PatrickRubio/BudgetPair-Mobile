<div align="center">
  <img src="logo.png" alt="BudgetPair app icon" width="170" />

# BudgetPair

### Couples budgeting, shared money tracking, and financial clarity in one place.

[View on the App Store](https://apps.apple.com/us/app/budgetpair-couples-budgeting/id6779858073)

</div>

---

## About

**BudgetPair** is an iOS budgeting app designed specifically for couples. It gives partners one shared place to organize income, bills, everyday spending, savings, investments, debt, and recurring money.

Instead of relying on separate spreadsheets or trying to remember who paid for what, couples can track their finances together and see a clear picture of the month.

> This is a public product showcase repository. The production source code and private infrastructure are intentionally not included.

## Highlights

- Shared budgets for couples
- Real-time partner synchronization
- Income, spending, bills, savings, investments, and debt tracking
- Transactions assigned to either partner or marked as shared
- Recurring and scheduled money
- Receipt attachments
- Monthly budget templates, including 50/30/20 and custom plans
- Budget health and personalized financial insights
- Clear monthly breakdowns and remaining-balance tracking
- Dark, mobile-first interface designed for quick everyday use

## Screenshots

<table>
  <tr>
    <td align="center"><img src="assets/screenshots/home-dashboard.png" width="250" alt="BudgetPair home dashboard"></td>
    <td align="center"><img src="assets/screenshots/budget-breakdown.png" width="250" alt="Budget breakdown"></td>
    <td align="center"><img src="assets/screenshots/add-transaction.png" width="250" alt="Add transaction"></td>
  </tr>
  <tr>
    <td align="center"><b>Monthly dashboard</b></td>
    <td align="center"><b>Budget breakdown</b></td>
    <td align="center"><b>Add transactions</b></td>
  </tr>
  <tr>
    <td align="center"><img src="assets/screenshots/scheduled-money.png" width="250" alt="Scheduled money"></td>
    <td align="center"><img src="assets/screenshots/insights.png" width="250" alt="Financial insights"></td>
    <td align="center"><img src="assets/screenshots/couples-sync.png" width="250" alt="Couples sync"></td>
  </tr>
  <tr>
    <td align="center"><b>Scheduled money</b></td>
    <td align="center"><b>Financial insights</b></td>
    <td align="center"><b>Partner sync</b></td>
  </tr>
</table>

## Main Experience

### Budget together

BudgetPair is built around a shared financial workspace. Couples can create or join a shared room, keep transactions and budgets synchronized, and see the same financial picture across their devices.

### Track the complete month

The app separates money into practical categories:

- Bills
- Spending
- Savings
- Investments
- Debt
- Income

Users can quickly see how much has been used, what remains, and where the household is ahead of or over budget.

### Plan before money moves

Scheduled Money helps users organize recurring income, rent, subscriptions, bills, and other upcoming transactions. Entries can be tracked by due date and marked complete when processed.

### Understand the numbers

The Insights experience turns monthly activity into clear feedback, including budget health, spending guidance, savings progress, and shared contribution summaries.

## Technology

The production application was built with:

- React Native
- Expo
- TypeScript
- Hono
- Upstash Redis
- Vercel
- EAS Build and Submit

The architecture supports a mobile-first frontend with a separately deployed synchronization API and cloud-backed shared budget storage.

## Product Goals

1. **Clarity** — make household money easy to understand.
2. **Collaboration** — give both partners a shared financial view.
3. **Confidence** — help couples plan ahead instead of reacting after money is spent.

## Repository Scope

This repository contains product documentation, screenshots, branding assets, and public feature information.

It does **not** contain application source code, API source code, credentials, secrets, or private infrastructure configuration.

## Author

Built by [Patrick Rubio](https://github.com/PatrickRubio).

---

<div align="center">
  <b>Plan together. Grow together.</b>
</div>
