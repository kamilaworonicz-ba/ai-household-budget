# AI-Built Household Budget Tracker
### AI-Assisted Development Case Study

A lightweight, two-page household budget app — one page for logging transactions, one for reviewing, filtering and summing them — built end-to-end with AI-assisted development.

`Status: Prototype` `Type: AI-Built Prototype` `Domain: Personal Finance / Content Growth` <br>
`Methods: AI-Assisted Development / No-Backend Architecture`

🔗 **[Try the app](https://kamilaworonicz-ba.github.io/ai-household-budget/budget-entry.html)**

## 🎯 Why This Project Exists

This prototype was built as a companion piece to my [physics textbook product launch](https://github.com/kamilaworonicz-ba/physics-product-launch) case study and [What Kind of Math Learner Are You?](https://kamilaworonicz-ba.github.io/ai-math-path-quiz/) quiz, to demonstrate a third kind of skill relevant to a Content Growth Manager role: shipping a small, working, real-world tool by directing an AI coding assistant.

Instead of a content or acquisition experiment, this project starts from an everyday personal need — tracking shared household expenses — and turns it into a working app through a series of concrete product decisions: what data to capture, how to let two people log spending, how to make summaries genuinely useful, and how to protect people from accidentally deleting a record.

The goal was to show that AI-assisted development doesn't remove the need for product thinking. It shifts where that thinking happens: from writing code to specifying requirements, reviewing output critically, and iterating on UX details an AI wouldn't get right on its own.

## 🧩 What the App Does

- **Entry page** — a form for logging a single transaction: date (defaults to today, editable), type (expense/income), category, person (Person A / Person B), amount, and an optional comment.
- **Summary page** — a running ledger of all transactions, with:
  - filters by date range, category, and min/max amount
  - sorting by date or amount
  - a running total that nets expenses against income (not just a raw sum)
  - a link back to the entry page via an "Add transaction" button
- **Safe deletion** — deleting a row asks for confirmation, then requires solving a simple math problem before the record is actually removed, to prevent accidental data loss.
- **No backend** — the two pages share data through the browser's local storage, so the whole thing runs as static HTML with no server or database.

## 📐 Prototype Scope

- Two connected pages, one shared data layer (`localStorage`)
- Fully client-side, no build step, no backend
- English-language UI and sample categories
- Designed to be hosted for free on GitHub Pages

This is a personal-use prototype, not a production finance tool: there's no multi-device sync, no authentication, and no data export yet. Those are natural next steps if the concept were taken further.

## 📁 Files

```
budget-entry.html      # transaction entry form
budget-summary.html    # ledger, filters, sorting, totals
README.md
```

## 📬 Contact

**Kamila Woronicz**<br>
Product Project Manager | Business Analyst<br>
<kamila.woronicz@gmail.com>
