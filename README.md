# AccuSpirals — Tool & Inventory Module (Wireframe)

An interactive, clickable **preview** of the Tool & Inventory Management system
being designed for **AccuSpirals**, a precision gear manufacturer.

This README explains **every screen in simple words** — what it shows, what each
part means, and why it matters. No technical background needed.

> ⚠️ **This is a design preview only.** Everything inside (names, numbers, tools)
> is **fake sample data**. Search, login, and saving don't work yet — it's a
> picture of the app you can click through, not the finished app.

---

## Table of contents

1. [What this is](#1-what-this-is)
2. [The one big goal: stop tools & materials from being stolen](#2-the-one-big-goal)
3. [How to open and navigate it](#3-how-to-open-and-navigate-it)
4. [The screens, explained simply](#4-the-screens-explained-simply)
   - [Dashboard](#dashboard)
   - [Catalog & Search](#catalog--search)
   - [Tool Crib (Issue & Return)](#tool-crib-issue--return)
   - [Tool Detail](#tool-detail)
   - [Calibration](#calibration)
   - [Scrap & Write-off](#scrap--write-off)
   - [Cycle Count](#cycle-count)
   - [Accountant View](#accountant-view)
   - [Audit Log](#audit-log)
5. [How the screens work together](#5-how-the-screens-work-together)
6. [Common words explained](#6-common-words-explained)

---

## 1. What this is

Imagine AccuSpirals has a **locked tool room** (called a "tool crib") full of
expensive cutting tools, measuring instruments, and materials. Workers borrow
tools, use them on machines, and return them.

This software keeps track of **everything** in that room: what's there, where it
is, who has it, what condition it's in, and whether anything is going missing.

Think of it as a very smart, always-watching store-keeper.

---

## 2. The one big goal

The company owner's main worry is simple: **workers could steal tools or
material.** So this system is built, from the ground up, to make stealing very
hard and easy to catch. It does this in several ways:

- Nothing leaves the room without a **named person** attached to it.
- **Scrap** (waste metal) is weighed and double-checked, because pretending
  something is "scrap" is the most common way people hide theft.
- Stock is **counted regularly** and compared to the records.
- Every single action is saved in a **permanent record that can't be edited**.

It also does the normal helpful things: find tools fast, keep instruments
accurate, reorder before running out, and show the money value of everything.

---

## 3. How to open and navigate it

**To open:** download the file, then double-click it. It opens in your web
browser (Chrome, Safari, Edge). Nothing to install.

**To navigate:** click the words in the **dark menu on the left** to move between
screens.

**Things you can click:**
- On **Catalog & Search** — tick the filter boxes on the left, and click any row
  in the list to open that tool's detail page.
- On **Tool Detail** — click the tabs (Overview / Custody chain / Regrind history
  / Calibration).
- On **Cycle Count** — click **"Submit & reveal variance"** to see counting work.

---

## 4. The screens, explained simply

### Dashboard

**What it is:** the home screen — like a noticeboard on the wall of the tool room.
The manager or owner looks at it and instantly knows if everything is under control.

**What you'll see:**

- **Four big number boxes** (the most important figures):
  - **Inventory value** — total worth of all tools in the room (money to protect).
  - **Tools currently issued** — how many tools are out in workers' hands right now.
  - **Overdue returns** — tools that should have come back already but haven't
    (a warning sign).
  - **Calibration due** — measuring instruments that need an accuracy check soon.
- **Bar chart** — how much waste metal (scrap) was produced each month, and its
  value. Watched closely because scrap is a common cover for theft.
- **Alerts list** — the problems to deal with first (a late tool, an expired
  instrument, low stock, a suspicious scrap gap, a worn-out tool).
- **Recently issued table** — a list of who took which tool (proof of who's
  responsible).
- **Record accuracy (A/B/C)** — do the computer's records match what's actually
  on the shelf? If accuracy drops too low, the system automatically orders a
  recount.

**In one line:** the Dashboard shows, at a glance, how many tools are out, who
has them, what's late, and whether anything looks like it's being stolen.

---

### Catalog & Search

**What it is:** the big search page. It lets anyone find any tool instantly out
of thousands.

**What you'll see:**

- **A search box** — type anything (tool name, part number, material).
- **Filters on the left** ("facets") — checkboxes to narrow the list by:
  - **Type** (gear hob, cutter, gauge…)
  - **Material** (what the tool is made of)
  - **Status** (Available, Issued, being resharpened, held aside)
  - **Location** (which plant/room)
  - **Size** (which gear size it makes)
  - The number next to each shows how many tools match.
- **Results table** — each row is one tool, showing its ID, description, material,
  size, exact shelf location, how much life it has left, and its status.

**Why it matters:** in a shop with thousands of tools, the hardest daily task is
*finding the right one*. This shows what exists, where it is, its condition, and
whether it's free — in seconds.

**In one line:** find any tool by any detail, and see exactly where it is and
whether you can use it.

---

### Tool Crib (Issue & Return)

**What it is:** the checkout counter of the tool room. This is where a tool
physically leaves — so it's the most important screen for stopping theft.

**What you'll see:**

- **Scan the tool** — scan the tool's barcode/tag (or type its number).
- **Scan the employee badge** — records exactly *who* is taking it.
- **Job / Work order** — *why* they're taking it (which production job).
- **Expected return** — *when* it must come back. If it's late, it becomes
  "overdue" and shows up as an alert.
- **Transaction preview** — a summary to confirm before saving, showing the
  "custody chain": tool room → person → job.
- **Calibration lock** — if the tool were a measuring instrument that's out of
  date, the system would **block it automatically** so it can't be used.

**Why it matters:** because every checkout records a name + time + job, a tool can
never quietly disappear. If it's not returned, the system already knows who has it.

**In one line:** scan the person, scan the tool, link it to a job, set a return
time — now that tool is officially someone's responsibility.

---

### Tool Detail

**What it is:** the full profile page of a single tool — its complete life story.

**What you'll see (tabs):**

- **Overview** — the tool's specs (type, size, material, coating, accuracy class,
  what it cost) and its **remaining life** (how many times it can still be
  resharpened before it's worn out).
- **Custody chain** — a timeline of everyone who has held this tool over time.
- **Regrind history** — every time it was resharpened, and whether it still met
  the accuracy standard afterward.
- **Calibration** — accuracy-check info (for measuring instruments).

**Why it matters:** it ties together theft control (who has it, where it belongs),
money-saving (use the tool's full life instead of buying new too early), and
quality (proof it meets standards).

**In one line:** one tool's complete file — what it is, what it cost, how much
life is left, and everywhere it's been.

---

### Calibration

**What it is:** a register that keeps measuring instruments (micrometers, master
gears, gauges) accurate. Required by the ISO 9001 quality standard.

**What you'll see:**

- A table of instruments showing when each was last checked, when it's due again,
  its certificate number, who certified it, and its status (Valid / Due soon /
  Expired).
- **Calibration lock:** any instrument past its due date is automatically marked
  "Out of cal" and **can't be used** until it's re-checked.

**Why it matters:** measuring with a drifted instrument gives wrong results and
breaks ISO rules. This makes sure only accurate instruments are ever used — and
it happens automatically.

**In one line:** keeps your measuring tools trustworthy and blocks expired ones
on its own.

---

### Scrap & Write-off

**What it is:** the tightest anti-theft screen. "Scrap" means waste metal
(shavings, offcuts) and broken/worn-out tools that get thrown away or sold to a
recycler.

**The problem it solves:** a worker could steal a good tool or material and simply
record it as "scrap" to hide it. This screen makes that very hard.

**What you'll see:**

- **Reconciliation (the anti-theft math):**
  - Material given to a job − finished parts − normal expected waste = what's
    left over.
  - If the leftover ("unexplained") is bigger than allowed, it's a **red flag**,
    and the system **refuses to save it** until someone investigates.
- **Scrap entry** — the type of scrap, its **weight on a calibrated scale**, where
  it came from, and its resale value.
- **Two-signature rule** — the person logging the scrap and the person approving
  it must be **two different people**. One person can't do both. This stops a
  single dishonest employee acting alone.

**Why it matters:** this directly answers the owner's biggest fear — weigh
everything, do the math, flag anything missing, and require two people to sign off.

**In one line:** stops theft that's disguised as waste, by weighing, checking the
math, and requiring two approvals.

---

### Cycle Count

**What it is:** regularly counting the physical stock to make sure it matches the
records. "Blind" means the counter is **not shown** the number the computer
expects.

**What you'll see:**

- A count task assigned to someone (who is *not* the person in charge of those
  tools).
- The system's expected quantity is **hidden** while they count.
- After they enter what they counted, the difference ("variance") is revealed and
  investigated.

**Why "blind"?** If the counter could see the expected number, a dishonest one
could just write it down to hide a theft. Hiding it forces an honest, independent
count.

**Why it matters:** it independently proves nothing has quietly gone missing — and
the design means the check itself can't be faked.

**In one line:** an honest, independent stock count that catches missing items.

---

### Accountant View

**What it is:** the money side. Everything else tracks *tools*; this turns it all
into *rupees* for the accountant and owner.

**What you'll see:**

- **Total inventory value** — what all the stock is worth.
- **Scrap value recovered** — money made from selling scrap this year.
- **Shrinkage cost** — the money value of stock that went **missing** this year.
  (This is the number that shows theft/loss in rupees.)
- **Stock ledger** — a running money diary: purchases add value, issues and
  missing items reduce it, scrap sales add a little back.
- **Read-only:** this role can *look* at the money but **can't change** stock
  records — so the person seeing the money can't cover anything up.

**Why it matters:** gives the owner and accountant a clean, trustworthy money view
of what stock is worth and what's been lost — ready for audits.

**In one line:** turns all the tool tracking into rupee value and a clear loss
figure.

---

### Audit Log

**What it is:** a permanent, unchangeable record of **every action anyone takes**.
Like an airplane's black box or CCTV that can never be edited or deleted.

**What you'll see:**

- A table of every action: the exact time, who did it, what they did, what it was
  done to, and the before/after detail.
- Even the system's own automatic actions (like marking an instrument expired) are
  recorded.
- **No one — not even an admin — can edit or delete** these records. Each one is
  mathematically linked to the one before it, so any tampering would be obvious.

**Why it matters:** if anything ever goes wrong — a theft, a dispute, an audit —
you have an unfakeable record of exactly who did what and when.

**In one line:** a permanent, tamper-proof record of everything that happens in
the system.

---

## 5. How the screens work together

Everything is connected. Here's the flow in plain words:

1. A worker checks out a tool at the **Tool Crib** → recorded in the **Audit Log**
   and shown on the **Dashboard**.
2. If the tool isn't returned on time → it becomes an **overdue alert** on the
   **Dashboard**.
3. **Calibration** makes sure measuring instruments stay accurate and blocks
   expired ones.
4. When waste is produced, **Scrap** weighs it, checks the math, and needs two
   sign-offs.
5. **Cycle Count** regularly checks the shelves against the records.
6. Any missing items become a **shrinkage cost** in the **Accountant View**.
7. Every step, everywhere, is written into the **Audit Log** — permanently.

The result: a complete tool-and-inventory system with **theft prevention built
into every layer** — while also saving money, keeping quality compliant, and
keeping production running.

---

## 6. Common words explained

| Word | Simple meaning |
|------|----------------|
| **Tool crib** | The locked room where tools are stored and handed out. |
| **Issue / Return** | Giving a tool out / taking it back. |
| **Custody chain** | The record of who is responsible for a tool at each moment. |
| **Overdue** | A tool that should have been returned but hasn't. |
| **Calibration** | Officially checking a measuring instrument is still accurate. |
| **Regrind** | Resharpening a cutting tool (it can only be done a limited number of times). |
| **Scrap** | Waste metal or worn-out tools thrown away or sold. |
| **Reconciliation** | Checking that the numbers add up (material in vs. out). |
| **Variance** | The difference between what records say and what's actually there. |
| **Cycle count** | A regular physical count of stock. |
| **Blind count** | Counting without seeing the expected number, so it can't be faked. |
| **Shrinkage** | Stock that goes missing (often from theft or error). |
| **Audit log** | A permanent, unchangeable record of every action. |
| **ABC class** | Sorting items by importance (A = valuable, counted often; C = cheap, counted rarely). |
| **ISO 9001** | An international quality standard the company follows. |

---

*This is an early design — screens and details can change based on feedback.*
