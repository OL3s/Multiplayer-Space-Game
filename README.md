# Astraphobia

**Players:** 2–8  
**Goal:** *Reach the Center* – *Start from edge* – get to the wormhole in time.

---

## Zones & Progression

- The game is divided into **Zones** based on **distance to the Center**.
- Each Zone acts as a **milestone gate**.
- Zones define:
  - Enemy difficulty & types
  - Environmental hazards
  - Required ship tier
  - Required **Hull Tier**
  - Expected player gear & skills

---

### Zone Rules

- You are **not meant to brute-force** higher zones early.
- Entering an under-tiered zone results in:
  - Overwhelming enemies
  - Extreme system strain
  - High infection / hazard rates
  - **Passive hull / environment damage** if hull tier is too low
- Zones enforce **natural progression**, not hard locks.

---

### Hull vs Environment System

Higher zones apply **constant environmental stress** to the ship:

- **Cold Nebula** → hull brittleness, crack chance  
- **Radiation Fields** → slow structural decay  
- **Acid Clouds** → integrity damage over time  
- **Gravitational Shear** → structural HP loss on turns / high speed  
- **EM Storms** → shield collapse + hull exposure  

If hull tier is too low:
- Leaks form automatically  
- Structural HP drains over time  
- Repairs become slower / less effective  

---

### Hull Tier Progression

- **Tier 1 – Scrap Hull**
  - Weak to all environments  
  - Only safe in Zone 1  

- **Tier 2 – Reinforced Hull**
  - Better vs cold + micro-impacts  
  - Needed for Zone 2  

- **Tier 3 – Radiation Shielded Hull**
  - Prevents passive radiation decay  
  - Needed for Zone 3  

- **Tier 4 – Graviton-Stabilized Hull**
  - Handles shear & reality stress  
  - Needed for Zone 4  

- **Tier 5 – Exotic-Infused Hull**
  - Survives full Center exposure  
  - Needed for Zone 5  

---

### Example Zone Structure

- **Zone 1 – Outer Edge**
  - Basic monsters  
  - Low radiation  
  - Starter ship parts  
  - Scrap-tier weapons  
  - **Hull Tier 1 required**

- **Zone 2 – Mid Frontier**
  - Boarding enemies  
  - Power stress events  
  - Research becomes mandatory  
  - Chemical & bacteria systems activate  
  - **Cold nebula exposure**  
  - **Hull Tier 2 required**

- **Zone 3 – Inner Ring**
  - Heavy AI-controlled outposts  
  - Advanced monsters  
  - Structural hull damage common  
  - Fusion-tier tech required  
  - **Radiation + micro-meteor storms**  
  - **Hull Tier 3 required**

- **Zone 4 – Core Approach**
  - Reality anomalies  
  - Antimatter-level threats  
  - Crew sanity collapse risk  
  - Clone system heavily taxed  
  - **Gravitational shear + EM storms**  
  - **Hull Tier 4 required**

- **Zone 5 – The Center**
  - Endgame entities  
  - Wormhole instability  
  - No escape except forward  
  - Final ship configuration required  
  - **Total multi-environment exposure**  
  - **Hull Tier 5 required**

---

### Progression Philosophy

- **Gear check** – Not optional  
- **Crew skill check** – Mandatory  
- **Ship system check** – Constant pressure  
- **Hull check** – Survival gate  

You don’t “level past” zones.  
You **prepare or you die**.

---

## Start-Roles (Boost only, not class-locked)

Each role gives:
- **XP boost in 2–3 skills**
- **Starting gear + uniform**
- **No hard lock** — all players can learn all skills

**Roles:**
- **Engineer** – power, grid, generators  
- **Mechanic** – hull, doors, physical repairs  
- **Captain** – decisions, morale, macro-calls  
- **Navigator** – maps, routes, sensor reading  
- **Medic** – injuries, trauma, drugs  
- **Security** – combat, boarding defense  
- **Researcher** – tech, anomalies, upgrades  
- **Astronaut** – EVA, salvage, external repairs  
- **Trainee** – fast early XP, worst gear  
- **Biochemist** – food, bacteria, chemical safety  

