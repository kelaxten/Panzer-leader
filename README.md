# Iron & Steel

A hex-and-counter tactical wargame for two players, inspired by Avalon Hill's *Panzer Leader* (1974). Designed from the ground up for **play-by-email** — take your turn, export the file, send it to your opponent.

**Zero dependencies. Zero build step. One HTML file.** Download `index.html`, double-click it, and you're playing.

## How to Play

1. Open `index.html` in any modern browser
2. Pick a scenario (Cobra or Omaha Beach)
3. Place your units on the highlighted hexes
4. Take turns: **Combat Phase** (fire at enemies) then **Movement Phase** (advance your forces)
5. At the end of your turn, export the file and send it to your opponent
6. They open `index.html`, click **Resume Game**, load your file, and play their turn

## Play-by-Email (PBEM)

The game is built around emailing turn files back and forth:

- After your movement phase, a modal offers to **export your turn as a JSON file**
- Your opponent loads it via **Resume Game** on the start screen
- A **turn summary** shows what happened last turn (casualties, objectives, key events)
- You can also use **Copy Share Link** to send a URL instead of a file

## Scenarios

**Cobra Engagement** — US armor and infantry push through Norman bocage against dug-in German Panzer forces. 24x18 hex map, ~12 units per side, 8 turns. Control 3 of 5 objectives to win.

**Omaha Beach — D-Day** — June 6, 1944. US 1st and 29th Infantry Divisions storm the fortified bluffs against the German 352nd. 30x20 hex map, wave-based reinforcements, 6 turns. Break through or be thrown back into the sea.

## Controls

| Key | Action |
|-----|--------|
| **F** | Enter fire mode (Combat phase) |
| **M** | Enter move mode (Movement phase) |
| **N** | Cycle to next available unit |
| **Enter** | End current phase |
| **Escape** | Cancel fire/move mode, dismiss modals |
| **V** | Toggle objectives panel |
| **?** | Open rules manual |
| **+/-** | Zoom in/out |
| **Arrow keys** | Pan map |

Mouse: left-click to select/place, right-click to deselect. Scroll wheel to zoom. Right-drag or Shift+drag to pan.

## Combat System

- Units have **AT** (anti-tank) and **AP** (anti-personnel) attack factors
- AT is used against armored targets, AP against soft targets
- Combat is resolved on a **CRT** (Combat Results Table) with odds from 1:4 to 6:1
- **Hover over targets** to see odds, outcome probabilities, and terrain modifiers before committing
- **Click once** to lock a target, **click again** to confirm the attack
- Terrain provides defense multipliers: Woods/Town/Hill x2, Fortification x3
- **Indirect fire** (artillery/mortars) can fire over obstacles if a friendly unit spots the target

## Unit Roster

60+ unit types across German and American forces:

- **Tanks**: PzIV, Panther, Tiger I/II, Sherman (75/76/Jumbo/Easy Eight), Stuart, Pershing
- **Tank Destroyers**: StuG III, Jagdpanther, Hetzer, Hellcat, Wolverine, Jackson
- **Infantry**: Rifle, Grenadier, Panzergrenadier, Rangers, Airborne, Engineers
- **Anti-Tank**: Pak 40, Pak 43, Flak 88, Panzerschreck, Bazooka, 57mm/3-inch/90mm
- **Artillery**: Wespe, Hummel, Priest, Nebelwerfer, mortars, howitzers
- **Recon**: Puma, SdKfz 222, M8 Greyhound

## Tech

- Single `index.html` file (~3500 lines, ~120KB)
- Vanilla JavaScript, HTML5 Canvas
- No frameworks, no build tools, no server
- Works offline — just open the file

## Status

Pre-release prototype. Playable with two scenarios, full PBEM support, and a complete combat engine. See `ROADMAP.md` for the full development plan.
