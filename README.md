# Space Exploration Quiz

A ten-question quiz about space missions, planets, and pioneers, with instant
answer feedback, score and progress tracking, and an incorrect-answer review.
The app supports light and dark themes, reduced motion, and keyboard controls.

## Play online

https://jeongwon-yang.github.io/space-quiz/

## Run locally

Clone or download this repository, then open `index.html` directly in a browser
(`file://`). No installation, dependencies, build step, or local server is needed.
All HTML, CSS, and JavaScript live in `index.html`.

Use **A-D** or **1-4** to answer, **Up/Down** to move between choices, and
**Enter** to continue after answering. **Tab**, **Enter**, and **Space** also work
with the buttons and answer-review disclosure.

## Deployment

GitHub Pages uses **GitHub Actions** as its publishing source. The
`.github/workflows/pages.yml` workflow validates the HTML entry point and inline
JavaScript syntax on pull requests to `main`. After a push or merge to `main`,
it publishes only `index.html` using the official GitHub Pages actions; no
application build is required. It can also be run manually on `main` from the
Actions tab.

Monitor the **Deploy GitHub Pages** workflow in the repository's Actions tab.
Repository administrators can manage publishing under **Settings > Pages**.
