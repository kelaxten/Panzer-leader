# Iron & Steel — Product Roadmap

## Document Purpose

This roadmap defines the phased development plan for Iron & Steel, from Minimum Lovable Product (MLP) through full release. It covers the complete unit roster inspired by Panzer Leader, the authentic turn sequence, scenario maps with fixed OOBs, and the PBEM system.

---

## Game Identity

Iron & Steel is an original hex-and-counter tactical wargame inspired by the mechanics and spirit of Avalon Hill's Panzer Leader (1974). It is **not** a direct copy or licensed product. All unit values, scenarios, and army compositions are original designs informed by historical research and the general conventions of the PanzerBlitz/Panzer Leader game system. The game uses its own Combat Results Table, terrain system, and turn structure.

Scale: each hex represents 250 meters. Each turn represents approximately 6 minutes. Units represent platoons and individual vehicles/weapons.

---

## Part 1: Complete Unit Roster

Units carry the following values on their counter:

- **AT** — Anti-Tank attack factor (used vs armored targets)
- **AP** — Anti-Personnel attack factor (used vs soft/non-armored targets)
- **DF** — Defense factor (red = non-armored / black = armored)
- **RNG** — Range in hexes
- **MOV** — Movement allowance in movement points
- **Class** — Weapon class (A = Armor-Piercing, H = High-Explosive, M = Mortar, I = Infantry light weapons)
- **Type** — Target type: Armored (A) or Non-Armored (NA)
- **Special** — Special capabilities (IF = Indirect Fire, OR = Overrun, CAT = Close Assault Tactics, AA = Anti-Aircraft, CR = Carrier, PS = Passenger)

### German Units

#### Tanks (Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| PzKpfw IVH | 12 | 6 | 10 | 8 | 10 | A | OR | Main battle tank, backbone of Panzer divisions |
| PzKpfw VG (Panther) | 18 | 6 | 16 | 10 | 12 | A | OR | Superior gun and frontal armor |
| PzKpfw VIE (Tiger I) | 18 | 8 | 18 | 10 | 8 | A | OR | Heavy tank, fearsome but slow |
| PzKpfw VIB (Tiger II) | 24 | 8 | 24 | 12 | 6 | A | OR | King Tiger, devastating firepower |
| StuG IIIG | 12 | 6 | 12 | 8 | 10 | A | OR | Assault gun, no turret, low profile |
| JgPz IV | 14 | 4 | 12 | 8 | 10 | A | OR | Tank destroyer variant |
| Jagdpanther | 20 | 6 | 18 | 10 | 12 | A | OR | Fast heavy tank destroyer |
| Jagdtiger | 24 | 8 | 24 | 12 | 6 | A | OR | Heaviest TD, extremely slow |
| Hetzer | 10 | 4 | 10 | 6 | 10 | A | OR | Light TD, cheap and effective |
| Marder III | 12 | 2 | 4 | 8 | 10 | A | OR | Open-topped, vulnerable |
| Nashorn | 16 | 4 | 4 | 12 | 10 | A | OR | Long-range AT platform, thin armor |
| StuH 42 | 4 | 12 | 12 | 6 | 10 | H | OR | Assault howitzer for infantry support |

#### Self-Propelled Artillery (Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| Wespe | 2 | 14 | 4 | 20 | 10 | H | IF | 105mm SP gun |
| Hummel | 2 | 18 | 4 | 24 | 10 | H | IF | 150mm SP gun |
| Grille | 2 | 12 | 4 | 16 | 10 | H | IF | 150mm infantry gun carrier |

#### Halftracks & Transports (Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| SdKfz 251 | 0 | 2 | 2 | 2 | 12 | I | CR, OR | Standard halftrack, carries 1 infantry |
| SdKfz 251/1 | 0 | 4 | 2 | 2 | 12 | I | CR, OR | Halftrack with extra MG |
| SdKfz 251/9 | 6 | 6 | 2 | 4 | 12 | A | CR, OR | 75mm stummel gun |
| SdKfz 251/22 | 10 | 2 | 2 | 6 | 12 | A | CR, OR | Pak 40 mounted halftrack |
| SdKfz 250 | 0 | 2 | 2 | 2 | 14 | I | CR, OR | Light recon halftrack |
| Opel Blitz (Truck) | 0 | 0 | 0 | 0 | 16 | — | CR | Unarmed transport |
| Maultier | 2 | 10 | 2 | 16 | 10 | H | IF | Rocket launcher halftrack |

#### Armored Cars (Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| SdKfz 234/2 (Puma) | 8 | 4 | 4 | 6 | 14 | A | OR | 50mm gun, fast recon |
| SdKfz 234/1 | 0 | 4 | 2 | 4 | 14 | I | OR | 20mm autocannon recon |
| SdKfz 222 | 0 | 2 | 2 | 4 | 14 | I | OR | Light armored car |

