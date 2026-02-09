# mkTask

Goal: a lightweight, single-file task manager that keeps daily execution tied to bigger goals.

Feature list:
- One HTML file (Alpine.js + Tailwind) with no build step.
- Goal hierarchy: yearly, quarterly, weekly, daily, plus notes (Daily Bits).
- Daily Focus view for the selected day.
- Standup view with Yesterday, Selected Day, and Tomorrow columns.
- Knowledge Base view with pinned bits, collapse/expand, and copy.
- Daily Bits sidebar with quick markdown/code entry and convert-to-task.
- Status system: In Progress cycle plus tags (Blocked, Waiting, Review).
- Status filters with per-day counts.
- Next Action spotlight and per-task next-action toggle.
- Automatic rollover of unfinished daily tasks to today.
- Overdue attention bell with a quick list.
- Calendar date picker and history navigation.
- Global search across title, notes, and tags.
- Tags and parent linking (daily to weekly/quarterly, weekly to quarterly, quarterly to yearly).
- Undo delete toast.
- Review modal with cleanup for overdue tasks.
- Metrics dashboard (completion rates, alignment score).
- Light and dark themes.
- File open/save flow with auto-save to localStorage.
- Export CSV, load sample data, delete local database.
- Keyboard shortcuts: Ctrl/Cmd+S save, Ctrl/Cmd+F search, B/W/R/P status hotkeys on selected task.

Files:
- mktask.html: the entire app (UI + logic) in a single file.
- sample_data.json: optional sample dataset for testing.

Data load/unload:
- Open: uses the browser file picker to load a saved JSON file.
- Auto-save: changes are stored in localStorage while you work.
- Export CSV: exports tasks as a CSV file.
- Load Sample Data: replaces current data with the sample dataset.
- Delete Database: clears localStorage for a fresh start.

![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)