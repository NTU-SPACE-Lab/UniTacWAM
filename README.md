# UniTacWAM: A Unified Visuo-Tactile World Action Model for Grippers and Dexterous Hands

[![Project Page](https://img.shields.io/badge/Project-Page-38bdf8)](https://spacelab-ntu.com/UniTacWAM/) ![Paper](https://img.shields.io/badge/arXiv-coming%20soon-b31b1b) [![Lab](https://img.shields.io/badge/NTU-Space%20Lab-8b5cf6)](https://spacelab-ntu.com/)

UniTacWAM is a single world action model that sees, feels and acts across embodiments. One unified action space covers parallel-jaw grippers and a wide range of dexterous hands, and tactile signals from fingertips or gripper pads enter the same model. On Bench2Dex, one checkpoint handles all 26 bimanual dexterous tasks across 15 robot–hand pairs.

- **Project lead:** Yanping Fu
- **Paper:** arXiv (coming soon)
- **Code:** coming soon

## Bench2Dex results

| SR (%) | LSCR (%) | Eff. | Score |
|---:|---:|---:|---:|
| **65.44** | **83.54** | **0.985** | **76.89** |

26 tasks × 4 channels × 50 episodes (5200 evaluated), Bench2Dex commit `cf83e86`, one checkpoint for all tasks. Score = 0.45·SR + 0.45·LSCR + 10·Eff. Self-evaluated; the leaderboard submission is in preparation.

### Comparison with the Bench2Dex leaderboard

| # | Model | Organization | SR | LSCR | Eff. | Score |
|---:|---|---|---:|---:|---:|---:|
| **1** | **UniTacWAM (ours)** | **NTU Space Lab** | **65.44** | **83.54** | **0.985** | **76.89** |
| 2 | PyRUA-Dex | PKU DAGroup | 60.58 | 82.32 | 0.859 | 72.89 |
| 3 | ME-Dex 1.5 | Li Auto. | 58.60 | 76.31 | 0.979 | 70.50 |
| 4 | GigaWorld-Policy-0.6 | GigaAI | 51.37 | 70.91 | 0.962 | 64.64 |
| 5 | Phoenix-MWA (w. Pretrain) | Anyverse & OpenPhoenix | 45.60 | 65.61 | 0.903 | 59.07 |
| 6 | Mora V0 | Morphi Robot | 33.23 | 52.31 | 0.974 | 48.23 |

Other entries: public [Bench2Dex leaderboard](https://bench2dex.github.io/Bench2Dex-Leaderboard/) snapshot of 2026-11-23 (ranked entries with all 26 tasks).

### Success rate per channel

| None | Equi. | Inv. | Full |
|---:|---:|---:|---:|
| 68.5 | 61.3 | 66.0 | 65.9 |

### Success rate per task

| Task | SR (%) | LSCR (%) |
|---|---:|---:|
| 03 · Wine Glass Plate Balance | 51.0 | 88.0 |
| 06 · Fruit Bowl Loading | 86.0 | 97.4 |
| 07 · Citrus Plate Loading | 94.5 | 98.8 |
| 08 · Frypan Stand & Pour | 92.0 | 95.5 |
| 09 · Cleaner Box Loading | 68.5 | 95.0 |
| 12 · Screwdriver Box & Hammer | 76.5 | 90.8 |
| 21 · Condiment Box Loading | 84.0 | 95.0 |
| 22 · Tool Box Loading | 39.0 | 59.9 |
| 24 · Stationery Category Sorting | 48.5 | 75.2 |
| 26 · Canned Food Tray Arrangement | 48.0 | 69.8 |
| 27 · Ball Box Loading | 66.0 | 89.6 |
| 32 · Baking Tray Prep | 16.5 | 74.5 |
| 34 · Fridge Wine Interhand Pour | 77.0 | 88.2 |
| 42 · Trash Disposal | 63.0 | 90.2 |
| 43 · Fridge Fruit Shelf Sorting | 49.0 | 74.6 |
| 44 · Microwave Bowl Loading | 98.0 | 98.9 |
| 51 · Toilet Lid Cleaner Pour | 70.5 | 76.7 |
| 60 · Breadbasket Fast-Food Loading | 77.0 | 82.2 |
| 61 · Medicine Shoebox Pack | 69.5 | 80.8 |
| 62 · Shoebox Accessory Pack | 89.0 | 93.3 |
| 64 · Sports Ball Cup Sort | 72.0 | 80.6 |
| 67 · Faucet Cup Water Fill | 69.5 | 79.1 |
| 73 · Jigsaw Puzzle Assembly | 3.0 | 56.8 |
| 76 · Soup Serving | 33.5 | 68.0 |
| 79 · Bimanual Piano Melody | 89.0 | 94.0 |
| 80 · Gaming Desk Setup | 71.0 | 79.3 |

## Citation

Coming soon.

