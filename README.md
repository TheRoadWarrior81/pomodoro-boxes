# Pomodoro Boxes

A focus timer where a box only fills if you actually did the work.

- **Honest sessions:** random check-ins during the timer, and a required note on what you finished before a box is earned.
- **Carry-over:** unfinished boxes roll into the next day until you clear them.
- **Categories:** tag sessions (Work, Study, Health, Personal, or your own) with colours.
- **Insights:** time by category and by task over 7 days, 30 days or all time.
- **Calendar:** coloured dots per session; click a day to see what you finished.
- **Reports and data:** download an HTML progress report (print to PDF), CSV, or a JSON backup, and restore a backup on another device.
- **Private:** no account, no tracking. Everything is stored in your browser (`localStorage`).
- **Installable:** works offline as a PWA.

## Run it

Open `index.html`, or host the folder on GitHub Pages (Settings, Pages, deploy from the main branch).
Service workers need http(s), so the offline/install features work on the hosted version.

## Roadmap

- Short and long breaks
- Weekly streaks and a heatmap
- PNG icons for broader install support
- Tests for the carry-forward logic

MIT licensed.
