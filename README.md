# Vili Casino — Final Prototype

This is the expanded browser prototype. It is intentionally not tied to Macaly.

Included in this build:
- Sign in / Create account UI
- $50 new-player starting balance
- Home/Dashboard
- Slot Machine Simulator with money/percentage betting
- Jackpot, big-win feedback, spin history and sound toggle
- MORE menu with 8 planned mini-games
- Marketplace with a large starter catalog (80+ items), categories, rarity and search
- In-game phone with Messages, Friends, Gifts, Send Money, Vili Market, Auctions, Profile, Notifications, Achievements, Stats, News, Games, Settings, Bank, BTC and Mini Games app tiles
- Leaderboard and player profile
- Daily bonus
- History
- Multi-language selector foundation, English first
- Responsive Chromebook/mobile layout
- Prototype admin panel

## Run
Install Node.js, then in this folder run:

`npm install`

`npm run dev`

Open the Vite address in Chrome.

## For the real public website
This prototype stores demo data in localStorage. A real online release needs a secure backend/database for accounts, passwords, balances, inventories, gifts, trades, auctions, marketplace transactions, leaderboards and server-side admin authorization. The admin secret is deliberately not included in the project.