---

## Global Skill System

All players share the same skill pool:

- **Medical** – healing, surgery, trauma, drugs  
- **Engineering** – power, reactors, tuning  
- **Mechanics** – doors, hull, tools, pumps  
- **Combat** – weapons, accuracy, recoil  
- **Navigation** – maps, scanning, routing  
- **Research** – tech upgrades, anomalies, non-bio science  
- **EVA / Space Ops** – zero-G, salvage, exterior repairs  
- **Leadership** – morale, command, panic resist  
- **Survival** – oxygen, cold, radiation, hunger  
- **Psychology** – fear control, mental breaks  
- **Biochemistry** – food safety, toxins, alien bacteria, infections  
- Each player chooses **one Focus Skill** that receives an XP boost.
> **Captain is not a skill** – it is a **role** that usually leans on Leadership + Navigation + some Combat.

---

## Role Overlaps & Coverage

To support **2–8 players**, roles overlap in skills:

- **Engineer**
  - Strong: Engineering  
  - Medium: Mechanics, Research (systems)  

- **Mechanic**
  - Strong: Mechanics  
  - Medium: Engineering, Survival  

- **Captain**
  - Strong: Leadership  
  - Medium: Navigation, Psychology  
  - Calls: zone entry, retreats, clone usage  

- **Navigator**
  - Strong: Navigation  
  - Medium: Leadership, Survival  

- **Medic**
  - Strong: Medical  
  - Medium: Biochemistry, Psychology  

- **Security**
  - Strong: Combat  
  - Medium: Survival, Psychology (stress)  

- **Researcher**
  - Strong: Research  
  - Medium: Biochemistry, Engineering (lab systems)  

- **Astronaut**
  - Strong: EVA / Space Ops  
  - Medium: Survival, Combat  

- **Biochemist**
  - Strong: Biochemistry  
  - Medium: Medical, Research  

- **Trainee**
  - Small boost in everything  
  - Levels faster, but starts very weak  

This lets small crews (2–3 players) **cover all systems** by stacking multiple roles on one player, while bigger crews (6–8) can specialize.

---

## Level System

- **You level SKILLS, not roles**  
- **XP cost increases every level (exponential)**

Natural builds:
- **Specialist**
  - Very strong in 1–2 skills  
  - Severe weaknesses elsewhere  

- **Jack of All Trades**
  - Medium in many skills  
  - Never reaches top-tier power  

- **No free respec** (only with heavy penalty)

---

## Respawning on Death

- **Dead = dead** (character is gone)

**If Clone Bay exists and is powered:**
- Player can be **cloned**:
  - Costs money  
  - Loses 30–50% skill XP  
  - Gains 1 permanent scar (fear, tremor, hallucination risk, etc.)

**If Clone Bay missing or offline:**
- Must **buy a new crew member**:
  - Starts with low skills  
  - Applies a temporary morale penalty to crew  

---

## Ship

- **Grid-based**, can rotate  
- **Local grid + world transform**  
- Struct-based stats (thrust, mass, torque, drag, etc)  
- Only interior visible (unless windows)  
- Camera centered in local ship space  

---

## Ship Parts

### Power & Energy
- Generator / Reactor  
- Batteries  
- Supercapacitors  
- Junction Boxes  
- Power Relays  

### Engine Types

**Raw Fuel Engines**
- Hydrogen  
- Methane  
- Fusion  
- Antimatter  

**Electrical**
- Ion  
- Plasma  
- Arcjet  
- Gyroscope (electrical)  

- Running both at max → **power overload + fuel drain**

### Weapons & Defense
- Turrets / Cannons  
- Point Defense (PD)  
- Missile Launchers  
- Shields  
- Armor Plating  

### Propulsion & Control
- Main Thrusters  
- Maneuver Thrusters  
- Navigation Core  
- Autopilot Module  

### Life Support
- Oxygen Generator  
- CO₂ Scrubbers  
- Heaters / Coolers  
- Pressure Regulators  

