# Agent Zero

Start from zero. Let the agent ship.

A single-page site (no build step) for a draft skill spec that lets an AI agent launch and trade coins on Pump.fun inside limits you set. HTML, CSS and JavaScript all live in `index.html`.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000

## What's in it
- Console demo: simulated sessions for `/launch`, `/buy`, `/sell`, `/watch`, `/limits`, `/kill`
- Safety limits demo and a copyable `SKILL.md` draft
- Connect wallet (Phantom, Solflare, Backpack): reads the wallet address only, no transactions

## Notes
This is a draft and preview. Nothing trades or launches, and console output is simulated. Not financial advice. Not affiliated with Pump.fun.

## Structure
- `index.html`: the whole site
- `assets/`: logo, mark, profile picture and X banner
