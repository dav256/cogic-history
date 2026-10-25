<h1><img src="https://sgsjcogic.org/wp-content/uploads/2018/03/COGIC_SEAL.png" width="56" align="middle" alt="Seal of the Church of God in Christ"> COGIC History</h1>

[![site live](https://img.shields.io/badge/site-live-brightgreen?style=for-the-badge&logo=github)](https://dav256.github.io/cogic-history/) ![last commit](https://img.shields.io/github/last-commit/dav256/cogic-history?style=for-the-badge) ![GitHub stars](https://img.shields.io/github/stars/dav256/cogic-history?style=for-the-badge&logo=github) ![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white)

> **Live site:** Read the story at [dav256.github.io/cogic-history](https://dav256.github.io/cogic-history/).

**COGIC History tells the story of the Church of God in Christ — Bishop Charles Harrison Mason, Azusa Street, Mason Temple, and a movement that reached the world.**

It is a single-page editorial site with light, image-led styling and oversized serif type. Historical photos, the COGIC seal, and a timeline carry the story from 1895 to today, while the Updates section keeps both church news and site changes visible.

## Photos

- Mason Temple, Memphis — Jim Roberts, CC BY-SA 4.0, via Wikimedia Commons
- Bishop Charles Harrison Mason portrait — Center for African & African American Research, Duke University
- Elder Kelsey preaching at a COGIC service, Mississippi, 1942 — Library of Congress, via New Georgia Encyclopedia
- COGIC seal © Church of God in Christ, Inc., shown for educational identification

## Updates System

The Updates section has two live feeds:

- **COGIC Updates** render from `updates.json` in this repo — add a dated entry `{date, tag, title, text, url}` and it appears on the site, newest first.
- **Website Updates** load live from this repo's GitHub commits, so every change to the site lists itself automatically.

An unofficial educational tribute, not affiliated with the Church of God in Christ, Inc. Sources are linked in the page footer.

## Run Locally

Open `index.html` with a local server (e.g. `npx serve .`) so the updates feed can load.
