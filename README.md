# Infinite Pinball

A browser pinball game with no end, served as one static page (it works on GitHub Pages).

- Every game builds a new random **world** from a seed. Levels are generated as you reach them.
- Each level is a full table with a **lower** and an **upper** flipper zone.
- Levels are stacked in one continuous table. To reach the next level, break through the **block wall** at the top of the current one. There are no loading screens.
- Higher levels get harder: gravity rises, flippers get shorter, blocks get tougher, and new elements appear. Those are moving bumpers, spinners, gravity wells, armored blocks, sliding gates, repulsors and kicker walls.
- Reaching a new level gives you an extra ball and moves the drain up to that level.

## Controls
- Left flippers: `←` / `Z` / left Shift, or tap the left half of the screen
- Right flippers: `→` / `/` / `M` / right Shift, or tap the right half of the screen
- `Space` nudges the table

## Run locally
Open `index.html` in a browser.

## Deploy
Under **Settings → Pages**, set the source to **GitHub Actions**. After that, every push to `main` deploys the game.
