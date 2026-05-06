# Project Ideas (Easy → Hard)

A quick list of low-touch starter builds you can finish in hours to a weekend.

## How to use this list
- Pick by **time you have today**.
- Keep each idea to an **MVP first**, then add one stretch feature.
- Stop when it works end-to-end.

---

## Easy (30–90 min)

### 1) CLI Daily Note Generator
**Topic:** Productivity / terminal tools  
**Time:** 30–45 min  
**Build:** A command that creates today’s markdown note with sections (Top 3, Tasks, Wins).  
**MVP scope:**
- Generate `notes/YYYY-MM-DD.md`
- Pre-fill fixed template
- Open/print file path after creation

### 2) Prompt Snippet Saver
**Topic:** AI workflow  
**Time:** 45–60 min  
**Build:** Save and retrieve reusable prompt snippets by keyword.  
**MVP scope:**
- `add`, `list`, `get <key>` commands
- Store snippets in one JSON file
- Basic duplicate-key warning

### 3) Tiny Habit Tracker
**Topic:** Personal analytics  
**Time:** 60–90 min  
**Build:** Track yes/no habits for each day in a local file.  
**MVP scope:**
- Mark habit complete for today
- Show current streak
- Print 7-day summary

---

## Medium (2–5 hours)

### 4) Markdown Project Scaffolder
**Topic:** Dev tooling  
**Time:** 2–3 hours  
**Build:** Create a starter folder with README, TODO, and changelog templates.  
**MVP scope:**
- `init <project-name>` command
- Generate 3–4 boilerplate files
- Optional flags like `--with-license`

### 5) Local Expense Tagger
**Topic:** Finance / data parsing  
**Time:** 3–4 hours  
**Build:** Parse a CSV export and tag transactions by simple rules.  
**MVP scope:**
- Read CSV and map categories by keyword
- Output cleaned CSV
- Show category totals

### 6) Learning Quiz from Notes
**Topic:** Education / AI-assisted learning  
**Time:** 4–5 hours  
**Build:** Turn markdown notes into quick multiple-choice quizzes.  
**MVP scope:**
- Read one notes file
- Generate 5 question-answer pairs
- Run quiz in terminal with score output

---

## Hard (1–2 days)

### 7) Personal Knowledge Search (Local)
**Topic:** Search / knowledge management  
**Time:** 1 day  
**Build:** Search all markdown notes with ranked results.  
**MVP scope:**
- Index local `.md` files
- Keyword + fuzzy search
- Show top results with short snippets

### 8) AI Commit Message Assistant
**Topic:** Developer productivity / git  
**Time:** 1–2 days  
**Build:** Suggest commit messages from staged diffs.  
**MVP scope:**
- Read `git diff --staged`
- Produce 3 candidate commit messages
- Allow copy/select in terminal

### 9) Mini “Build in Public” Dashboard
**Topic:** Web app / analytics  
**Time:** 1–2 days  
**Build:** Simple page showing weekly progress metrics from a local log file.  
**MVP scope:**
- Log entries with date + effort + outcome
- Render one dashboard page
- Show trend for last 4 weeks

---

## Pick one now (quick starts)
If you only have:
- **30 min:** CLI Daily Note Generator
- **1 hour:** Prompt Snippet Saver
- **3 hours:** Markdown Project Scaffolder
- **1 day:** Personal Knowledge Search

Keep it small, ship v1, and iterate.
