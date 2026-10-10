# ARISE — Hunter leveling system

A responsive hunter-themed to-do app. Create quests, earn XP, increase your level and rank, and track your achievements. Progress is saved in your browser's local storage.

## Run locally

Requires Node.js 20.19+ or 22.12+.

```sh
npm ci
npm run dev
```

Open the address printed by Vite.

## Build

```sh
npm run build
```

Production files are generated in `dist/`.

## GitHub Pages

The `gh-pages` branch contains the production website. In repository Settings → Pages, select **Deploy from a branch**, choose **gh-pages**, select **/ (root)**, and Save.

To rebuild for this repository's Pages URL:

```sh
npm run build -- --base=/Akira/
```

Progress is specific to each browser and website address. There is no account or cloud sync.
