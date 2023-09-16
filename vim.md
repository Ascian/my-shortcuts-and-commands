# vim

## Shortcuts

| Action            | Shortcut  |
| ----------------- | --------- |
| Normal mode       | Caps-Lock |
| Insert mode       | i         |
| Replace mode      | R         |
| Visual mode       | v         |
| Visual line mode  | V         |
| Visual block mode | \<c-v>    |


### Command line 

| Action                | Shortcuts     |
| --------------------- | ------------- |
| Command line mode     | :             |
| quit                  | :q            |
| save                  | :w            |
| save and quit         | :wq           |
| open file for editing | :e            |
| show open files       | :ls           |
| open help             | :help {topic} |


## Movement

| Action                             | Shortcuts                            |
| ---------------------------------- | ------------------------------------ |
| left                               | h                                    |
| down                               | j                                    |
| up                                 | k                                    |
| right                              | l                                    |
| next word                          | w                                    |
| beginning of word                  | b                                    |
| end of word                        | e                                    |
| beginning of line                  | 0                                    |
| first non-blank character          | ^                                    |
| end of line                        | $                                    |
| top of screen                      | H                                    |
| middle of screen                   | M                                    |
| bottom of screen                   | L                                    |
| scroll up                          | \<c-u>                               |
| scroll down                        | \<c-d>                               |
| begin of file                      | gg                                   |
| end of file                        | G                                    |
| line number                        | {number} G                           |
| match beginning and end of a block | %                                    |
| find forward character             | f{character}                         |
| find backward character            | F{character}                         |
| to forward character               | t{character}                         |
| to backward character              | T{character}                         |
| search                             | /{regex}, n/N for navigating matches |

## Edit

| Action                        | Shortcuts                                 |
| ----------------------------- | ----------------------------------------- |
| insert line below             | o                                         |
| insert line above             | O                                         |
| delete {motion}               | d{motion}                                 |
| change {motion}               | c{motion} (equal to d{motion} + i)        |
| delete character              | x (equal to dl)                           |
| substitute character          | s (equals to cl)                          |
| undo                          | u                                         |
| redo                          | \<c-r>                                    |
| copy(yank)                    | y                                         |
| paste                         | p                                         |
| flips the case of a character | ~                                         |
| visual mode + manipulation    | select text + d(to delete) + c(to change) |


## others

* Combine nums and verbs will perform a given action a number of times
    * 3w move 3 words forward
    * 5j move 5 lines down
    *  7dw delete 7 words
* Use modifiers to change the meaning of a noun 'i' means "inner" and 'a' means "around"
    *  ci[ change the content inside the current pair of square brackets
    *  ci( change the content inside the current pair of parentheses
    *  da' delete a single-quoted string including the surrounding single quotes