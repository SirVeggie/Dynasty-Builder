# Dynasty Builder rules

## Game progression

### Start

Each player starts with a level 1 city center in one of the special tiles and one soldier placed somewhere within its radius.

### Round
**1\)** Build\
**2\)** March\
**3\)** Recruit\
**4\)** Disband

### Winning conditions

**Conqueror** - Destroy all enemy city centers\
**Dynasty** - Reach total of 12 city levels\
**Veteran** - Acquire 12 military tokens\
**Timeout** - Achieve highest points after **x** amount of turns or **x** amount of time

### Points

- Cities: Level x 2p
- Level 3 units: 1p
- Military tokens: 1p

- - -

## Building

The build phase has 3 different actions:
- Build house
- Replace house with token
- Destroy house or token

3 build actions can be performed during the build phase.\
Building cannot be performed on a tile with an enemy unit.

### City building
- Create a 6 house ring and place a pagoda in the middle to build a city
- Upgrade a city by building an additional ring around the city
- Minimum of 4 houses for level 1 ring, minimum of 6 for above
- The new ring must be build as much as possible
- City centers can be built on any tile, including water, canyons and mountains
- Houses replaced with tokens do not count towards a new ring
- City consists of connected houses, areas that do not connect do not count towards the rings
- If a city center is being built on top of a friendly unit, move that unit to any valid adjacent tile

### Houses
- To build a house, it must be within a city's build area, or next to a troop (can't be built on another player's radius)
- Houses cannot be built on top of water, canyon or mountain tiles
- Houses can be replaced with land tokens
- Houses can be destroyed by units by moving on top of them or by attacking

### City features
City has a base build radius of 2.\
City gains +2 build radius for each upgrade.\
City has a static base defense of 4.\
Each adjacent house grants +1 defense.\
The attacker's attack power must be the same or higher than the city's defence to destroy the city.

### City types
**Level 1 - Town**\
Raises unit limit by 1

**Level 2 - City**\
Can recruit Ships and Infantry

**Level 3 - Fort**\
Can recruit Knights and Siege Towers

**Level 4 - Military Academy**\
Can generate 1 Military Token per turn

### Bridges:
- The round piece works as a bridge
- Build the bridge on water with one build action
- A new bridge causes the previous to disappear
- Troops can use an enemy's bridge
- Enemy bridge can be destoryed by attacking it
- A bridge occupied by an enemy troop cannot be dismantled

- - -

## Marching
- During march phase move and attack with each unit one at a time
- A unit cannot move after attacking
- If a land unit lands on a ship, it will be carried while the ship moves
- A unit carried by a ship cannot attack
- Units moving on the same terrain have a -1 movement penalty when adjacent to enemy units
- Units moving to/from/within a canyon have a -1 movement penalty

## Attacking
- Power difference contributes to dice number
- Battle area is the defending party's tile
- Additional adjacent troops add their power to the battle
- Attacker wins ties
- Attack can be performed even if the unit is out of moves
- A ranged attack can be dodged by rolling 3 or higher
  - This value can be increased by supporting with additional ships (+1 per ship)

## Recruiting and disbanding
- One unit can be recruited per city
- Unit limit is city count + 1
  - 4 cities -> unit limit is 5
- City spawn radius is the same as city radius
- Enemy troop within city border limits spawn radius to enemy distance to enemy - 2
  - Example: When enemy troop is within 3 tiles from the city, spawn radius is limited to radius 1
- Troop can be disbanded within city range of any level

- - -

## Special Tokens
### Land tokens

Houses can be replaced with land tokens to gain back houses.\
Land tokens can be swapped back to houses if needed. (Requires a build action)

### Military tokens

**Acquiring tokens:**\
Military tokens are awarded for destroying enemy cities.\
Destroying a city center awards as many tokens as its level.\
Losing a level 2 or higher city center drops 1 military token signified by fleeing troops.

**Token usage:**\
Military tokens are worth 1 point when the game ends.\
Military tokens can be used to create units on any tile within friendly territory that is traversable by that unit.\
Unit cannot be created adjacent to enemy troops or structures.\
Created units cannot exceed current unit limit.\
Unit creation must be performed during the recruiting phase.

1 token = level 2 unit\
2 tokens = level 3 unit\
3 tokens = level 1 city center

- - -

## Troops
### Soldier
- Required level 2 city
- Power 1
- Range 1
- Movement 2

### Ship
- Required level 2 city
- Power 1
- Range 2
- Movement 4
- Can carry a single unit

### Knight
- Requires level 3 city
- Power 2
- Range 1
- Movement 3

### Siege
- Required level 3 city
- Power -1
- Range 1
- Movement 2
- Unconditionally destroys city upon attack
