# Hunter System

A personal RPG quest tracker based on the supplied Hunter System reference.

## Features

- Daily and one-time quests, rotating challenges, XP, gold, ranks and attribute points
- Local-midnight quest reset with a live countdown
- Turn-based dungeons and a focus timer that survives page reloads
- Collectible cards: one free summon, then 60 earned gold per summon
- Three equipment slots with stacking XP, gold, Strength and Endurance buffs
- Duplicate card upgrades up to tier 5; max-tier duplicates return 30 gold
- Reward shop, achievements, activity history, JSON export/import
- Automatic browser-local saves and migration from the original ARISE tracker
- Responsive layout, animations and reduced-motion support

Saves are specific to the browser and site address. Export a backup before clearing browser data or changing devices. There is no cloud sync. Daily resets use the device's local calendar and clock.

## Development

Requires Node.js 20.19+ or 22.12+.

```sh
npm ci
npm run dev
```

The main application is in `index.html`; additional animations and card styles are in `enhancements.css`.

## Publish

```sh
npm run build -- --base=/Akira/
```

Publish the contents of `dist/` to the `gh-pages` branch. In repository Settings → Pages, select **Deploy from a branch**, **gh-pages**, **/ (root)**.

The ChatGPT assistant button opens ChatGPT in a separate window; it does not send your saved hunter data.
