# Shadow Dungeon: 32 Rogues

A turn-based roguelike dungeon crawler that runs entirely in your browser.

## Play

Open the game in any modern browser:

**https://mystall05-jpg.github.io/Shadow-Dungeon/**

Or download `index.html` and open it locally. No server, no build step, no dependencies.

## Features

- **3 character classes** with distinct stats and spells (Warrior, Mage, Rogue)
- **5 procedurally generated floors** with connected rooms and corridors
- **Real dungeon generation** (Prim's algorithm for room connection)
- **Raycast field of view** with wall occlusion
- **Turn-based combat** with bump-to-attack, spells, and monster AI
- **Boss fight** on floor 5 (the Red Dragon)
- **Inventory system** with potions, keys, weapons, and shields
- **XP and leveling** with stat growth
- **Synthesized audio** (no audio files, everything generated with Web Audio API)
- **Mobile support** with on-screen D-pad
- **Retro CRT aesthetic** with scanline overlay

## Controls

- **Desktop:** Arrow keys / WASD to move and attack, Space or `.` to wait, Escape to cancel spell targeting
- **Mobile:** On-screen D-pad

## How to play

1. Pick a class (Warrior is easiest, Mage is hardest but most powerful)
2. Walk into monsters to attack them
3. Collect keys to unlock doors
4. Find the stairs (🌀) to descend to the next floor
5. Kill the Red Dragon on floor 5 to win

## License

MIT. Made by Sherwin Samuel Paponette in Trinidad and Tobago.

## Source

Single HTML file, no build tools. View the source at [index.html](index.html).

