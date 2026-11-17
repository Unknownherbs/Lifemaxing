# Lifemaxing Daily

A daily habit tracker for faith, looks, body, mind and money. One file, no build step, no account, no tracking. Your data stays in your browser.

## Features

- **Next up**: one habit at a time, so there is no "what now?" decision.
- **Core habits**: a small minimum that keeps a day counted, even on a bad one.
- **Tiny versions and cues**: every habit has an "after I..." cue and a 2 minute version.
- **Low energy mode and rest days**: core habits only, or a planned day off that protects your streak.
- **Never miss twice**: one missed day is forgiven, two in a row break the streak.
- **Identity votes, levels and milestones**: each habit is a vote for who you are becoming.
- **Daily close**: intention, top 3, win, gratitude, lesson, mood, sleep and weight with trends.
- **Weekly review** and a 28 day history grid.
- **Plan editor** with an ideas library, plus backup export/import and CSV export.
- Works on phone and desktop, light and dark. Keyboard shortcuts on desktop: `1`-`4` switch tabs, arrow keys change day, `D` marks the next habit done.

## Run it

Open `index.html` in any modern browser. That is all.

## Put it on GitHub Pages (free hosting)

1. Create a new repository on GitHub and upload these files (drag and drop works: *Add file > Upload files*).
2. Go to **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
3. After a minute your app is live at `https://<your-username>.github.io/<repo-name>/`. Open it on your phone and use *Add to Home Screen*.

## Your data

Everything is saved in your browser's `localStorage`. Clearing site data erases it, and each browser or device has its own copy. Use **Me > Export backup** to save a `.json` file and **Import backup** to restore it on another device.

## Customize

Edit habits in the app (**Plan** tab). To change the starter habits, verses, level names or colors, edit the `STARTER`, `VERSES`, `TITLES` and CSS variables near the top of `index.html`.

## License

MIT. See `LICENSE`.
