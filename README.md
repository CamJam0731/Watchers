ist# Watchers Game Doc
_**Using Unreal Engine 5.5.4**_
## Ideas
- Augments
  - Operator-based (like Rainbow)
    - Specific Player Models (Identifying enemy augments can be done at a glance)
  - Crafted and Uploaded
    - Generic Player Models (Identifying enemy augments cannot be done at a glance)
- Reaper Construction
  - Robot (Pure Conciousness upload, like Avatar)
    - Limited Player Customization
    - Easier to create models
  - Android (Biomechanical copy of Host)
    - Full Player Customization
    - Harder to create models
- "Zombies" Game Mode
  - Possibly add material gathering
  - Need reason to continue infinitely
    - 'Zombies' drop certain valuable items?
      - Harder 'Zombies' drop better items
     
        
## Watchers
- Functions
  - Man the Computer Station
  - Monitor Reaper Vitals
  - Maintain connection to Reapers
- Augments
  - Team disconnect (insane cooldown)
    - Select team to disconnect
  - Respawn Reaper (long cooldown)
    - Activated at Control Panel
   
      
## Reapers
- Functions
  - Complete Objectives
  - Gather materials (for upgrading main base stations)
- Augments
  - Player disconnect (insane cooldown)
    - Nearest enemy player
  - Material Ping <general> (quick cooldown)
  - Material Ping <specific> (medium cooldown)
 

## Specialists
  - Empty [None]
    - Watcher Passive Ability:
      - Reapers get 120% health
    - Reaper Passive Ability:
      - 200% HP
  - Raven [Utility]
    - Watcher Passive Ability: Sharp Eye
      - Outline materials when Reapers look at them
    - Watcher Active Ability: Scavenge
      - Select Material from Menu
      - Live Pings for Each Instance
      - <>s Countdown to Select New Material
    - Reaper Passive Ability: Visio Corvis
      - See Friendly Players through Walls
    - Reaper Active Ability: Adaptive Awareness
      - Ping all enemies within range
  - Turtle [Tank]
    - Watcher Passive Ability: Hard Shell
      - Reaper Shield
    - Watcher Active Ability: Painless Threshold
      - Reapers take 30% less damage for <>s
    - Reaper Passive Ability: Life Pool
      - Each enemy in range loses 5% max health
    - Reaper Active Ability: Testudine Tolerance
      - Turtle gains all health enemies lose
 - Hare [Movement]
    - Watcher Passive Ability: Quick Footed
      - 25% Movement Increase for Reapers
    - Watcher Active Ability: Second Wind
      - 100% Movement Increase for Reapers (10s)
      - Medium cooldown
    - Reaper Passive Ability: "Can't Touch This"
      - Percent chance to ignore incoming damage (excludes fall damage)
    - Reaper Active Ability: Lagomorph Leap
      - Quick Dash, any direction (quick cooldown)
  - [Medic] todo
    - Watcher Passive Ability:
      - todo
    - Watcher Active Ability:
      - todo
    - Reaper Passive Ability:
      - Heal over time
    - Reaper Active Ability:
      - Single Heal (medium cooldown)
      - Team Heal (long cooldown)
  - Ghost [Utility] (too complicated for alpha)
    - Watcher Passive Ability: Astral Project
      - AI Reaper Companion
      - Heal Phantom (medium cooldown)
      - Respawn Phantom (long cooldown)
    - Reaper Passive Ability: Shadow Walk
      - Can walk through certain doors/barricades
    - Reaper Active Ability: Plane Shift
      - Team Invisibility (long cooldown)

## Classes
- Movement
  - Used to access out of reach places
    - Parkour, double jump, dash, etc.
  - Functions as DPS
    - Higher Speed
    - Lower Health
    - Higher Crit. Multiplier
- Utility
  - Used to unlock areas otherwise inaccessible
    - Hacking, precision destruction, etc.
  - Medium Health
  - Medium Speed
- Tank
  - Higher Health
  - Lower Speed
  - More carry weight
- Medic
  - Heal Other Players without using materials
  - Medium Health
  - Medium Speed 
        
## Main Base
- Themes
  - Van
    - Starting theme
    - Very basic
    - Minimal room/stations
  - Prison Cell
    - Possible Story-Related
    - Multiple Cells allowws for more room
  - Field Base
    - Outdoor Makeshift Field Setup
    - Can only support low-tier stations
  - Cabin
    - More room
    - Mid-game base, supports all but high-tier stations
  - Futuristic
    - Late-game theme
    - supports all stations
- Stations
  - Computer Station
    - Upgrade main base (outside game)
    - Monitor Reaper Vitals (in game)
    - Camera Monitors (in game)
  - Reaper Pods
    - Where Reapers go to get in the level
    - Slot for weapon, any augments/attachments will be sent with Reaper
      - Last imputed weapon is what is sent
    - Slot of Player Augments (If there are no operators)
  - Firing Range
      - Test weapon Augments/Attachments
  - Weapon Bench
    - Craft Augments
    - Craft Weapons
    - Attach Weapon Augments/Attachments
  - Control Panel/Shop
    - Fix any sabotages (in game)
    - Buy Cosmetics (outside game)
  - Specialist Camp
    - Select Operator
    - Acquire New Operators
    - View Operator Health
      - Health regen is tied to level of Camp
   
      
## Maps
- Small Maps

- Medium Maps
  - Dense Forest
    - Aztec Theme?
    - Log Cabin?
  - Desert
    - Rundown Buildings for Cover
    - Middle East?
  - Snow (Possibly mixture between forest and glacier areas)
    - Log Cabin?
  - Small Town
    - Wild West?
    - Modernized?
- Large Maps
  - City
  - Castle
  - Prison
 
    
## Game Modes
- Capture the Flag
  - Small Map
  - 2 Teams
- Team Deathmatch
  - Small/Medium Map
- Hardpoint
  - Medium Map
  - 3-4 Teams
  - Attacking Teams have no Watcher, instead have 4 Reapers
  - Attack Reapers automatically respawn (5s cooldown) in their respective sides of the map
  - Take over the hardpoint to gain access to a Watcher (physically in Hardpoint)
  - Defending Watcher functions as normal
  - Defending Reapers only respawn when someone accesses the Control Panel, then respawn in Hardpoint (10s cooldown)
  - Holding the Hardpoint gives points towards objective
  - Team with the most points after time, or first to hit a threshold wins
- Domination
  - Medium Map
  - 3-4 Teams
  - Similar to Hardpoint, each Choke Point gives a team points towards objective
  - Team with the most points after time, or first to hit a threshold wins
- Material Gathering
  - Large Map
  - 10+ Teams
  - No Respawns, unless Watcher activates it
  - Main goal is to gather materials to upgrade main base
  - Exfil as team to get materials
  - If a Reaper dies with materials, all materials are dropped for other players to grab
- Zombies/Round Based Survival?
  - Medium/Large Map
  - 1 Team
 
    
## Lore
- Group of Hackers, hacked into a major security company who ran a biomechanical AI Police force
