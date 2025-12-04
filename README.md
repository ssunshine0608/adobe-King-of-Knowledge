# Adobe King of Knowledge

A single-page React quiz game that runs directly from `index.html` using CDN-loaded React, ReactDOM, Babel, and Tailwind. Five image-based questions award up to 100 points, with a results screen that can send the score to a LINE chat.

## Project structure
- `index.html`: React component `App` implements start, answer, and result states, plus scoring and LINE handoff.
- `q1.jpg`–`q5.jpg`: Question images referenced by the quiz.
- `fengmian.jpg`: Cover image shown on the start screen.

## How to preview locally
1. Open `index.html` in a browser—no build step required.
2. Toggle `DEV_MODE` inside `index.html` to `true` to reveal sliders for adjusting clickable regions.

## Sharing code for updates
If you want me to modify the game, you can paste the relevant code snippets (e.g., updates to `index.html` or question data), and I’ll integrate them here. Mention what behavior you expect—scoring rules, LINE parameters, or UI tweaks—so I can apply and test the changes accurately.
