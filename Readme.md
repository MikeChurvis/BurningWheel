# Burning Wheel Tool Belt

Several tools for Burning Wheel:
- [Dice Roller](#dice-roller)
- [Character Burner](#character-burner)
- [Character Tracker](#character-tracker)
- [Ability Tester](#ability-tester)
- [Tables](#tables)
- [Discord Chat Bot](#discord-chat-bot)

## Dice Roller
```
def roll(count: int, 
         shade: Shade = Shade.BLACK, 
         open: bool = False) -> RollOutcome
```
### Dice
Every die in Burning Wheel has **six sides**, 
numbered from 1 to 6 inclusive.

When a die is rolled, it will come to rest on a number. This is
the die's **result**.

A die has one of three **shades**: Black, Grey, or White.
They map to a number called difficulty:

| Shade | Difficulty    | Narrative Meaning 
| ---   | :---:         | ---               
| Black | 3             | standard ability  
| Grey  | 2             | heroic potential  
| White | 1             | supernatural gift 

A die is a **success** if its result is **higher than its
difficulty**. Otherwise, it is a **failure**.

### Rolls




## Character Burner
## Character Tracker
## Ability Tester
## Tables
## Discord Chat Bot