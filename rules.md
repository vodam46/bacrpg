# what it is
a simple (most likely bad) solo rpg i made to play during class when its boring (hence the name - Bored At Class RPG)

# "dice" rolls
4 small papers with number 1-4 are needed (cards)
skill checks are done by drawing a number of papers equal to the stat, dont mind that there are less papers than at the beginning
all other card draws are done one at a time, then reshuffling the deck
if the stat is more than 4, just count the 4 rolls as 10, and continue as normal
or use this formula: `10 * stat/4 + (n%4)k4`

# character
there are 4 stats corresponding to 4 classes:
strength -> warrior
dexterity -> rogue
inteligence -> wizard
charisma -> bard

all start on 1 point

upon character creation, you choose a class, and get a bonus point in the main stat of that class

you also choose a race, which has effect only in roleplay (if you want), and in villages, where you will get either lower (half on buying, one half more on selling), normal, or higher costs on items (double on buying, half on selling)
the x signifies that the races dont like each other, meaning you will get higher costs on bought items and lower costs on sold items
races that dont hate each other have normal costs, and your race will give you lower costs on buying and higher costs on selling
dwarves x elves
humans x goblins

health is calculated by strength * 10

all characters start with 5 silver

lastly a nice thing to have is a name

example character:
`
Entron, human, warrior
strength 2
dexterity 1
inteligence 1
character 1

hp 20/20
5 silver
`
a good thing to keep track of the character is to have it all written down on a post-it note, as theres very little so it can fit

# combat
you can attack once per turn, and either block or dodge incoming attacks
the block roll: `main char stat x strength + armor`
the dodge roll: `main char stat x dexterity`

if the attack succeeds, then the damage is based on the weapon

## weapons
`
fists: dmg 1
knife: dmg 2, dmg 6 if from behind, cost 2 silver
sword: dmg 3, cost 10 silver
axe: dmg 4, cost 20 silver
bow and arrows: dmg 2, bow cost 10 silver, arrows cost 5 silver
hammer: 4, 6 against armor, cost 30 silver
`
## armor
leather: def 2, cost 10 silver
chain: def 4, cost 30 silver
plate: def 6, cost 50 silver

## enemy list
rat: 1 hp, 1 dmg, 1 str
wolf: 6 hp, 2 dmg, 2 str
skeleton: 10 hp, weapon dmg, 3 str
human: str * 10, weapon dmg, str
goblin: str * 10, weapon dmg, str
elf: str * 10, weapon dmg, str
dwarf: str * 10, weapon dmg, str

the playable races are supposed to be equipped similairly to the player

# worldgen
there are 2 maps, the overmap, and a location map
overmap is where you keep track of locations and travel larger distances
locations are where actual gameplay occurs
to create a location, you draw a card to find out how many things are there, then draw that number of cards to find out what is there
1: a dungeon
2: a forrest
3: a mountain
4: a village

## villages

a village is the only place where you can shop

### village generation
draw a card for size (used just for roleplay)
a new card for a special attribute:
1: destroyed village
2: normal
3: normal
4: a village with a castle
and the last card for what race the inhabitants
1: goblins
2: elves
3: dwarves
4: humans

## dungeon
dungeons are linear, no branching paths

### dungeon generation
draw a card for length (number of rooms)
each room is discovered after surviving the last (clearing out the enemies, checking the treasure)
to know what a room is, draw a card
1: an empty room
2: enemies
3: enemies + treasure (clear out the enemies first before checking the treasure)
4: treasure (5 silver)
after the last room, is an extra room with a final treasure of 10 silver

# leveling up
level points are gained by dealing damage (overkill doesnt count) and clearing out a dungeon (getting to the final room)
each damage dealt gives 1 point, and clearing out a dungeon 5 points for every room