#### Towed Artillery (Non-Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| 7.5cm leIG 18 | 2 | 6 | 2 | 6 | 2 | H | IF | Light infantry gun |
| 10.5cm leFH 18 | 2 | 14 | 2 | 20 | 2 | H | IF | Standard divisional artillery |
| 15cm sFH 18 | 2 | 18 | 2 | 24 | 2 | H | IF | Heavy field howitzer |
| 17cm K18 | 2 | 22 | 2 | 32 | 2 | H | IF | Corps-level heavy gun |
| 21cm Mrs 18 | 2 | 24 | 2 | 28 | 0 | H | IF | Immobile heavy mortar |
| 8cm GrW 34 | 0 | 6 | 1 | 8 | 2 | M | IF | Standard mortar |
| 12cm GrW 42 | 0 | 10 | 1 | 12 | 2 | M | IF | Heavy mortar |
| Nebelwerfer 41 | 0 | 16 | 1 | 14 | 2 | H | IF | Rocket artillery |

#### Anti-Tank Guns (Non-Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| 7.5cm Pak 40 | 14 | 4 | 2 | 8 | 2 | A | — | Standard AT gun |
| 8.8cm Pak 43 | 20 | 6 | 2 | 12 | 0 | A | — | Devastating, immobile |
| 8.8cm Flak 36 | 16 | 6 | 2 | 10 | 2 | A | AA | Dual-purpose AT/AA |
| 5cm Pak 38 | 8 | 2 | 2 | 6 | 2 | A | — | Lighter AT gun |

#### Anti-Aircraft (Non-Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| 2cm Flak 38 | 0 | 4 | 1 | 4 | 2 | I | AA | Light AA |
| 3.7cm Flak 43 | 2 | 6 | 1 | 6 | 2 | A | AA | Medium AA |
| SdKfz 7/1 | 0 | 6 | 2 | 4 | 10 | I | AA | Quad 20mm on halftrack |
| Wirbelwind | 0 | 8 | 4 | 4 | 10 | I | AA, OR | Quad 20mm on Panzer IV chassis |
| Ostwind | 2 | 6 | 6 | 6 | 10 | A | AA, OR | 37mm on Panzer IV chassis |

#### Infantry (Non-Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| Rifle Platoon | 1 | 4 | 4 | 1 | 4 | I | CAT, PS | Standard infantry |
| Grenadier Platoon | 1 | 5 | 5 | 1 | 4 | I | CAT, PS | Experienced infantry |
| Volksgrenadier Plt | 1 | 3 | 3 | 1 | 4 | I | CAT, PS | Late-war conscript infantry |
| Panzergrenadier Plt | 2 | 5 | 5 | 1 | 4 | I | CAT, PS | Motorized infantry |
| SS Panzergrenadier | 2 | 6 | 6 | 1 | 4 | I | CAT, PS | Elite motorized infantry |
| Fallschirmjäger Plt | 2 | 6 | 6 | 1 | 4 | I | CAT, PS | Paratrooper elite infantry |
| Pioneer Platoon | 2 | 5 | 4 | 1 | 4 | I | CAT, PS, ENG | Combat engineer |
| MG Platoon (MG42) | 0 | 6 | 2 | 4 | 2 | I | PS | Heavy machine gun team |
| Panzerschreck Team | 6 | 1 | 1 | 2 | 4 | A | CAT, PS | AT rocket team |
| Sniper | 0 | 2 | 1 | 6 | 4 | I | PS | Disrupts enemy |
| Forward Observer | 0 | 0 | 1 | 0 | 4 | — | PS, FO | Calls artillery |

#### Fortifications & Obstacles

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| Minefield | — | — | — | — | — | — | — | Attacks all entering units at 2:1 |
| Roadblock | — | — | — | — | — | — | — | Blocks road movement |
| Bunker | — | — | +6 | — | — | — | FORT | Defense bonus to occupants |
| Wire | — | — | — | — | — | — | — | Halts infantry movement |
| Trench | — | — | +3 | — | — | — | FORT | Defense bonus, infantry only |

---

### American Units