### Structural
- Hull Segments  
- Reinforced Hull  
- Airlocks  
- Bulkheads  

### Crafting & Production
- Fabricator  
- Assembler  
- Refinery  
- Recycler  
- Blueprint Terminal  

### Research & Science
- Research Lab  
- Analysis Station  
- Specimen Containment  
- Data Archive  
- Experimental Chamber  

### Biochemical & Food Systems
- **Hydroponics Bay** – food growth  
- **Food Processor** – cooking & nutrient balance  
- **Chemical Lab** – drugs, antitoxins, acids  
- **Decontamination Shower** – removes alien bacteria  
- **Bio-Waste Processor** – prevents outbreaks  

Alien bacteria:
- Infects **food, air systems, wounds, water**  
- Causes:
  - Fear gain  
  - Hallucinations  
  - Organ damage  
- Requires **Biochemistry skill** to detect and neutralize  

### Utility & Systems
- Medbay  
- Cargo Hold  
- Drone Bay  

### Sensors & Comms
- Radar / Scanner  
- Long-range Sensors  
- Communications Array  

### Special
- Cryo Clone Bay  
- Blackbox Recorder  
- Escape Pods  

---

## Enemies

- Monsters  
- AI Outposts / Controllers  

---

## General Tasks

### Generator Handling
- Balance power output vs load  
- Avoid overload / blackout  
- Manage fuel / heat  

### Repairs (All Components)
- Fix hull, doors, systems  
- Replace destroyed modules  
- Seal breaches before environment kills crew  

### Jams
- Unjam doors, turrets, fabricators  
- Clear stuck mechanics  

### Researching
- Analyze anomalies  
- Unlock tech and ship parts  
- Long protected tasks  

### Health Checks (Crew + Ship)
- HP, bleeding, oxygen, pressure  
- Fire exposure, fear  
- Room oxygen / temperature  
- Life support online  
- **Bacteria spread in rooms, food, objects**  

### Driving the Ship
- Throttle, rotation, dodging  
- Docking, EVA alignment  
- Wormhole alignment  

### Map Navigation
- Route selection  
- Hazard marking  
- Wormhole timer vs distance  

---

## Work UI

- **Actual work, not button presses**

**Resource Crusher**
- Drag resources physically  
- Timing & jams  

**Research**
- Active tool-based analysis  
- Misuse causes contamination or explosions  

---

## Dynamic Resource & Material System

All construction uses **dynamic materials**.  
The same item built from different materials gains different:

- Durability  
- Power efficiency  
- Hazard resistance  
- Perks & side effects  
- Tier scaling bonuses  

---

### Material Progression (Base → Endgame)

#### Tier 1 – Scrap & Primitive (Zone 1)
- Scrap Metal  
- Rusted Alloy  
- Carbon Plates  
- Basic Plastics  
- Organic Fibers  

#### Tier 2 – Industrial (Zone 2)
- Steel  
- Copper  
- Aluminum  
- Reinforced Polymer  
- Glass Composite  

#### Tier 3 – Advanced Engineering (Zone 3)
- Titanium Alloy  
- Tungsten  
- Silicon Wafers  
- Superconductive Wire  
- Hardened Ceramics  

#### Tier 4 – Hazard & Energy (Zone 4)
- Leaded Radiation Plating  
- Plasma Conduits  
- Cryo-Stabilized Metal  
- Acid-Resistant Composite  
- High-Density Battery Cells  

#### Tier 5 – Exotic / Endgame (Zone 5)
- Exotic Matter  
- Dark Crystal  
- Antimatter Containment Alloy  
- Graviton-Weave  
- Living Biomaterial  

---

### Example Material Effects

- **Titanium Hull** → Lightweight + high structural HP  
- **Cryo Metal Pipes** → Freeze-resistant life support  
- **Dark Crystal Weapons** → Fear effect on enemies  
- **Living Biomaterial** → Self-repair but infection risk  

**Rule:**  
Material choice changes **system behavior**, not just numbers.
