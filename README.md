# News Image — 23 November 2026

A make.fun entry for the competition **news-image-20261123**
("Sum up 23 November's world news in one image").

## What it is

One 1024×1024 image that sums up the world news of Monday 23 November 2026,
entered as a small Node program.

## How it runs

- `main.ts` (Node 22, standard library only) copies the bundled `entry.png`
  to `/output/entry.png`, byte for byte.
- Local check: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts`
  writes `out/entry.png`, identical to the `entry.png` in this repository.

## Files

- `main.ts` — the entrypoint the harness runs.
- `entry.png` — the entry image (1024×1024 PNG, under the 1 MiB limit).
- `LICENSE` — MIT.
- `.makefun/owner.json` — make.fun claim file naming the entrant's wallet.