#### Tanks (Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| M4 Sherman (75mm) | 8 | 6 | 8 | 6 | 12 | A | OR | Workhorse medium tank |
| M4A1 Sherman (76mm) | 12 | 4 | 8 | 8 | 12 | A | OR | Improved AT capability |
| M4A3E2 (Jumbo) | 8 | 6 | 14 | 6 | 10 | A | OR | Heavy armor variant |
| M4A3E8 (Easy Eight) | 12 | 6 | 10 | 8 | 12 | A | OR | Best late-war Sherman |
| M4 DD (Duplex Drive) | 8 | 6 | 6 | 6 | 10 | A | OR, AMPH | Amphibious Sherman |
| M4 Dozer | 8 | 6 | 8 | 6 | 10 | A | OR, ENG | Obstacle clearing |
| M5A1 Stuart | 6 | 4 | 4 | 6 | 14 | A | OR | Fast light tank |
| M24 Chaffee | 8 | 4 | 4 | 8 | 14 | A | OR | Improved light tank |
| M26 Pershing | 18 | 6 | 16 | 10 | 10 | A | OR | Heavy tank, late war |
| M10 Wolverine | 14 | 4 | 6 | 8 | 12 | A | OR | Open-topped TD |
| M18 Hellcat | 14 | 4 | 2 | 8 | 16 | A | OR | Fastest TD in the war |
| M36 Jackson | 18 | 6 | 6 | 10 | 10 | A | OR | 90mm gun TD |

#### Self-Propelled Artillery (Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| M7 Priest | 2 | 14 | 4 | 20 | 10 | H | IF | 105mm SP howitzer |
| M12 GMC | 2 | 20 | 2 | 28 | 8 | H | IF | 155mm SP gun |

#### Halftracks & Transports

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| M3 Halftrack | 0 | 2 | 2 | 2 | 12 | I | CR, OR | Standard APC |
| M16 MGMC | 0 | 8 | 2 | 4 | 12 | I | AA | Quad .50 cal AA halftrack |
| M15A1 CGMC | 2 | 6 | 2 | 6 | 12 | A | AA | 37mm + .50 cal combo |
| DUKW | 0 | 0 | 0 | 0 | 8 | — | CR, AMPH | Amphibious truck |
| 2.5-ton Truck | 0 | 0 | 0 | 0 | 16 | — | CR | Unarmed transport |
| Jeep | 0 | 1 | 0 | 1 | 18 | I | CR | Light recon/transport |

#### Armored Cars

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| M8 Greyhound | 4 | 4 | 2 | 4 | 16 | A | OR | 37mm gun armored car |
| M20 Scout Car | 0 | 2 | 2 | 2 | 16 | I | OR | Light utility car |

#### Towed Artillery (Non-Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| M2A1 105mm | 2 | 14 | 2 | 20 | 2 | H | IF | Standard divisional howitzer |
| M1 155mm | 2 | 18 | 2 | 28 | 2 | H | IF | Corps artillery |
| M1A1 75mm Pack How | 2 | 8 | 2 | 12 | 2 | H | IF | Airborne/mountain howitzer |
| M2 60mm Mortar | 0 | 4 | 1 | 6 | 4 | M | IF | Light mortar |
| M1 81mm Mortar | 0 | 6 | 1 | 8 | 2 | M | IF | Standard mortar |
| M2 4.2" Mortar | 0 | 12 | 1 | 12 | 2 | M | IF | Heavy mortar |

#### Anti-Tank Guns (Non-Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| M1 57mm | 8 | 2 | 2 | 6 | 2 | A | — | Standard AT gun |
| M5 3-inch | 12 | 4 | 2 | 8 | 2 | A | — | Heavier AT gun |
| M1 90mm | 16 | 6 | 2 | 10 | 0 | A | AA | Dual AT/AA |

#### Anti-Aircraft

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| M1 40mm Bofors | 2 | 6 | 1 | 6 | 2 | A | AA | Standard medium AA |
| M51 Quad .50 | 0 | 8 | 1 | 4 | 2 | I | AA | "Meat Chopper" vs infantry too |

#### Infantry (Non-Armored Target Type)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| Rifle Platoon | 1 | 4 | 4 | 1 | 4 | I | CAT, PS | Standard GI infantry |
| Armored Inf Platoon | 2 | 5 | 5 | 1 | 4 | I | CAT, PS | Armored division infantry |
| Ranger Platoon | 2 | 6 | 5 | 1 | 4 | I | CAT, PS | Elite light infantry |
| Airborne Platoon | 2 | 6 | 5 | 1 | 4 | I | CAT, PS | Paratrooper elite |
| Engineer Platoon | 2 | 5 | 4 | 1 | 4 | I | CAT, PS, ENG | Combat engineers |
| HMG Platoon (.30 cal) | 0 | 6 | 2 | 4 | 2 | I | PS | Heavy machine gun |
| Bazooka Team | 4 | 1 | 1 | 2 | 4 | A | CAT, PS | AT rocket team |
| Forward Observer | 0 | 0 | 1 | 0 | 4 | — | PS, FO | Calls artillery |
| Sniper | 0 | 2 | 1 | 6 | 4 | I | PS | Disrupts enemy |

#### Aircraft

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| P-47 Thunderbolt | 8 | 12 | — | — | — | A/H | AIR | Bombs + rockets + strafing |
| P-51 Mustang | 4 | 8 | — | — | — | A/H | AIR | Fighter-bomber |
| P-38 Lightning | 6 | 10 | — | — | — | A/H | AIR | Twin-boom fighter-bomber |

