# Blend In

A pass-the-phone imposter word game for 3–20 players on one phone.

Everyone gets the secret word, except the imposter. Take turns giving clues, then vote. If the imposter gets caught, they get one guess at the word to steal the win.

## How to play

1. Add everyone's names in seating order (drag the dots to reorder). Roles go around in that order.
2. Confirm players, then pick your word categories, then choose settings (imposter hint, number of imposters, talk timer).
3. Pass the phone. Each player presses and holds their name card to see their role, then lets go to hide it.
4. Talk, then vote for who you think the imposter is.

## Features

- Three-step setup (Players, Words, Settings) with a sticky Next button
- Hold-to-reveal role cards in each player's colour that slide open to show your role
- Imposter hint options: none, category, clue, or both
- 1–3 imposters, talk timer, scoreboard
- Everyday categories plus video game categories (Block World, Fortnite, Roblox)
- Custom word packs you make yourself
- No repeat words until a category runs out
- Sounds and vibration
- Add it to your home screen to use it like an app

## Run it

It's a single `index.html` file. Open it in a browser, or turn on GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main`).

Not affiliated with Mojang, Microsoft, Epic Games or Roblox. Game names are used only to describe word categories.

## Versions and updates

The current version is shown at the bottom of the Players tab (tap it to see what's new).

The app checks `version.json` when it opens, when you come back to it, and every 5 minutes. If the number there is newer than the one built into `index.html`, it updates itself on the setup screens, or shows an **Update** button if you're mid-game.

To release an update, bump `VERSION` (and `CHANGES`) in `index.html` and the number in `version.json` to the same value, then push.
