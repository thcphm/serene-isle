# Redgum Island

A cozy 3D island life sim built with Three.js. The whole game is a single HTML file.

You leave a stressful city job and move to a nearly deserted island. Old Bảy, a fisherman who lives in a stilt house by the pier, gives you your first tools and teaches you to farm, chop wood, fish and craft.

## Features
- Smooth skinned chibi character with procedural walk, run, jump and tool animations
- Huge procedural island (800×800 tiles) with 11 biomes: beach, bushland, forest, pine forest, plains, desert with terraced mesas, tropics, mangrove wetland, alpine peaks, savanna and a coastal town with a pier
- Winding fresh-water rivers you can wade across, billabong lakes, rolling hills, rough-soil ore patches and red-sand shores
- Terrain is chunked; trees stream in around the camera with automatic low-poly LOD and near-only shadows
- Farming, tree chopping (palms drop coconuts), crafting, building, and moving buildings and placed items
- Fishing minigame: hold to cast by distance, then keep the fish inside the bar. 30 fish across habitats, plus squid and other sea creatures
- Health, water and energy that drain over time and refill when you eat or drink
- 3D story intro, tutorial quests, and procedural lofi music
- Settings for volume, graphics and keybinds

- Character creation: pick male or female and name your character
- Wildlife in every biome, a pet dog or cat, and livestock (chickens, goats, cows) for eggs and milk
- Seasons and weather, milestones and licences, a museum, campfire cooking
- Serenity (Bình yên): slow down, watch sunsets and stars, sit by the fire, and unlock diary pages; messages in bottles and treasure maps

See ROADMAP.md for what comes next.

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
- Days run 7:00 to 23:00. Be at your tent by 23:00 or you faint and lose everything in your bag (tools are kept)
- Hunger: without food, energy falls to 50% between 7:00 and 12:00
- Bag: stacks hold up to 99. You start with 8 slots; craft a cloth backpack (16) and a leather backpack (24). Overflow drops on the ground
- E: interact · G: move a building or placed item · J: journal · V: sit · I: inventory · M: music · Esc: settings · H: controls help (in Settings)

The game text is in Vietnamese.
