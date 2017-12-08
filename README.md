# Liero Xtreme Mod: Diablo II

A mod for Liero Xtreme using weapons from Diablo II.

![Screenshot](http://www.danjb.com/images/liero/diablo.jpg)

Players can pick a single class, dual-class, choose any weapons they want, or pick randomly, allowing for a lot of replayability. Each class is very different, but they are all fairly balanced.

## Installation

Compile the text files using *gc.exe* that ships with the game. Place the compiled *script.lgs* and the *gfx* and *sfx* directories in a subfolder in your Liero Xtreme directory.

## Weapons

### Amazon

    Guided Arrow          - Arrow that seeks out players
    Decoy                 - Creates a worm that explodes after time
    Charged Strike        - Close-combat attack that emits charged bolts
    Freezing Arrow        - Arrow that freezes players on contact
    Immolation Arrow      - Arrow that explodes into flames
    Plague Javelin        - Javelin that leaves a trail of poison
    Lightning Fury        - Javelin that emits lightning on contact
    Multiple Shot         - A volley of arrows

### Assassin

    Cobra Strike          - Close-combat attack that heals the user
    Dragon Flight         - Surges the user forward and damages players in its wake
    Psychic Hammer        - Knocks back nearby worms
    Shadow Master         - Creates a worm that throws blades
    Fire Blast            - Simple fire bomb
    Charged Bolt Sentry   - Turret that fires charged bolts
    Wake of Fire          - Trap that fires waves of fire
    Blade Fury            - Throws several blades

### Necromancer

    Raise Skeleton        - Summons a jumping skeleton
    Fire Golem            - Summons a walking golem that leaves a trail of fire
    Revive                - Summons an undead guardian worm
    Teeth                 - Fires many bone projectiles
    Bone Wall             - Creates a solid wall of bone
    Bone Spear            - A fast-moving bone projectile
    Bone Prison           - Creates a solid bone prison around the target
    Poison Nova           - Fires poison in all directions

### Barbarian

    Taunt                 - Sucks nearby enemies inwards
    Grim Ward             - Creates a totem that knocks enemies back
    War Cry               - Damages and stuns nearby enemies
    Battle Orders         - Gives life to all nearby worms
    Double Throw          - Throws an axe and a sword
    Leap Attack           - Launches the user and hurts any enemies below
    Frenzy                - Rapid-fire close-up weapon
    Whirlwind             - Forces the user forward, leaving a destructive trail

### Sorceress

    Frozen Orb            - Fires an orb that emits cold bolts
    Charged Bolt          - Fires many lightning projectiles
    Nova                  - Fires lightning in every direction
    Chain Lightning       - Shoots lightning that generates more lightning on contact
    Thunder Storm         - Hold down to randomly summon thunderbolts all around
    Blaze                 - Hold down to leave a trail of fire
    Fire Wall             - Creates a wall of fire
    Meteor                - Summons a meteor from the sky

### Druid

    Molten Boulder        - Sends out a great fiery boulder
    Arctic Blast          - A short-ranged icy blast
    Twister               - Fires two small hurricanes at enemies
    Volcano               - Summons a volcano that spits out fireballs
    Rabies                - Close-up attack that leaves a cloud of poison
    Raven                 - Summons a raven that floats upwards
    Poison Creeper        - Summons a creeper that leaves a trail of poison
    Oak Sage              - Summons an oak sage that heals nearby worms

### Paladin

    Holy Fire             - Hold down to cause fire damage to nearby enemies
    Holy Freeze           - Hold down to freeze nearby enemies
    Blessed Hammer        - Fires a magic hammer that damages enemies
    Vengeance             - Fires projectiles of ice, fire and lightning
    Charge                - Propels the user forward, sword outstretched
    Fist of the Heavens   - Bolt that travels through walls
    Sacrifice             - Deadly close-combat attack that harms the user
    Holy Bolt             - Fire at an allied worm to heal them

### Special

    Teleport              - Teleports the user forward through walls

## To Do

### General Improvements

 - Change CPU starting weapon (offset weapons in Main.txt)
 - Make Nova weapons less affected by player velocity?
    - Fire a projectile which then releases the nova
 - Fire Wall - spread out from the middle rather than going side-to-side
 - War Cry - improve graphic
 - Poison Creeper - trail disappears before fully animating?
 - Lightning Sentry - bolder graphic?
 - Double Throw - missing frames of animation?
 - Oak Sage - emit glowing particles?
 - Wake of Fire - shoots backwards sometimes (bounces back?)
 - Revive - leave behind giblets?
 - Revive / Charged Sentry - keeps firing after it's gone
    - Turret should seamlessly change into a dummy one towards end-of-life
 - Freezing weapons should share the same freeze projectiles

### Rebalancing

 - Nerf:
    - Plague Javelin
    - Volcano (longer reload?)
    - Arctic Blast (freeze?)
    - Shadow Master (longer reload?)
 - Improve:
    - Sacrifice
    - Decoy (shorter reload?)
    - Taunt (see below)
    - Grim Ward
    - Chain Lightning
    - Blade Fury
    - Dragon Flight
    - Cobra Strike
    - Holy Freeze (bigger freeze radius)
    - Freezing Arrow (bigger freeze radius)

### New Weapons

 - Replace Taunt with Find Item?
    - Creates an "Item" projectile with a random effect when you pick it up, e.g. heal, nova, etc.
    - Use TimerVars to randomly change the item
 - More special weapons:
    - Throwing Potions
    - Healing Potions
    - Diablo's skills (Firestorm, Red Lightning, Fire Nova)
    - Mercenary - Summons a worm to fight by your side
        - Rotates through a bunch of weapons, e.g. Javelins -> Frozen Orbs -> Double Throw
