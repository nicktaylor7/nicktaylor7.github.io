# Since '79

*Pull up a seat to the greatest conference in sports.*

Since '79 is the front door to a family of fan-made sites about Big East men's basketball. It's a single illustrated page: a screen-printed, 1980s-style game scene where each part of the court leads somewhere.

**Live at:** [since79.org](https://since79.org) (also [nicktaylor7.github.io](https://nicktaylor7.github.io))

## The sites

| In the scene | Site | What it covers |
|---|---|---|
| The bench (the coaches) | [Big East Coaching Tree](https://nicktaylor7.github.io/BigEastCoachingTree/) | Who learned under whom, from the founding coaches to today's sidelines |
| The floor (the players) | [Big East Big Data](https://nicktaylor7.github.io/BigEastBigData/) | Team and player stats, leaderboards and head-to-head comparisons |
| The scoreboard | [Big East Gami](https://nicktaylor7.github.io/BigEastGami/) | Every final scoreline in conference history |

The same three links appear as ticket stubs below the scene, for anyone who'd rather not hunt.

## How the page works

- **Everything is in `index.html`.** No build step, no dependencies. The illustration is drawn in SVG and JavaScript, so there are no image files.
- **Hotspots.** Hovering (or keyboard-focusing) the coaches, the players or the scoreboard draws a chalk circle around them. On load, each spot gets circled once so visitors know they're live.
- **Phones.** The scene crops in so the hotspots are big enough to tap. The first tap circles a spot and the second tap opens the site.
- **Fonts** load from Google Fonts: Shrikhand (title), Reenie Beanie (handwritten notes), Big Shoulders Display (text) and VT323 (scoreboard digits).
- **Accessibility.** Hotspots are real links with labels, the ticket links work without JavaScript, and the opening animation is skipped for visitors who prefer reduced motion.

## Quick edits

- **Scoreboard score.** Search `index.html` for `>66<` and `>64<` and change the numbers. The default 66–64 is a nod to the 1985 national title game.
- **Site links.** Each link appears twice, once in the scene and once in the ticket stubs. Search for the site's URL to find both.
- **Colors.** The four "inks" are defined at the top of the `<style>` block (`--navy`, `--red`, `--mustard`, `--ink`) and again near the top of the script.

## Domain

The custom domain is set in this repo under Settings → Pages. Because this is the account's `username.github.io` site, the project sites are served under the same domain automatically (for example, `since79.org/BigEastBigData/`). Paths are case-sensitive.

---

Since '79 is an independent fan project by Nicholas Taylor. Not affiliated with, endorsed by or sponsored by the Big East Conference, its member schools or the NCAA. The illustration is original and depicts no real game or person.
