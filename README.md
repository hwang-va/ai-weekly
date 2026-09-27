# AI Weekly

The week's AI news that matters for how we build software, from public sources only. A new issue comes out every Monday. It is written by Hai Wang with Claude for AI Labs at Valitana.

**Read it here: https://hwang-va.github.io/ai-weekly/**

## How to read it

- **Start at the front page.** It lists every issue, newest first. Each issue shows its top five headlines, so you can skim before you open it.
- **Open an issue.** Each issue has its own address, `https://hwang-va.github.io/ai-weekly/<issue-date>/`, for example [2026-09-28](https://hwang-va.github.io/ai-weekly/2026-09-28/). Link to it directly when you share one.
- **Pick your depth.** The headlines take 30 seconds, the top five with their notes about three minutes, and the whole issue about ten.
- **Follow the links.** Every item links to its source. The catch-up sections give a short reading list for the week's hottest topics: where to start, the news, how to try it, and the skeptic's view.

You don't need an account or a login. The pages work on a phone and follow your system's light or dark setting.

## What's in an issue

| Part | What it gives you |
|---|---|
| Top five | The five items that matter most this week, one line each on why |
| Trend | One pattern across the week, in a paragraph |
| Catch up | A reading list for a topic you may have missed |
| Also this week | Shorter items, grouped by theme |
| Sources | Every link the issue used |

## Suggest a topic

Did we miss a signal, or is there a topic you want covered? Reply to the issue post in the AI Labs chat, or [open an issue](https://github.com/hwang-va/ai-weekly/issues) on this repo.

## How this repo works

This repo is the published site and nothing else. GitHub Pages serves the `main` branch as is.

- `index.html` is the front page.
- `<issue-date>/index.html` is one issue.
- `.nojekyll` tells Pages to serve the files without processing them.

The pages are built from a separate working repo and committed here. Don't edit them by hand: the next build overwrites them. A push to `main` puts a new issue live within a minute or two.
