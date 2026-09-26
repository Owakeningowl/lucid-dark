# Lucid — dark

A dark copy of the [Pokémon Lucid](https://lucid-dex.vercel.app/) dex, trainer sheets and
damage calculator, with navigation kept inside the copy so moving between them doesn't
bounce you back to the light original.

- **Dex + trainer sheets** — Astral's dark theme (`theme/dark.css`, 128 rules scoped to `.dark-mode`)
- **Calculator** — a neutral grey palette appended to its own `css/dark-theme.css`, dark by default
- **Trainer Browser** (`src/trainer_browser.html`) — every trainer in fight order, one fight at a time,
  with search (trainer, Pokémon, route or `#index`) and a split menu. Reads `src/trainers.json`;
  1v2 fights (shared `team`) and back-to-back fights (`pair: "B2B"`) show as two rows, and
  `pair: "Double"` marks double battles.

All data, sheets and calculator logic belong to the Pokémon Lucid project and
[Smogon's damage calculator](https://github.com/smogon/damage-calc). Only the styling differs.
