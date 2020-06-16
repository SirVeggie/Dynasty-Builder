# Dynasty Builder rules

## Game progression

### Start

Each player starts with a level 1 city center placed somewhere within their part of the board and one soldier placed somewhere within 2 tiles of it.

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



## Building

The build phase has 3 different actions:
- Build house
- Replace house with token
- Destroy house or token

3 build actions can be performed during the build phase.\
Building cannot be performed on a tile with an enemy unit.

### Terms:

|  |  |
| ------- | ---- |
| data    | it's great |

**City Area** - The tiles within the city's range\
**Friendly Territory** - The area defined by the combined area of the player's cities\
**Conflicted Territory** - An area in which multiple territories are overlapping\
**Hostile Territory** - An enemy player's territory\
**Combat Power** - Value of the dice + the **Power** of the participating units\
**City Center** - The building built in the center of the city

### City building
Create a 6 house ring and place a [**City Center**](#terms) in the middle to build a city\
Upgrade a city by building an additional ring around the [**City Center**](#terms)\
A new ring must be build as full as possible\
Minimum of 4 houses for level 1 ring, minimum of 6 for above\
[**City Centers**](#terms) can be built on any tile, including water, canyons and mountains\
Houses replaced with tokens do not count towards a new ring\
All previous rings must be complete before upgrading a city\
City consists of connected houses, areas that do not connect do not count towards the rings\
If a city center is being built on top of a friendly unit, move that unit to any valid adjacent tile

### Houses
Houses can be built on [**Friendly Territory**](#terms), or next to a unit\
Houses cannot be built on [**Conflicted Territory**](#terms)\
Houses cannot be built on top of water, canyon or mountain tiles\
Houses can be destroyed by enemy units by moving on top of them or by attacking

### City features
City has a range calculated by **level x 2**\
City has a static base defense of 4\
Each adjacent house grants +1 defense

### City types
**Level 1 - Town**\
Raises unit limit by 1

**Level 2 - City**\
Can recruit [**Ships**](#troops) and [**Infantry**](#troops)

**Level 3 - Fort**\
Can recruit [**Knights**](#troops) and [**Siege Towers**](#troops)

**Level 4 - Military Academy**\
Can generate 1 [**Military Token**](#special-tokens) per turn

**Level 5 - Mage Tower**\
Can use one [**Spell**](#spells) per turn

### Bridges:
- Each player has a single bridge
- Build the bridge on water with one build action
- A new bridge causes the previous to disappear
- Troops can use an enemy's bridge
- Enemy bridge can be destoryed by attacking it
- A bridge occupied by an enemy troop cannot be dismantled



## Marching
- During march phase move and attack with each unit one at a time
- A unit cannot move after attacking
- If a land unit lands on a ship, it will be carried while the ship moves
- A unit carried by a ship cannot attack
- Units moving on the same terrain have a -1 movement penalty when adjacent to enemy units
- Units moving to/from/within a canyon have a -1 movement penalty
- Units can always move at least 1 tile per turn

## Combat
- The **Power** values of both units are added to the dice
- The area of battle is the tile on which the defender party stands
- An attack can be performed even if the unit is out of moves
- In case of a tie, the attacker can back off, or try again
- Each unit only has one attack per turn

### Supporting
- Units can support the battle if the battle area is within their range [(see exception)](#range-attacks)
- The **Power** values of the supporting units are added to the dice during combat

### Range attacks
- The target can choose to evade or retaliate
- Retaliation is only possible if the attacker is within their range
- All normal battles can be supported by ranged units
- Ranged attacks can be supported only by other ranged units **when attacking**
- Ranged attacks can not be supported against **when defending**
- A ranged attack can be evaded by rolling 2 or higher
  - This value can be increased by supporting with additional ships (+2 per ship)

### City siege
- During an attack on a city, only the attacker throws the dice
- If the attacker's combat power exceeds the city's defense, the city is destroyed
- A tie proceeds in the same way as a normal battle

### Spells

## Recruiting and disbanding
- One unit can be recruited per city
- Unit limit is city count + 1
  - 4 cities -> unit limit is 5
- City spawn radius is the same as city radius
- Closest enemy troop to a city limits its spawn radius to: [ *distance to enemy - 2 ]
  - Example: When an enemy troop is within 3 tiles of the city, its spawn radius is limited to 1
- Troops can be disbanded from within friendly territory

- - -

## Special Tokens
### Land tokens

Houses can be replaced with land tokens to gain back houses.\
Land tokens can be swapped back to houses if needed.\
Both require a build action.

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
- City level 2
- Power 1
- Range 1
- Movement 2

### Ship
- City level 2
- Power 1
- Range 2
- Movement 4
- Ranged unit
- Can carry a single unit

### Knight
- City level 3
- Power 2
- Range 1
- Movement 3

### Siege
- City level 3
- Power -1
- Range 1
- Movement 2
- Unconditionally destroys city upon attack
