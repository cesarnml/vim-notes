[BEGIN - 07 June 2022]

## Lesson 1  - Basics
The basic movement in vim is accomplished with the right-hand, home row keys: 

**h** (left)
**j** (down)
**k** (up)
**i** (right)

**:q!** - Discards changes and exits vim

**x** - Deletes the character under the cursor (*or to the right*)

**i** - Inserts text before the highlighted character (*or to the left*)

**A** - appends text to the end of the line (very handy)

**:wq** - Saves changes and quits vim


## Lesson 2 - Deletion

**dw** - [delete] to start of next [word], excluding first character - places cursor just to left of next word (no space)

**de** - [delete] to end of current word, including last character - places cursor to left of next word with a space

**d$** - [delete] to end of [line]

The first letter is an `operator`  followed by a `motion`

Motions can be modified via `counts` (e.g. 3w, 2e)

Operators, Counts, and Motions can be combined (e.g d3w)

**dd** - deletes an entire line

**u** - undo previous action

**U** - undo all actions on current line

**CTRL-R** - undo the last undo


## Lesson 3 - The Put/Replace/Change Operator 

**p** - put previously deleted text after cursor (below current line)

**r** - replaces the currently highlighted character (to the right)

**c** - change operator

**ce** - change to end of word

**cc** - change entire line

**c$** - change to end of line - equivalent to **C**

## Lesson 4 - Hopping and Searching

**CTRL-G** - File name, status and cursor location

**G** - Go to end of file

**gg** - Go to beginning of file

**#G** - Go to # line number

**/pattern** - search for pattern and place cursor

**n** - search next forward

**N** - search next backward

**?pattern** - search for pattern in reverse and place cursor there

**CTRL-O** - hop to previous location

**CTRL-I** - hop to newer position

**CRTL-W** - switches windows

**%** - hops to matching bracket

**:s/old/new/[g]** - substitute command (for a single line)

**:#,#s/old/new** - change occurence in between line number

**:%s/old/new/[g]** - change occurence in entire file

## Lesson 5 - External Commands & Visual Mode

**:![COMMAND]** - allows for external command execution

**v** - Visual inspection mode

**:w FILENAME** - write current file to FILENAME

**:r** - Retrieve command

## Lesson 6 - Open/Append/Copy & Paste - Set Option

**o** - Open a line BELOW the current line and changes to INSERT mode

**O** - Open a line ABOVE the current line and changes to INSERT mode

**a** - INSERT text after the cursor

**A** - INSERT text at the end of line

**i** - INSERT text before the cursor

**R** - REPLACE mode

**y** - YANK operator

**yy** - yank whole line

**yw** - yank word

**:set OPTION** - sets an OPTION

SOME OPTIONS:

**ic** - ignore case

**is** - incremental search (show partial matches)

**hls** - highlight search matches

**noOPTION** - turns off option

## Lesson 7 - How to get Help

**:help** - Enter online vim help documentation

**CTRL-D** - Command line completion

**CTRL-W** - Jump to another window

[DONE - 08 June 2022]