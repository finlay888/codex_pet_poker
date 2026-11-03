# Pet Poker

Pet Poker is a browser-based Texas Hold’em prototype where a pet joins you at the table. The current version is a solo practice game against up to five bots using play chips.

## How to play

Open `index.html` in a modern browser. Choose a seat, add or remove bots, and deal a hand. Each player receives two private cards; five community cards are dealt over the flop, turn, and river. Check, call, bet, raise, or fold to make the best five-card hand. The dealer button moves between hands, and the pot is awarded at showdown or when everyone else folds.

Use **How to play & pet** to upload a compatible PNG or WebP pet sprite sheet. The game displays its animations at your seat. Pet images are stored locally in your browser when space is available.

## Current status

This is an early prototype, not an online multiplayer service. Bots use simple practice behaviour. Accounts, shared tables, server-side game state, and multiplayer betting have not yet been implemented. Chips have no monetary value. The sprite-sheet layout detector supports standard sheets and a padded eight-frame layout, but unusual sheets may need adjustment.

## Project files

- `index.html` is the standalone browser version.
- `worker/index.js` serves the same experience as a Worker.

The standalone browser version does not require any dependencies.
