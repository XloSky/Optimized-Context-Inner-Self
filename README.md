# Optimized Context Inner Self

Optimized Context Inner Self packages LewdLeah's open-source AI Dungeon mod in a ready-to-install four-tab setup with configurable context allocation. It gives story characters persistent inner lives: NPCs can learn, remember, plan, form beliefs, and adapt over time through individual Brain Story Cards.

This repository contains **Inner Self v1.0.2** in the same Library, Input, Context, and Output layout used by AI Dungeon's scripting editor.

## Features

- Gives each configured NPC an independent, persistent Brain Story Card
- Triggers NPC minds from recent story mentions
- Lets characters form new thoughts and update existing beliefs over time
- Preserves thoughts between turns while controlling how much story context each brain may use
- Supports first-, second-, and third-person adventures
- Provides human-readable or JSON-formatted brain notes
- Includes configurable trigger distance, thought frequency, context allocation, and visual indicators
- Includes optional inline debugging for model tasks
- Includes optional Auto-Cards integration
- Provides an in-game **Configure Inner Self** Story Card

## Installation

1. Open your scenario's AI Dungeon scripting editor.
2. Copy [`files/library.js`](files/library.js) into the **Library** tab.
3. Copy [`files/input.js`](files/input.js) into the **Input** tab.
4. Copy [`files/context.js`](files/context.js) into the **Context** tab.
5. Copy [`files/output.js`](files/output.js) into the **Output** tab.
6. Save the scripts and begin the adventure.

## Setup

1. Open the generated **Configure Inner Self** Story Card.
2. Enter the player character's first name.
3. Confirm whether the adventure uses first, second, or third person.
4. At the bottom of the card's Notes section, list each NPC's first name on a separate line, ordered from highest to lowest trigger priority.
5. Adjust thought frequency, trigger distance, brain size, or other settings if desired.

Scenario creators can also change the defaults at the top of [`files/library.js`](files/library.js) before publishing.

## Repository Layout

```text
assets/
files/
  context.js
  input.js
  library.js
  output.js
README.md
```

## Credits

Inner Self v1.0.2 was created by **LewdLeah** on January 3, 2026. The source states that Inner Self is free, open-source, general-purpose, and may be used with any scenario.
