# what it is
a simple (most likely bad) solo rpg i made to play during class when its boring (hence the name - Bored At Class RPG) <br/>

# "dice" rolls
4 small papers with number 1-4 are needed (cards) <br/>
skill checks are done by drawing a number of papers equal to the stat, dont mind that there are less papers than at the beginning <br/>
all other card draws are done one at a time, then reshuffling the deck <br/>
if the stat is more than 4, just count the 4 rolls as 10, and continue as normal <br/>
or use this formula: `10 * stat/4 + (n%4)d4` <br/>

# character
there are 4 stats corresponding to 4 classes: <br/>
- strength -> warrior <br/>
- dexterity -> rogue <br/>
- inteligence -> wizard <br/>
- charisma -> bard <br/>

all start on 1 point <br/>

upon character creation, you choose a class, and get a bonus point in the main stat of that class <br/>

you also choose a race, which has effect only in roleplay (if you want), and in villages where costs of items will change <br/>
the x signifies that the races dont like each other <br/>
races that dont hate each other have no significant relationship <br/>
dwarves x elves <br/>
humans x goblins <br/>

health is calculated as strength * 10 <br/>

all characters start with 5 silver <br/>

lastly a nice thing to have is a name <br/>

example character: <br/>
``` 
Entron, human, warrior <br/>
strength 2 <br/>
dexterity 1 <br/>
inteligence 1 <br/>
character 1 <br/>

hp 20/20 <br/>
5 silver <br/>
``` 
a good thing to keep track of the character is to have it all written down on a post-it note, as theres very little so it can fit <br/>

# combat
you can attack once per turn, and either block or dodge incoming attacks <br/>
the block roll: `main char stat x strength + armor` <br/>
the dodge roll: `main char stat x dexterity` <br/>

if the attack succeeds, then the damage is based on the weapon <br/>

## healing
after combat, you will most likely have lost some hp <br/>
you recover health at the end of the day, and depending on where you are, at different speeds <br/>
in a village, you recover all health <br/>
if there is no village, you recover only half of your max health <br/>

## weapons
```
fists: dmg 1
knife: dmg 2, dmg 6 if from behind, cost 2 silver
sword: dmg 3, cost 10 silver
axe: dmg 4, cost 20 silver
bow and arrows: dmg 2, bow cost 10 silver, arrows cost 5 silver
hammer: 4, 6 against armor, cost 30 silver
```

## armor
```
leather: def 2, cost 10 silver
chain: def 4, cost 30 silver
plate: def 6, cost 50 silver
```

## enemy list

```
rat: 1 hp, 1 dmg, 1 str
wolf: 6 hp, 2 dmg, 2 str
skeleton: 10 hp, weapon dmg, 3 str
human: str * 10, weapon dmg, str
goblin: str * 10, weapon dmg, str
elf: str * 10, weapon dmg, str
dwarf: str * 10, weapon dmg, str
```

the playable races are supposed to be equipped similairly to the player <br/>

# worldgen
there are 2 maps, the overmap, and a location map <br/>
overmap is where you keep track of locations and travel larger distances <br/>
locations are where actual gameplay occurs <br/>
to create a new location, you draw a card to find out how many things there are, then draw that number of cards to find out what is there <br/>

1. a dungeon
2. a forest
3. a mountain
4. a village


## villages

a village is the only place where you can shop <br/>

### shops
 every village has a shop with everything important
however they may give you higher or lower costs based on your race
if the villagers dont like your race (dwarves x elves, humans x goblins), they will give you less money for items you sell them (half the value), and demand more money on items you buy from them (double the value)
if you are the same race as the inhabitants, then they will give you more money on items you sell them (one and a half of the value), and will want less money for items you buy (half the value)

### village generation
draw a card for size (used just for roleplay) <br/>
a new card for a special attribute: <br/>

1. destroyed village
2. normal
3. normal
4. a village with a castle

and the last card for the race of the inhabitants <br/>

1. goblins <br/>
2. elves <br/>
3. dwarves <br/>
4. humans <br/>


## dungeon
dungeons are linear, no branching paths <br/>

### dungeon generation
draw a card for length (number of rooms) <br/>
each room is discovered after surviving the last (clearing out the enemies, checking the treasure) <br/>
to know what a room is, draw a card <br/>

1. an empty room <br/>
2. enemies <br/>
3. enemies + treasure (clear out the enemies first before checking the treasure) <br/>
4. treasure (5 silver) <br/>

after the last room, is an extra room with a final treasure of 10 silver <br/>

# leveling up
level points are gained by dealing damage (overkill doesnt count) and clearing out a dungeon (getting to the final room) <br/>
each damage dealt gives 1 point, and clearing out a dungeon gives 5 points for every room (excluding the bonus room) <br/>

