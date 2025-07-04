# Watchers Game Doc
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
 

## Operators
  - Raven [utility]
    - Watcher Ability: Scavenge
      - Select Material from Menu
      - Live Pings for Each Instance
      - <>s Countdown to Select New Material
    - Reaper Ability: Visio Corvis
      - See Friendly Players through Walls
      - Passive
  - Turtle [tank]
    - Watcher Ability: Hard Shell
      - Reaper Shield
      - Passive
    - Reaper Ability: 
      - Each enemy in range loses 5% max health
      - Turtle gains all health enemies lose
      - More Health
      - Slower Movement
 - Hare [movement]
    - Watcher Ability: Second Wind (may remove)
      - 30% Movement Increase for Reapers (10s)
      - Medium cooldown
      - Active
    - Watcher Ability: Quick Footed (may remove)
      - 10% Movement Increase for Reapers
      - Passive
    - Reaper Ability: 
      - Quick Dash, any direction (quick cooldown)
  - [healer] (not for alpha)
    - Watcher Ability:
      - todo
    - Reaper Ability: 
      - Single Heal (medium cooldown)
      - Team Heal (long cooldown)
  - Ghost [utility] (too complicated for alpha)
    - Watcher Ability: Astral Project
      - AI Reaper Companion
      - Heal Phantom (medium cooldown)
      - Respawn Phantom (long cooldown)
    - Reaper Ability: Plane Shift
      - Self Invisibility (quick cooldown)
      - Team Invisibility (long cooldown)

        
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
  - Operator Camp
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
