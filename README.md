# Quest

**▶ Play in your browser: https://briandgtl.github.io/WIP-HOD-ENGINE-TEST/**

The link runs the latest build of the `quest-conversion` branch. It needs no install, and it works with a keyboard, a touch screen or a controller.

Quest is a voxel action role-playing game in a 32-bit pixel style, built on the Hills of Dowra engine. The player makes a Hero and sets out from Greywatch Keep across six zones: the grasslands, the Winterlands, autumn woods, the Haunted Hollow, dry grasslands and the cliffs. A day lasts 15 minutes and so does the night, when the dead rise.

- **Six classes:** Warrior, Paladin, Necro-Knight, Rogue, Ranger and Mage. Each has its own armour, weapons, resource and three skill trees.
- **Loot:** five rarities, from Common to Legendary. Gear has affixes and mutators, and there are eleven gear slots. Gold is spent on draughts, the Gambler and the Blacksmith.
- **Bounty board:** it stands before the keep's gate. Ten bounties run from easy to deadly, and clearing the whole board pays a bonus.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Walk | W A S D or arrow keys | Drag anywhere |
| Strike | Space | Sword button |
| Drink a draught | Q | Red flask |
| Skills | Shift, E, 1-5 to use, K for the trees | Skill buttons |
| Character, inventory, quests | C, I, J | Helm and bag buttons |
| Map | M | Map button |
| Pause | Esc | Pause button |

With a controller, the in-game how-to-play shows the matching buttons.

## Running it locally

The game is one file, `ENGTEST.html`; `index.html` just forwards to it. Serve the folder over HTTP and open it, for example:

```bash
python3 -m http.server 8000
```

Then go to http://localhost:8000/. WebGPU is used where the browser has it, otherwise WebGL 2. To force WebGL, add `?webgl` to the address.

`ENGINE-BRIEFING.md` describes how the engine and the game are put together.
