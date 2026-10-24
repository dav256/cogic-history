# cogic-history

[![site live](https://img.shields.io/badge/site-live-brightgreen?style=for-the-badge&logo=github)](https://dav256.github.io/cogic-history/)
![last commit](https://img.shields.io/github/last-commit/dav256/cogic-history?style=for-the-badge)

the story of the Church of God in Christ — Bishop Charles Harrison Mason, Azusa Street, Mason Temple, and a movement that reached the world.

a single-page editorial site (light, image-led, oversized serif type) with the COGIC seal, historical photos, and a timeline from 1895 to today. plain html and css in one file, hosted on github pages.

## photos

- Mason Temple, Memphis — Jim Roberts, CC BY-SA 4.0, via Wikimedia Commons
- Bishop Charles Harrison Mason portrait — Center for African & African American Research, Duke University
- Elder Kelsey preaching at a COGIC service, Mississippi, 1942 — Library of Congress, via New Georgia Encyclopedia
- COGIC seal © Church of God in Christ, Inc., shown for educational identification

## updates system

the Updates section has two live feeds:

- **COGIC Updates** render from `updates.json` in this repo — add a dated entry `{date, tag, title, text, url}` and it appears on the site, newest first.
- **Website Updates** load live from this repo's GitHub commits, so every change to the site lists itself automatically.

an unofficial educational tribute, not affiliated with the Church of God in Christ, Inc. sources are linked in the page footer.

## run locally

open `index.html` with a local server (e.g. `npx serve .`) so the updates feed can load.
