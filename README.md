# Redgum Island

A cozy 3D island life sim built with Three.js. The whole game is a single HTML file.

You leave a stressful city job and move to a nearly deserted island. Old Bảy, a fisherman who lives in a stilt house by the pier, gives you your first tools and teaches you to farm, chop wood, fish and craft.

## Features
- Smooth skinned chibi character with procedural walk, run, jump and tool animations
- Large procedural island with 10 biomes: beach, bush, forest, desert, jungle, wetland, alpine, savanna, sea and a coastal town with a pier
- Farming, tree chopping (palms drop coconuts), crafting, building, and moving buildings and placed items
- Fishing minigame: hold to cast by distance, then keep the fish inside the bar. 30 fish across habitats, plus squid and other sea creatures
- Health, water and energy that drain over time and refill when you eat or drink
- 3D story intro, tutorial quests, and procedural lofi music
- Settings for volume, graphics and keybinds

## Run
Open `redgum-island.html` in a browser, or serve the folder:

```
python -m http.server 8765
```

Then go to http://localhost:8765/redgum-island.html

Play online: https://thcphm.github.io/redgum-island/

## Controls (default)
- WASD: move · Space: jump · Shift: run · Mouse drag: orbit camera
- Left mouse or F: use tool (hold to repeat) · Mouse wheel / 1–9, 0: switch slot
- Hotbar is customizable: assign tools, food or drinks from the inventory, drag slots to reorder, right-click a slot to clear it
- Running (Shift) drains energy twice as fast
- E: interact · G: move a building or placed item · I: inventory · M: music · Esc: settings

The game text is in Vietnamese.
