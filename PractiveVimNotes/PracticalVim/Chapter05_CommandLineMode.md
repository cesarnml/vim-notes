# Chapter 05 - Command-Line Mode (28 pages)

> In the beginning, there was ed, ed begat ex, and ex begat vi, and vi begat Vim
>
> - The Old Testament of Unix

## Tip 27 - Meet Vim's Command Line

- *Ex commands strike far and wide*

## Tip 28 - Execute a Command on One or More Consecutive Lines

- `:d`- delete range and place in register
- `:y`- yank range and place in register
- `:put` - [line] put [x] register at specified line
- `:normal` - apply normal commands to given range
- `[range]` - range #,#
- `%` - symbol for entire file

## Tip 29 - Duplicate or Move Lines Using `:t` and `:m` Commands

- `:t` - copy range to address
- `:m` - move range to address
- `:[range] copy/move {address}`

## Tip 30 - Run Normal Mode Commands Across a Range

- `:normal A;` - Add semicolon at the end of all lines
- `:normal i//` - Comment out all lines (JS)

## Tip 31 - Repeat the Last Ex Command

- `@:` - repeat last Ex command; use `@@` - after one repeat for multiple repeats
- `<C-o>` - goes one step back in the jump list (maynot work because of my funcy ctrl scheme)

## Tip 32 - Tab-Complete Your Ex Commands

- Remember to make use of tab completions in Ex mod

## Tip 33 - Insert the Current Word at the Command Prompt


## Tip 34 - Recall Commands from History

## Tip 35 - Run Commands in the Shell

## Tip 36 - Run Multiple Ex Commands as a Batch