#### Naval Fire Support (Omaha Beach only)

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| DD Destroyer | 2 | 16 | — | 30 | — | H | IF, NAVAL | 5-inch guns, rapid fire |
| CL Light Cruiser | 2 | 20 | — | 40 | — | H | IF, NAVAL | 6-inch guns |
| BB Battleship | 2 | 30 | — | 50 | — | H | IF, NAVAL | 14/16-inch guns, devastating |

---

### British Units (Future — Post-MLP)

#### Tanks

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| Cromwell IV | 8 | 6 | 8 | 6 | 14 | A | OR | Fast cruiser tank |
| Churchill VII | 6 | 6 | 16 | 6 | 6 | A | OR | Heavy infantry tank |
| Sherman Firefly | 16 | 4 | 8 | 10 | 12 | A | OR | 17-pounder gun |
| Comet | 14 | 6 | 10 | 8 | 14 | A | OR | Best late-war British tank |
| Churchill AVRE | 2 | 16 | 16 | 2 | 6 | H | OR, ENG | Petard mortar, engineering |
| Sherman Flail (Crab) | 8 | 6 | 8 | 6 | 8 | A | OR, FLAIL | Mine clearing |
| Valentine Bridgelayer | 0 | 0 | 6 | 0 | 6 | — | BRIDGE | Deploys temporary bridges |

#### Infantry

| Unit | AT | AP | DF | RNG | MOV | Class | Special | Notes |
|------|-----|-----|-----|------|------|-------|---------|-------|
| Rifle Platoon | 1 | 4 | 4 | 1 | 4 | I | CAT, PS | Standard British infantry |
| Commando Platoon | 2 | 6 | 5 | 1 | 4 | I | CAT, PS | Royal Marine / Army Commando |
| Parachute Platoon | 2 | 6 | 5 | 1 | 4 | I | CAT, PS | Red Devils airborne |
| PIAT Team | 5 | 1 | 1 | 1 | 4 | A | CAT, PS | British AT projector |
| RE Platoon (Engineers) | 2 | 5 | 4 | 1 | 4 | I | CAT, PS, ENG | Royal Engineers |

---

## Part 2: Authentic Turn Sequence

Each game turn consists of two player segments (Allied first, then German). Each segment follows this phase order, faithful to Panzer Leader:

### Player Segment Phases

```
1. COMBAT PHASE
   a) Indirect Fire Orders     — Write IF orders for NEXT turn
   b) Minefield Attacks        — Resolve minefields vs enemy units
   c) Indirect Fire Resolution — Resolve IF orders written LAST turn
   d) Direct Fire Attacks      — Resolve all DF attacks
   → All units that fired are INVERTED (may not move this segment)

2. AIR PHASE (if aircraft available)
   a) Aircraft Movement        — Move aircraft units
   b) Anti-Aircraft Fire       — Opposing player fires AA
   c) Air Attack Resolution    — Resolve fighter-bomber attacks

3. MOVEMENT PHASE
   a) Vehicular Movement       — Move all face-up VEHICULAR units
      → Overrun attacks executed and resolved during movement
   b) Non-Vehicular Movement   — Move face-up NON-VEHICULAR units
   → Units that fire may NOT move; units that move may NOT fire

4. CLOSE ASSAULT PHASE
   → Infantry/engineer units execute CAT attacks
   → Must be adjacent to target
   → May not have unloaded from transport this segment
```

### Key Rule: Fire OR Move

A unit may fire OR move in a single segment, never both. Units that fire in the Combat Phase are inverted and may not move. Units that move may not have fired. This is the central tension of the game system.

### Combat Resolution

