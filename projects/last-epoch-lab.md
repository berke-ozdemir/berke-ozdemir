# Last Epoch Lab

A personal tool for exploring Last Epoch character builds and understanding why their numbers change.

**Status:** Active personal tool · **Stack:** TypeScript, Vite, Vitest · **Source:** Local, not yet published

## The project

The calculation engine models character statistics, damage, survivability, and build choices. The browser interface exposes breakdowns, equipment and skill choices, and searches across supported configurations.

A central part of the work is investigating disagreements with other planners. Mechanics records distinguish verified rules, assumptions, disputed behavior, and unsupported cases. Data carries version and provenance information because a result is only useful in the context of the game version it describes.

## Areas of work

- A calculation engine separated from the browser interface.
- Build import, equipment and skill editing, and candidate search.
- Comparisons with community planners and explanations of differences.
- Versioned game data and explicit coverage limitations.
- Supporting loot-filter and upgrade-analysis tools.

The tool includes AI-assisted implementation and research. Coverage varies by skill and mechanic; provisional calculations are not verified in-game outcomes. Game data and reference projects retain their own attribution and terms.

[Back to my profile](https://github.com/berke-ozdemir)
