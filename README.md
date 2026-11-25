# Randomizer

**Open it:** https://gdrutz-blip.github.io/random/

A random group maker for the classroom, built for Building Thinking Classrooms and other subjects.

- Keep-apart, keep-together and "with one of" rules
- Set groups with their own size, custom group names, absences
- Class view for the projector with six shuffle animations (or a surprise one each time), timer, student picker and quotes
- Group history

The whole tool is one file, `index.html`. No class lists are built in: each teacher adds their own, and their classes, rules, absences, history and settings are saved only in their own browser.

Changes pushed to `main` go live on the Netlify site automatically.

## Links to the other tools
Each tool shows a quiet "More from Mr. Drutz" line linking to the others. The list lives in `tools.json` in this repo.

- **This site** reads `tools.json`, so a new tool only needs adding there (it also keeps a built-in copy in `index.html` for when the file can't be loaded).
- **The other sites** (`teambuilder`, `drama-generator`, `seatingplanner`, `math-strings`) have their own fixed lists in their own `index.html` / `app.js`. They make no network requests on purpose, so they don't read `tools.json`. When you add a tool, update each of them too.