**Direct Fire:** Compare attack factor to defense factor as a ratio (rounded down in defender's favor). Cross-reference with die roll on CRT.

**Indirect Fire:** Planned one turn in advance. Total IF attack strength is divided equally among all units in the target hex. Each defender is attacked separately.

**Overrun:** Armored vehicles only, in clear terrain only. Odds shifted one column in attacker's favor, -2 to die roll. Executed during movement phase.

**Close Assault Tactics (CAT):** Infantry and engineers only, must be adjacent. Uses a special CAT column on the CRT. Engineers add a bonus.

### Combat Results Table

| Die | 1:2 | 1:1 | 2:1 | 3:1 | 4:1 | 5:1 | 6:1 | CAT |
|-----|------|------|------|------|------|------|------|------|
| 1 | AE | AE | AR | AR | DR | DR | DE | AE |
| 2 | AE | AR | AR | DR | DR | DE | DE | AR |
| 3 | AE | AR | DR | DR | DE | DE | DE | AR |
| 4 | AR | DR | DR | DE | DE | DE | DE | EX |
| 5 | AR | DR | DE | DE | DE | DE | DE | DR |
| 6 | DR | DE | DE | DE | DE | DE | DE | DE |

**Results:**
- **AE** — Attacker Eliminated
- **AR** — Attacker Retreat 1 hex, dispersed (halved values next turn)
- **EX** — Exchange: defender eliminated, attacker loses equivalent DF in units
- **DR** — Defender Retreat 1 hex, dispersed
- **DE** — Defender Eliminated

### Terrain Effects

| Terrain | Infantry MP | Vehicle MP | DF Modifier | Blocks LOS | Notes |
|---------|-------------|------------|-------------|------------|-------|
| Clear | 1 | 1 | +0 | No | — |
| Road (clear hex) | ½ | ½ | +0 | No | Must enter via road hexside |
| Forest/Woods | 1 | 2 | ×2 DF | Yes (beyond adjacent) | Concealment |
| Town/Village | 1 | 1 | ×2 DF (non-vehicle) | Yes | Strong defensive position |
| Hill/Slope | 2 | 2 | ×2 DF if on crest | Blocks behind | Elevation advantage |
| Stream | 2 | 3 | +0 | No | Shallow water obstacle |
| River | — | — | — | No | Impassable without bridge |
| Swamp/Marsh | 2 | Prohibited | +0 | Yes | Infantry only |
| Beach | 1 | 2 | +0 | No | Amphibious landing zone |
| Bocage | 2 | 3 | ×2 DF | Yes | Normandy hedgerow |
| Fortification | — | — | ×3 DF (non-vehicle) | No | Must be pre-placed |

---

## Part 3: Scenario Maps & Orders of Battle

### Scenario 1: Omaha Beach — "Bloody Omaha" (MLP Launch Scenario)

**Date:** June 6, 1944, 0630 hours
**Map:** 30 × 20 hex beach map. Sea hexes on the south edge, beach hexes along the shoreline, bluffs rising to bocage and village terrain inland. Features the Vierville, St. Laurent, and Colleville draws.
**Turns:** 20 turns (representing approximately 2 hours)
**Victory:** Allied player must control 2 of 3 draw exit hexes by end of game.

**Special Rules:**
- Allied units enter from sea hexes via landing craft (1 platoon per turn per entry hex)
- DD tanks must roll for swamping: 1-2 on d6 = lost at sea
- Naval fire support available (2 DD destroyers, 1 CL cruiser)
- German units set up hidden; revealed when firing or spotted by adjacent unit
- Beach hexes provide no defensive cover
- Bluff hexes are elevation 1; units on bluffs gain ×2 DF vs units on beach

**German OOB (352nd Infantry Division detachment):**

| Qty | Unit | Position |
|-----|------|----------|
| 8 | Rifle Platoon | Bluff WN (Widerstandsnest) positions |
| 2 | Grenadier Platoon | Reserve behind draws |
| 2 | Pioneer Platoon | Fortified positions at draw entrances |
| 2 | MG Platoon (MG42) | Enfilade positions on bluffs |
| 3 | 8cm GrW 34 (Mortar) | Behind bluffs |
| 2 | 7.5cm Pak 40 | Covering beach exits |
| 1 | 5cm Pak 38 | Forward AT position |
| 2 | 2cm Flak 38 | Beach-level AA/AI |
| 3 | Minefield | Beach obstacles |
| 4 | Wire | Beach approaches |
| 4 | Bunker | WN positions on bluffs |
| 2 | Trench | Connecting positions |

**American OOB (16th & 116th RCT, 1st & 29th Infantry Divisions):**

**Wave 1 (Turns 1-3):**

| Qty | Unit | Entry |
|-----|------|-------|
| 8 | Rifle Platoon | Sea hexes, spread across beach sectors |
| 2 | Ranger Platoon | Western beach sector |
| 2 | Engineer Platoon | Spread across sectors |
| 4 | M4 DD (Duplex Drive) | Sea hexes (must roll for swamping) |

**Wave 2 (Turns 4-8):**

| Qty | Unit | Entry |
|-----|------|-------|
| 6 | Rifle Platoon | Sea hexes |
| 2 | Armored Inf Platoon | Sea hexes |
| 2 | Engineer Platoon | Sea hexes |
| 4 | M4 Sherman (75mm) | Beach edge (LCT delivery) |
| 2 | M4 Dozer | Beach edge |
| 2 | Bazooka Team | Sea hexes |
| 2 | HMG Platoon | Sea hexes |
| 1 | M2 60mm Mortar | Sea hexes |

**Wave 3 (Turns 9-14):**

| Qty | Unit | Entry |
|-----|------|-------|
| 4 | Rifle Platoon | Beach edge |
| 2 | M4A1 Sherman (76mm) | Beach edge |
| 2 | M10 Wolverine | Beach edge |
| 1 | M7 Priest | Beach edge |
| 2 | M1 81mm Mortar | Beach edge |
| 1 | Forward Observer | Beach edge |
| 2 | M3 Halftrack | Beach edge |

**Naval Support (available from Turn 1):**

| Qty | Unit | Notes |
|-----|------|-------|
| 2 | DD Destroyer | Fire support, unlimited range to beach |
| 1 | CL Light Cruiser | Heavy fire support |

---

### Scenario 2: Bocage Breakout — "Cobra" (MLP Launch Scenario)

**Date:** July 25, 1944
**Map:** 24 × 18 hex Normandy inland map. Dense bocage in the north, opening to mixed terrain with villages and road network in the south. A main road runs east-west.
**Turns:** 16 turns
**Victory:** American player must exit 8+ units off the southern map edge.

**German OOB (Panzer Lehr Division remnants + infantry):**

| Qty | Unit |
|-----|------|
| 3 | PzKpfw IVH |
| 1 | PzKpfw VG (Panther) |
| 1 | StuG IIIG |
| 6 | Grenadier Platoon |
| 2 | Pioneer Platoon |
| 3 | MG Platoon (MG42) |
| 2 | 7.5cm Pak 40 |
| 2 | 8cm GrW 34 |
| 1 | 10.5cm leFH 18 |
| 2 | Panzerschreck Team |
| 2 | SdKfz 251 |
| 2 | Minefield |

**American OOB (mixed armored + infantry task force):**

| Qty | Unit |
|-----|------|
| 4 | M4A1 Sherman (76mm) |
| 2 | M4 Sherman (75mm) |
| 2 | M5A1 Stuart |
| 2 | M10 Wolverine |
| 6 | Armored Inf Platoon |
| 4 | Rifle Platoon |
| 2 | Engineer Platoon |
| 2 | HMG Platoon |
| 2 | Bazooka Team |
| 4 | M3 Halftrack |
| 2 | M7 Priest |
| 2 | M1 81mm Mortar |
| 1 | Forward Observer |
| 2 | M8 Greyhound |
| 2 | P-47 Thunderbolt |

---

### Scenario 3: Ardennes Ambush — "Bulge" (Post-MLP)

**Date:** December 16, 1944
**Map:** 24 × 18 forested/hilly map with few roads, scattered villages, river crossing.
**Turns:** 20 turns
**Victory:** German must control the bridge and village hexes by turn 20.

*(Full OOB to be detailed in v1.1)*

---

### Scenario 4: Gold Beach — British Assault (Post-MLP)

**Date:** June 6, 1944
**Map:** British beach landing map with seawall, dunes, minefields, and inland villages.
**Turns:** 16 turns
**Victory:** British must clear all beach defenses and advance 8 hexes inland.

*(Requires British unit roster — full OOB in v1.2)*

---

### Scenario 5: Remagen Bridge (Post-MLP)

**Date:** March 7, 1945
**Map:** Rhine river crossing map with intact bridge, urban terrain on both banks.
**Turns:** 12 turns
**Victory:** Americans must get units across and hold the eastern bridgehead.

*(Full OOB in v1.3)*

---

## Part 4: PBEM System Design

### How It Works

1. Active player completes all four phases of their segment
2. Game state is serialized to a `.iron` JSON file
3. Player emails the file to their opponent
4. Opponent imports the file, sees replay of the previous turn's actions
5. Opponent takes their turn, exports, emails back

### The .iron File Format

```json
{
  "version": "2.0",
  "game": "Iron & Steel",
  "scenario": "omaha_beach",
  "turn": 5,
  "segment": "german",
  "phase": "start",
  "timestamp": "2025-02-06T14:30:00Z",
  "state": {
    "terrain": [...],
    "units": [...],
    "wrecks": [...],
    "minefields": [...],
    "fortifications": [...],
    "ifOrders": [...],
    "spottedUnits": [...],
    "victoryConditions": {...}
  },
  "actionLog": [
    { "turn": 4, "segment": "allied", "phase": "combat", "action": "directFire", "attacker": "unit_12", "target": "unit_45", "result": "DR", "dieRoll": 5 },
    { "turn": 4, "segment": "allied", "phase": "movement", "action": "move", "unit": "unit_12", "path": [{"col":5,"row":8}, {"col":6,"row":8}] }
  ],
  "chatMessages": [
    { "turn": 4, "side": "allied", "text": "Those Panthers are giving me trouble at the crossroads..." }
  ]
}
```

### PBEM Chat Feature

Each export can include an optional text message from the player. These accumulate in the `chatMessages` array, creating an in-game correspondence. This is the email-game equivalent of table talk.

---

## Part 5: Product Roadmap — Phased Releases

### Phase 0: Foundation (Current — Pre-MLP)

**Status:** Prototype complete
**What exists:**
- Basic hex map rendering with canvas
- Simplified 3-phase turn structure
- Simplified unit roster (6 unit types)
- Basic CRT-based combat
- .iron file export/import for PBEM
- Minimap, unit selection panel, battle log

**What's missing for MLP:**
- Authentic 4-phase turn sequence
- Full unit roster with proper AT/AP/DF/RNG/MOV
- Fire OR move constraint
- Indirect fire with forward observers
- Overrun mechanics
- Close Assault Tactics
- Fixed scenario maps with preset OOBs
- Stacking rules
- Spotting and line of sight
- Terrain effects on combat (DF modifiers)
- Unit dispersal/recovery
- Wrecks from destroyed armor

---

### Phase 1: MLP — "Minimum Lovable Product"

**Target:** The version you can actually sit down and play a full game with your dad over email and have it feel like a real wargame.

**Release 1.0 — Core Engine**

- [ ] **Authentic turn sequence:** Combat → Air → Movement → Close Assault, with fire-or-move constraint
- [ ] **Full German unit roster:** All tanks, infantry, artillery, AT guns, AA, halftracks, armored cars from Part 1
- [ ] **Full American unit roster:** All tanks, infantry, artillery, AT guns, AA, halftracks from Part 1
- [ ] **Dual combat factors:** AT factor vs armored targets, AP factor vs non-armored targets
- [ ] **Complete CRT** with all columns including CAT
- [ ] **Direct fire** with range and LOS checking
- [ ] **Indirect fire** with forward observer requirement, one-turn delay
- [ ] **Overrun attacks** for armor in clear terrain, with odds shift and DRM
- [ ] **Close Assault Tactics** for infantry/engineers, with engineer bonus
- [ ] **Terrain effects on combat:** DF multipliers for woods, town, hill, fortification
- [ ] **Terrain effects on movement:** Full terrain cost table, road bonus, vehicle restrictions
- [ ] **Stacking limits:** 4 units per hex max
- [ ] **Unit dispersal:** Dispersed units halved, recover next turn
- [ ] **Wrecks:** Destroyed armor leaves wreck counters (max 3 per hex)
- [ ] **Line of sight:** Blocked by woods, towns, hills at range; adjacent always visible
- [ ] **Spotting:** Hidden units in concealment terrain until firing or spotted by adjacent enemy
- [ ] **Passenger/carrier system:** Load/unload infantry onto halftracks and trucks
- [ ] **Unit counter display:** Show AT/AP/DF/RNG/MOV on each counter, color-coded

**Release 1.1 — Omaha Beach Scenario**

- [ ] **Fixed Omaha Beach map** (30×20, hand-designed terrain)
- [ ] **Beach, bluff, and draw terrain types**
- [ ] **Amphibious landing rules:** Sea hex entry, wave timing, DD tank swamping rolls
- [ ] **Naval fire support:** Off-map DD/CL/BB providing IF
- [ ] **German hidden setup** with fog of war on beach
- [ ] **Fixed OOBs** for both sides as defined in Part 3
- [ ] **Wave-based reinforcement schedule** for Americans
- [ ] **Victory condition checking** (control draw exit hexes)
- [ ] **Fortification/wire/minefield placement** per scenario card

**Release 1.2 — Bocage Breakout Scenario**

- [ ] **Fixed Cobra map** (24×18, bocage/village terrain)
- [ ] **Bocage terrain type** with special movement/combat rules
- [ ] **Air support:** P-47 fighter-bomber attacks with AA defense
- [ ] **Map exit victory conditions**
- [ ] **Fixed OOBs** per Part 3

**Release 1.3 — PBEM Polish**

- [ ] **Turn replay animation:** On import, watch opponent's moves play out step-by-step
- [ ] **In-game chat messages** embedded in .iron files
- [ ] **Turn summary screen** showing casualties, territory changes, key events
- [ ] **Save/load to browser localStorage** for mid-game saves
- [ ] **Export turn as email-ready text** (for those who prefer pasting into email)

---

### Phase 2: Depth — "The Full Game"

**Release 2.0 — Ardennes Scenario + German Expansion**

- [ ] **Ardennes Ambush map** (forested hills, river, villages, snow terrain)
- [ ] **Snow/winter terrain rules:** Reduced movement, frozen rivers passable
- [ ] **Night turn rules:** Reduced range, no air support
- [ ] **German reinforcement schedule**
- [ ] **Full Ardennes OOB** with late-war German units (Tiger II, Jagdtiger)
- [ ] **Smoke shells:** Artillery can lay smoke hexes blocking LOS

**Release 2.1 — British Forces + Gold Beach**

- [ ] **Full British unit roster** (Cromwell, Churchill, Firefly, Comet, AVRE, Flail, etc.)
- [ ] **Gold Beach scenario** with British-specific rules
- [ ] **Hobart's Funnies** special units (AVRE, Flail, Bridgelayer, Crocodile)
- [ ] **Mine clearing mechanics** for Flail tanks

**Release 2.2 — Scenario Editor**

- [ ] **Map editor:** Paint terrain hex-by-hex on blank grid
- [ ] **OOB editor:** Pick units from roster, set starting positions
- [ ] **Victory condition editor:** Define objective hexes, exit conditions, turn limits
- [ ] **Save/load custom scenarios** as .iron-scenario files
- [ ] **Share scenarios** via file exchange (same as PBEM)

---

### Phase 3: Scale — "Community & Polish"

**Release 3.0 — Remagen + Campaign Mode**

- [ ] **Remagen Bridge scenario** (Rhine crossing)
- [ ] **Campaign mode:** Linked scenarios where surviving units carry over
- [ ] **Unit experience:** Veterans gain +1 DF after surviving 2 scenarios
- [ ] **Replacement system:** Receive reinforcements between scenarios

**Release 3.1 — Quality of Life**

- [ ] **Undo system:** Full undo stack for current phase
- [ ] **Movement path preview:** Show path and remaining MP before committing
- [ ] **Attack preview:** Show odds, terrain modifiers, expected results before committing
- [ ] **Detailed unit info popup** on hover
- [ ] **Keyboard shortcuts** for phase advance, undo, selection
- [ ] **Responsive layout** for tablets (iPad-friendly)
- [ ] **Print-friendly map view** for those who want to study the board offline

**Release 3.2 — Community Features**

- [ ] **Scenario repository:** Upload/download community scenarios via GitHub
- [ ] **Game replay viewer:** Load completed .iron files and watch full game replay
- [ ] **ELO rating system** (honor system, tracked in .iron metadata)
- [ ] **Multiple scenario packs** organized by campaign (Normandy, Bulge, Rhine)

---

### Phase 4: Future Vision

**Release 4.0 — Live Play**

- [ ] **WebRTC peer-to-peer** real-time play (optional, PBEM remains primary)
- [ ] **Spectator mode** for watching live games
- [ ] **Turn timer** options for competitive play

**Release 4.1 — AI Opponent**

- [ ] **Basic AI** for solo play (defensive posture, attacks of opportunity)
- [ ] **AI difficulty levels** (conscript / regular / veteran / elite)
- [ ] **AI suitable for learning the game** before challenging a human

**Release 4.2 — Eastern Front Expansion**

- [ ] **Soviet unit roster** (T-34, KV-1, IS-2, SU-76, SU-152, Katyusha, etc.)
- [ ] **Eastern Front scenarios** (Kursk, Bagration, Berlin)
- [ ] **Interchangeable with German units** per PanzerBlitz/Panzer Leader tradition

**Release 4.3 — Sound & Polish**

- [ ] **Optional sound effects:** Dice rolls, gunfire, movement, explosions
- [ ] **Atmospheric background audio** (period-appropriate, subtle)
- [ ] **Counter art upgrade:** Silhouette artwork on unit counters (like original PL)
- [ ] **Animated combat resolution** with dice roll visualization

---

## Development Principles

1. **Single HTML file as long as possible.** Zero dependencies, zero build step. If your dad can download a file and double-click it, he can play.

2. **PBEM is the primary multiplayer mode.** Live play is a nice-to-have. The core experience is taking your turn thoughtfully, exporting a file, and emailing it with a note about your strategy.

3. **Respect the source material.** Every mechanic should be traceable to established wargame conventions. If SPI or Avalon Hill did it that way, there's probably a good reason.

4. **Accessible doesn't mean dumbed down.** The game should have real depth. "Accessible" means the UI is clear, the controls are obvious, and you don't need a 40-page rulebook to start playing. The complexity lives in the decisions, not the interface.

5. **Test with your dad.** Every feature ships when a 70-year-old can use it without asking for help.

---

## Appendix: Key Differences from Panzer Leader

Iron & Steel is inspired by Panzer Leader but is an original game. Key differences:

- **Original unit values:** All AT/AP/DF/RNG/MOV numbers are our own designs, informed by historical data but not copied from any published game.
- **Simplified CRT:** Fewer columns than PL's Weapons Effectiveness Chart; we use a traditional odds-ratio CRT instead of the cross-referenced WEC.
- **No opportunity fire in MLP:** Added in Phase 2 as optional rule.
- **Digital-native PBEM:** File-based turn exchange designed for email from the start, not adapted from postal play.
- **Single map per scenario:** Not geomorphic tiles; each scenario has a purpose-built map.
- **No counter sheets to punch:** The computer handles all the bookkeeping that made the board game tedious (stacking, dispersal tracking, IF order writing, LOS checking).

This is the game Panzer Leader would be if it were designed in 2025 for two people who live 500 miles apart and want to play a serious wargame over email.
