# AccuSpirals — Tool & Inventory Module (Wireframe)

An interactive, clickable **wireframe** for the standalone Tool & Inventory
Management module being designed for **AccuSpirals**, a precision gear manufacturer.

It previews the screens and how they connect — with a focus on rigorous tool
tracking, calibration compliance, scrap control, and theft prevention.

> ⚠️ This is a **design preview only**. All names, numbers, and data are **fake
> samples**. Search, login, and saving are not functional yet.

---

## 🔗 Live preview

**👉 https://udayd20.github.io/accuspirals-wireframe/**

*(Replace with your actual GitHub Pages URL once enabled — see "View it" below.)*

Opens in any browser, on phone or laptop. No install required.

---

## Screens

| Screen | Purpose |
|--------|---------|
| **Dashboard** | Whole-crib status at a glance: tool value, tools out, overdue, alerts. |
| **Catalog & Search** | Find any tool by type, material, location, or status. |
| **Tool Crib** | Controlled issue/return — every tool tied to a named person + job. |
| **Tool Detail** | One tool's full file: specs, remaining life, custody & regrind history. |
| **Calibration** | Accuracy checks for measuring instruments (ISO 9001:2015). |
| **Scrap & Write-off** | Theft control: weighed, reconciled, and dual sign-off. |
| **Cycle Count** | Blind physical stock check to verify records match reality. |
| **Accountant View** | Valuation, stock ledgers, and shrinkage cost in rupees. |
| **Audit Log** | Tamper-proof record of every action. |

---

## How to navigate

- Click items in the **dark left menu** to switch screens.
- **Catalog & Search** — tick the filter checkboxes; click a result row to open its detail page.
- **Tool Detail** — switch tabs: Overview / Custody chain / Regrind history / Calibration.
- **Cycle Count** — click **"Submit & reveal variance"** to see counting in action.

---

## View it

**Online:** just open the live link above.

**Locally:** download `index.html` and double-click it — it opens in your browser.
No server, build step, or internet connection needed.

---

## Enable GitHub Pages (for the repo owner)

1. Ensure the wireframe file is named **`index.html`** in the repo root.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Select branch **main**, folder **/ (root)**, then **Save**.
5. Wait 1–2 minutes; your live link appears at the top of the Pages screen.

The repo must be **public** for GitHub Pages on a free account.

---

## Tech

A single self-contained `index.html` — plain HTML, CSS, and vanilla JavaScript,
with no external dependencies. Built as a design artifact ahead of the real
implementation (planned stack: NestJS + Prisma + PostgreSQL backend, Angular
frontend).

---

*Feedback welcome — this is an early design and screens can change.*
