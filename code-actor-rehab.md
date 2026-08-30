# Code Actor Rehab — 14-Day Drill Sheet

> Goal: rebuild raw-syntax muscle memory under pressure. Map master.dev *Senior Frontend Interview Prep* lessons to the exact patterns that broke you in the live test.
>
> **Rules (every day):**
> 1. **Type, don't tab.** AI/autocomplete OFF in the editor.
> 2. Watch the lesson's *problem statement only* → pause → build it yourself first.
> 3. Only after your attempt: unpause, compare, then **retype** the corrected version by hand.
> 4. Final 5 min: write a postmortem — "what syntax did I forget?"

---

## Daily structure (90 min)

| Block | Time | What |
|-------|------|------|
| Syntax warmup | 20m | JS fundamentals + TypeScript basics (types, interfaces, utility types) from memory |
| Implementation | 40m | the day's main build (from memory first) |
| Notepad drill | 20m | rebuild the same thing in a plain editor (no linting/snippets), timed |
| Postmortem | 10m | log forgotten syntax + broken patterns |

---

## Week 1 — Syntax endurance + core interview patterns

### Day 1 — Fundamentals reflex
- **Course:** *Easy JS/TS* → `detectType`, `Debounce`
- **TypeScript:** `Readonly`, `Pick`
- **Drill:** write debounce + throttle from memory; 10 array/object transforms by hand.
- **Why:** pure syntax warmup, no UI distractions.

### Day 2 — The exact test you failed (Part 1)
- **Course:** *Easy Component Problems* → `Creating the AbstractComponent`
- **Drill (Notepad):** Form → `e.preventDefault()` → dedupe by email/id → save to `localStorage` (`getItem`/`setItem` + `JSON.parse`/`stringify`) → render table → remove row.
- **Target:** finish in < 20 min, working MVP, zero copy-paste.

### Day 3 — Lists, rendering, state
- **Course:** *Easy Components* → `Star Rating: UI` + `Click Handler`, `Tabs`
- **Drill:** controlled/uncontrolled star rating; tabs with one active panel + ARIA roles.

### Day 4 — Fetch + render + search (test Part 2)
- **Course:** *Medium Components* → `Data Table: Fetching Data`
- **Drill:** fetch users from an API → render cards → add live search/filter. From memory.

### Day 5 — Inline edit + mutation (test Part 2 follow-up)
- **Course:** *Medium Components* → `Data Table: Sorting, Filtering & Pagination`
- **Drill:** add inline edit + save/cancel + pagination + sorting to yesterday's table.

### Day 6 — Dialog, Tooltip, focus management
- **Course:** *Easy Components* → `Dialog`; *Medium* → `Tooltip: UI` + `Show & Hide`
- **Drill:** native `<dialog>` open/close/confirm; tooltip with show/hide on hover+focus.

### Day 7 — Full mock (no AI at all)
- **Drill:** 45-min timed mock combining: Form+localStorage+table+remove **OR** Fetch+cards+search+inline-edit. Narrate out loud while coding.
- **Postmortem:** rank what slowed you down.

---

## Week 2 — Frontend interview execution

### Day 8 — Async utilities + UI patterns
- **Course:** `Throttle`, revisit `Debounce`
- **TypeScript:** `ReturnType`, `Parameters`
- **Drill:** implement debounce + throttle from memory, then build a searchable list with debounced search.

### Day 9 — Data Table mastery
- **Course:** *Medium Components* → `Data Table`
- **Drill:** fetch → search → sort → pagination. Build without looking at notes.

### Day 10 — Stateful component logic
- **Course:** *Hard Components* → `Calculator`
- **Drill:** calculator with event delegation and derived state.

### Day 11 — Interactive UI systems
- **Course:** *Hard Components* → `Toast`
- **TypeScript:** `Lookup`
- **Drill:** toast manager with add/remove, auto-dismiss, and animations.

### Day 12 — Complex state management
- **Course:** *Hard Components* → `Puzzle Game`
- **Drill:** move validation, state transitions, win conditions, immutable updates.

### Day 13 — Modern product UI
- **Course:** *Extreme Components* → `ChatGPT Client`
- **Drill:** chat UI, streaming text effect, auto-scroll, message state management.

### Day 14 — Full mock interview
- **Drill:** 60-minute timed interview simulation.

Choose one:
- Form + localStorage + table + edit + delete
- Fetch + cards + search + inline edit
- Data table + pagination + sorting
- Tabs + Dialog + Toast

Narrate your reasoning out loud and keep AI completely off.

Goal: finish a working solution before polishing.
---

## Interview-day execution flow (use every time)

1. **Clarify** requirements (2 min)
2. **Outline** state/data shape out loud (1–2 min)
3. **Build minimal working version fast** — flow first
4. **Verify** with 2–3 manual test cases
5. **Enhance** only after core works

**Priority:** working flow > clean syntax > polish.

**Narrate while coding** (protects you even on syntax slips):
- "Preventing default submit."
- "Parse existing storage or fall back to `[]`."
- "Guard duplicates by email/id."
- "Persist after each mutation."

**Same-day 30-min warmup before any interview:** one fast rep of
Form+localStorage+list+delete **or** Fetch+render+search+inline-edit.

---

## TypeScript track (15 min/day)

Focus only on practical interview TypeScript.

Implement and explain:

- `interface` vs `type`
- Union types
- Generics
- `Pick<T, K>`
- `Omit<T, K>`
- `Partial<T>`
- `Readonly<T>`
- `Record<K, V>`
- `ReturnType<T>`
- `Parameters<T>`

Skip advanced type-level puzzles for now.

Goal: be comfortable reading and writing TypeScript used in real React codebases.

---

## Communication drill (10 min/day)

Record yourself explaining:

- URMI
- College Portal
- Notes App

Answer:

1. What problem does it solve?
2. What tech stack did you use?
3. What was the hardest challenge?
4. What would you improve?

Goal: improve interview fluency and technical communication.

---

## AI usage model (the actual fix)

1. You write the first draft **from memory**.
2. AI reviews bugs/edge cases.
3. You **retype** the fixed version by hand.

> No direct paste for core interview patterns. AI stays for architecture, review, and speed *elsewhere*.
