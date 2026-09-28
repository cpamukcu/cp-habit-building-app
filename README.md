# CP

A personal discipline tracker. One HTML file, no build step, no backend.

Every day is a barbell with four plates to load:

- **Gym** – trained, rest day, or skipped (skipping makes you write the excuse down)
- **Vibe coding** – minutes and what you shipped
- **Chinese** – study minutes, a word bank, and flashcard review
- **Content** – minutes, or posted something

Load all four, finish the morning routine, and don't slip on a bad habit: that's a won day, and won days build the streak.

Also in the app: quit counters with a relapse calendar, gym set log with personal records, sleep, water, weight chart, weekly review, and XP levels.

## Running it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 5173
```

## Where data lives

On GitHub Pages or any plain host, everything is saved in that browser's `localStorage`. It doesn't sync between devices, and clearing site data erases it. Progress photo uploads need the hosted Claude version and are turned off here.
