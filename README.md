# Randomizer

**Open it:** https://gdrutz-blip.github.io/random/

A random group maker for the classroom, built for Building Thinking Classrooms and other subjects.

- Keep-apart, keep-together and "with one of" rules
- Set groups with their own size, custom group names, absences
- Class view for the projector with six shuffle animations (or a surprise one each time), timer, student picker and quotes
- Group history

The whole tool is one file, `index.html`. No class lists are built in: each teacher adds their own, and their classes, rules, absences, history and settings are saved only in their own browser.

Changes pushed to `main` go live on the GitHub Pages site automatically.

## Links to the other teacher tools
Each teacher tool shows a quiet "More teacher tools" list linking to the others: the Randomizer (bottom left of the page), Seating Planner (a "More tools" menu in the top bar) and Math Strings (under ☰ More). The list lives in `tools.json` in this repo.

- **This site** reads `tools.json`, so a new tool only needs adding there (it also keeps a built-in copy in `index.html` for when the file can't be loaded).
- **The other sites** (`seatingplanner`, `math-strings`) have their own fixed lists in their own `index.html` / `app.js`. When you add a tool, update each of them too.
- **Deliberately not linked:** G8MES (`g8mes`) and Drama Scene Builder (`drama-generator`) are student activities for grade 8, so no site links to them and they have no links of their own. **Gym Team Maker** (`teambuilder`) is held back while it's in development; when it's ready, add it to `tools.json` and to each site's list.
