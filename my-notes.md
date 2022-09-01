# Vim Consolidated Notes

- [Vim Consolidated Notes](#vim-consolidated-notes)
  - [VimTutor](#vimtutor)
    - [Lesson 1 - Basics](#lesson-1---basics)
    - [Lesson 2 - Deletion](#lesson-2---deletion)
    - [Lesson 3 - The Put/Replace/Change Operator](#lesson-3---the-putreplacechange-operator)
    - [Lesson 4 - Hopping and Searching](#lesson-4---hopping-and-searching)
    - [Lesson 5 - External Commands \& Visual Mode](#lesson-5---external-commands--visual-mode)
    - [Lesson 6 - Open/Append/Copy \& Paste - Set Option](#lesson-6---openappendcopy--paste---set-option)
    - [Lesson 7 - How to get Help](#lesson-7---how-to-get-help)
  - [Primeagen Guide to VIM](#primeagen-guide-to-vim)
    - [Basic Movement](#basic-movement)
    - [Foundation for Speed](#foundation-for-speed)
    - [Horizontal Speed](#horizontal-speed)
    - [Vertical Domination](#vertical-domination)
    - [Going Full Vim - File Movements, Buffers, Splits](#going-full-vim---file-movements-buffers-splits)
    - [Vim Long and Prosper](#vim-long-and-prosper)
  - [Vim MIT Lecture Notes](#vim-mit-lecture-notes)
    - [Vim is a modal editor](#vim-is-a-modal-editor)
    - [Movement in VIM](#movement-in-vim)
    - [Editing with VIM](#editing-with-vim)
    - [Modifiers in VIM](#modifiers-in-vim)
    - [Windows in VIM](#windows-in-vim)
  - [Surround.vim Plugin](#surroundvim-plugin)
    - [Change Surround](#change-surround)
    - [Delete Surround](#delete-surround)
    - [Yank(Add) Surround](#yankadd-surround)
  - [Practical Vim Book Notes](#practical-vim-book-notes)
    - [Chapter 00 - Movement Commands](#chapter-00---movement-commands)
    - [Chapter 01 - The Vim Way (11 pages)](#chapter-01---the-vim-way-11-pages)
      - [Tip 1 - Meet the Dot Command](#tip-1---meet-the-dot-command)
      - [Tip 2 - Don't Repeat Yourself](#tip-2---dont-repeat-yourself)
      - [Tip 3 - Take One Step Back, Then Three Forward](#tip-3---take-one-step-back-then-three-forward)
      - [Tip 4 - Act, Repeat, Reverse](#tip-4---act-repeat-reverse)
      - [Tip 5 - Find and Replace by Hand](#tip-5---find-and-replace-by-hand)
      - [Tip 6 - Meet the Dot Formula](#tip-6---meet-the-dot-formula)
    - [Chapter 02 - Normal Mode (12 pages)](#chapter-02---normal-mode-12-pages)
      - [Tip 07 - Pause with Your Brush Off the Page](#tip-07---pause-with-your-brush-off-the-page)
      - [Tip 08 - Chunk Your Undos](#tip-08---chunk-your-undos)
      - [Tip 09 - Compose Repeatable Changes](#tip-09---compose-repeatable-changes)
      - [Tip 10 - Use Counts to Do Simple Arithmetic](#tip-10---use-counts-to-do-simple-arithmetic)
      - [Tip 11 - Don't Count If You Can Repeat](#tip-11---dont-count-if-you-can-repeat)
      - [Tip 12 - Combine and Conquer](#tip-12---combine-and-conquer)
    - [Chapter 03 Insert Mode (9 pages)](#chapter-03-insert-mode-9-pages)
      - [Tip 13 - Make Corrections Instantly from Insert Mode](#tip-13---make-corrections-instantly-from-insert-mode)
      - [Tip 14 - Get Back to Normal Mode](#tip-14---get-back-to-normal-mode)
      - [Tip 15 - Paste from a Register Without Leaving Insert Mode](#tip-15---paste-from-a-register-without-leaving-insert-mode)
      - [Tip 16 - Do Back-of-the-Envelope Calculations in Place](#tip-16---do-back-of-the-envelope-calculations-in-place)
      - [Tip 17 - Insert Unusual Characters by Character Code](#tip-17---insert-unusual-characters-by-character-code)
      - [Tip 18 - Insert Unusual Character by Diagraph](#tip-18---insert-unusual-character-by-diagraph)
      - [Tip 19 - Overwrite Existing Text with Replace Mode](#tip-19---overwrite-existing-text-with-replace-mode)
    - [Chapter 04 - Visual Mode (14 pages)](#chapter-04---visual-mode-14-pages)
      - [Tip 20 - Grok Visual Mode](#tip-20---grok-visual-mode)
      - [Tip 21 - Define a Visual Selection](#tip-21---define-a-visual-selection)
      - [Tip 22 - Repeats Line-Wise Visual Commands](#tip-22---repeats-line-wise-visual-commands)
      - [Tip 23 - Prefer Operators to Visual Commands Where Possible](#tip-23---prefer-operators-to-visual-commands-where-possible)
      - [Tip 24 - Edit Tabular Data with Visual-Block Mode](#tip-24---edit-tabular-data-with-visual-block-mode)
      - [Tip 25 - Change Columns of Text](#tip-25---change-columns-of-text)
      - [Tip 26 - Append After a Ragged Visual Block](#tip-26---append-after-a-ragged-visual-block)
    - [Chapter 05 - Command-Line Mode (28 pages)](#chapter-05---command-line-mode-28-pages)
      - [Tip 27 - Meet Vim's Command Line](#tip-27---meet-vims-command-line)
      - [Tip 28 - Execute a Command on One or More Consecutive Lines](#tip-28---execute-a-command-on-one-or-more-consecutive-lines)
      - [Tip 29 - Duplicate or Move Lines Using `:t` and `:m` Commands](#tip-29---duplicate-or-move-lines-using-t-and-m-commands)
      - [Tip 30 - Run Normal Mode Commands Across a Range](#tip-30---run-normal-mode-commands-across-a-range)
      - [Tip 31 - Repeat the Last Ex Command](#tip-31---repeat-the-last-ex-command)
      - [Tip 32 - Tab-Complete Your Ex Commands](#tip-32---tab-complete-your-ex-commands)
      - [Tip 33 - Insert the Current Word at the Command Prompt](#tip-33---insert-the-current-word-at-the-command-prompt)
      - [Tip 34 - Recall Commands from History](#tip-34---recall-commands-from-history)
      - [Tip 35 - Run Commands in the Shell](#tip-35---run-commands-in-the-shell)
      - [Tip 36 - Run Multiple Ex Commands as a Batch](#tip-36---run-multiple-ex-commands-as-a-batch)
    - [Chapter 08 - Navigate Inside Files with Motions (22 pages)](#chapter-08---navigate-inside-files-with-motions-22-pages)
      - [Tip 47 - Keep Your Fingers on the Home Row](#tip-47---keep-your-fingers-on-the-home-row)
      - [Tip 48 - distinguish Between Real Lines and Display Lines](#tip-48---distinguish-between-real-lines-and-display-lines)
      - [Tip 49 - Move Word-Wise](#tip-49---move-word-wise)
      - [Tip 50 - Find by Character](#tip-50---find-by-character)
      - [Tip 51 - Search to Navigate](#tip-51---search-to-navigate)
      - [Tip 52 - Trace your Selection with Precision Text Objects](#tip-52---trace-your-selection-with-precision-text-objects)
      - [Tip 53 - Delete Around, or Change Inside](#tip-53---delete-around-or-change-inside)
      - [Tip 54 - Mark Your Place and Snap Back to It](#tip-54---mark-your-place-and-snap-back-to-it)
      - [Tip 55 - Jump Between Matching Parentheses](#tip-55---jump-between-matching-parentheses)
    - [Chapter 09 - Navigate Between Files with Jumps (8 pages)](#chapter-09---navigate-between-files-with-jumps-8-pages)
      - [Tip 56 - Traverse the Jump List](#tip-56---traverse-the-jump-list)
      - [Tip 57 - Traverse the Change List](#tip-57---traverse-the-change-list)
      - [Tip 58 - Jump to the Filename Under the Cursor](#tip-58---jump-to-the-filename-under-the-cursor)
      - [Tip 59 - Snap Between Files Using Global Marks](#tip-59---snap-between-files-using-global-marks)
    - [Chapter 10 - Copy and Paste (18 pages)](#chapter-10---copy-and-paste-18-pages)
      - [Tip 60 - Delete, Yank, and Put with Vim's Unnamed Register](#tip-60---delete-yank-and-put-with-vims-unnamed-register)
      - [Tip 61 - Grok Vim's Registers](#tip-61---grok-vims-registers)
      - [Tip 62 - Replace a Visual Selection with a Register](#tip-62---replace-a-visual-selection-with-a-register)
      - [Tip 63 - Paste from a Register](#tip-63---paste-from-a-register)
      - [Tip 64 - Interact with the System Clipboard](#tip-64---interact-with-the-system-clipboard)
    - [Chapter 11 - Macros (21 pages)](#chapter-11---macros-21-pages)
      - [Tip 65 - Record and Execute a Macro](#tip-65---record-and-execute-a-macro)
      - [Tip 66 - Normalize, Strike, Abort](#tip-66---normalize-strike-abort)
      - [Tip 67 - Play Back with a Count](#tip-67---play-back-with-a-count)
      - [Tip 68 - Repeat a Change on Contiguous Lines](#tip-68---repeat-a-change-on-contiguous-lines)
      - [Tip 69 - Append Commands to a Macro](#tip-69---append-commands-to-a-macro)
      - [Tip 70 - Act Upon a Collection of Files](#tip-70---act-upon-a-collection-of-files)
      - [Tip 71 - Evaluate an Iterator to Number Items in a List](#tip-71---evaluate-an-iterator-to-number-items-in-a-list)
      - [Tip 72 - Edit the Contents of a Macro](#tip-72---edit-the-contents-of-a-macro)
  - [Internet Article Notes](#internet-article-notes)
    - [vscode-neovim github](#vscode-neovim-github)

## VimTutor

### Lesson 1 - Basics

The basic movement in vim is accomplished with the right-hand, home row keys:

**h** (left)
**j** (down)
**k** (up)
**i** (right)

**:q!** - Discards changes and exits vim

**x** - Deletes the character under the cursor (_or to the right_)

**i** - Inserts text before the highlighted character (_or to the left_)

**A** - appends text to the end of the line (very handy)

**:wq** - Saves changes and quits vim

### Lesson 2 - Deletion

**dw** - [delete] to start of next [word], excluding first character - places cursor just to left of next word (no space)

**de** - [delete] to end of current word, including last character - places cursor to left of next word with a space

**d$** - [delete] to end of [line]

The first letter is an `operator` followed by a `motion`

Motions can be modified via `counts` (e.g. 3w, 2e)

Operators, Counts, and Motions can be combined (e.g d3w)

**dd** - deletes an entire line

**u** - undo previous action

**U** - undo all actions on current line

**CTRL-R** - undo the last undo

### Lesson 3 - The Put/Replace/Change Operator

**p** - put previously deleted text after cursor (below current line)

**r** - replaces the currently highlighted character (to the right)

**c** - change operator

**ce** - change to end of word

**cc** - change entire line

**c$** - change to end of line - equivalent to **C**

### Lesson 4 - Hopping and Searching

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

**CTRL-W** - switches windows

**%** - hops to matching bracket

**:s/old/new/[g]** - substitute command (for a single line)

**:#,#s/old/new** - change occurrence in between line number

**:%s/old/new/[g]** - change occurrence in entire file

### Lesson 5 - External Commands & Visual Mode

**:![COMMAND]** - allows for external command execution

**v** - Visual inspection mode

**:w FILENAME** - write current file to FILENAME

**:r** - Retrieve command

### Lesson 6 - Open/Append/Copy & Paste - Set Option

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

### Lesson 7 - How to get Help

**:help** - Enter online vim help documentation

**CTRL-D** - Command line completion

**CTRL-W** - Jump to another window

## Primeagen Guide to VIM

### Basic Movement

- [YouTube](https://www.youtube.com/watch?v=H3o4l4GVLW0)
- keys: `w b h j k l y p d v V :w <esc>`
  - basic movement: `h j k l`
  - Word-hop forward/back: `w b`
  - Copy/Paste: `y p`
  - Delete: `d`
  - Visual/Visual-line mode: `v V`
  - Save: `w`
  - Enter Normal mode: `<esc>`

### Foundation for Speed

- [YouTube](https://www.youtube.com/watch?v=gSHf_b6AWKc)
- keys: `o O p P a I A / ? n N * #`
  - Insert line below/above: `o O`
  - Paste line below/above: `p P`
  - Insert mode at first/last non-empty character on line: `I A`
  - Forward/Backward Search and Next/Previous match: `/ ? n N`
  - Search forward/backward on current word: `* #`

### Horizontal Speed

- [YouTube](https://www.youtube.com/watch?v=Q6mr7w0YmkQ)
- keys: `f t F T ; , x s c D C S`
  - Jump to/before character on current line forward/back and next/previous match: `f t F T ; ,`
  - Delete single character and also go into insert mode: `x s`
  - Delete word and go into insert mode: `dw cw`
  - Delete reset of line and also insert mode: `D C`
  - Delete entire line and go into insert mode: `S`

### Vertical Domination

- [YouTube](https://www.youtube.com/watch?v=4uPRlnTUlMY)

### Going Full Vim - File Movements, Buffers, Splits

- [YouTube](https://www.youtube.com/watch?v=N05REqmq0X4)

### Vim Long and Prosper

- [YouTube](https://www.youtube.com/watch?v=e1BFdY0NBLY)

## Vim MIT Lecture Notes

### Vim is a modal editor

`Esc` - Enter NORMAL mode
`i` - Enter INSERT mode BEFORE cursor
`a` - Enter INSERT mode AFTER cursor
`A` - Enter INSERT mode AFTER end of line
`R` - Enter REPLACE mode until hit ESC
`r` - Enter REPLACE mode for a single next character
`v` - Enter VISUAL mode
`V` - Enter VISUAL line mode
`CTRL-V` - Enter VISUAL block mode
`:` - Enter COMMAND-LINE mode

### Movement in VIM

`^` - Move to first non-blank character in a line

`H` - Move to TOP of screen
`M` - Move to MIDDLE of screen
`L` - Move to BOTTOM of screen

`CTRL-u` - SCROLL Up
`CTRL-d` - SCROLL Down

`#G` - Jump to line number

### Editing with VIM

`~` - Flips the character under cursor

### Modifiers in VIM

`ci(` - change content INSIDE current parentheses
`da'` - deletes single quote content INCLUSIVE (AROUND)

### Windows in VIM

`:sp` - split panel (HORIZONTAL)
`vsp` - split panel (VERTICAL)

Also completed [EXERCISES]

- Plugins to read about:
  - `surround.vim`
  - `repeat.vim`
  - `matchit.vim`

## Surround.vim Plugin

### Change Surround

- `cs[old][new]` - change surround

### Delete Surround

- `ds[old]` - delete surround

### Yank(Add) Surround

- `ysiw[new]` - yank surround + text object
- `yss[new]` - yank surround entire line

## Practical Vim Book Notes

### Chapter 00 - Movement Commands

`t/T/f/F` - toward a character and forward to character

`; and ,` - next/previous instance of above

`* and #` - find next/previous instance of current word

`< > =` - indentation related commands

`vim -u NONE -N` - start vim in default mode

### Chapter 01 - The Vim Way (11 pages)

#### Tip 1 - Meet the Dot Command

_The dot command lets us repeat the last change. It is the most powerful and versatile command in Vim._

- The `dot` command is a micro macro. haha!

#### Tip 2 - Don't Repeat Yourself

- Use combined shortcuts like `A` to be more efficient.

#### Tip 3 - Take One Step Back, Then Three Forward

- `f{char}` which searches for the given character can be combined with `;` and `.` to be super powerful.

#### Tip 4 - Act, Repeat, Reverse

- Handy commands and their reverse:
  - `.`: Repeat the last change. `u` reverses the last change.
  - `;`: Forward line search next char. `,` reverse line search previous char. Equivalent to `F{char}`.
  - `n`: Forward search next char. `N` reverse search previous char.
  - `:s/target/replacement`: Perform forward substitution. Repeat using `&` and undo using `u`.
  - `qx{changes}q`: Perform a macro. `u` reverses the macro.

#### Tip 5 - Find and Replace by Hand

- `*` Searches for the next occurrence of the word under the cursor.
- `n` Let's you repeat the previous search. Handy for quick search/edits, repeat.
- `*`, `cw`, `edit`, `*`, `.` Boom!

#### Tip 6 - Meet the Dot Formula

- _The goal: One Keystroke to Move, One Keystroke to Execute_

### Chapter 02 - Normal Mode (12 pages)

- `Normal` mode is Vim's natural resting mode
- _Just as a painter spends a fraction of their time applying paint, programmers spend a fraction of their time composing code._

#### Tip 07 - Pause with Your Brush Off the Page

- Make `Normal` your default (make it a habit)

#### Tip 08 - Chunk Your Undos

- Entering Insert mode and leaving to Normal _typically_ corresponds to an `undo`able chunk

#### Tip 09 - Compose Repeatable Changes

- `daw` delete a word (works great with the `.` operator)
- _Develop a habit of making your changes repeatable wherever possible, then Vim will reward you for it_

#### Tip 10 - Use Counts to Do Simple Arithmetic

- `<C-a>` adds a number to the current line
- `<C-x>` subtracts a number to the current line

#### Tip 11 - Don't Count If You Can Repeat

- No real useful advice here other than don't over count when a repeat might suffice

#### Tip 12 - Combine and Conquer

- `dap` deletes a paragraph
- _An `action` is composed from an `operator` followed by a `motion`_

### Chapter 03 Insert Mode (9 pages)

#### Tip 13 - Make Corrections Instantly from Insert Mode

- `<C-u>` - deletes back to start of line (also works in the terminal)
- `<C-w>` - deletes back to start of word (also works in the terminal)

#### Tip 14 - Get Back to Normal Mode

- `zz` - redraws screen with the current line in the middle

#### Tip 15 - Paste from a Register Without Leaving Insert Mode

- `<C-r>` - pastes from register

#### Tip 16 - Do Back-of-the-Envelope Calculations in Place

- `<C-r>=` - pastes from expression register (didn't work in neovim inside vscode)

#### Tip 17 - Insert Unusual Characters by Character Code

- `<C-v>` - inserts a character by character code (didn't work in neovim inside vscode)

#### Tip 18 - Insert Unusual Character by Diagraph

- `<C-k>{char1}{char2}` - inserts a character by diagraph (didn't work in neovim inside vscode)

#### Tip 19 - Overwrite Existing Text with Replace Mode

- `R and gR` - Replace mode and Virtual Replace mode
- `r and gr` - Single-shot replace mode and virtual replace mode

### Chapter 04 - Visual Mode (14 pages)

#### Tip 20 - Grok Visual Mode

- `c` - In visual mode, deletes the selected text and changes into Insert mode
  - Useful for wrapping changed selected text with quotes or brackets!!!

#### Tip 21 - Define a Visual Selection

- `v` - _character-wise Visual mode_
- `V` - _line-wise Visual mode_
- `<C-v>` - _block-wise Visual mode_
- `gv` - reselect the last visual selection
- `o` go to end of highlighted text (ping-pong cursor)
  - `o` is handy for redefining the begin/end points of the selection

#### Tip 22 - Repeats Line-Wise Visual Commands

- `.` - repeats the edit on the previously selected text when using visual-line mode
- `vit` - visual select in-between tags

#### Tip 23 - Prefer Operators to Visual Commands Where Possible

- `gU` - uppercase the following motion
- _As a general rule, we should prefer operator commands over this Visual mode equivalents when working through a repetitive set of changes_

#### Tip 24 - Edit Tabular Data with Visual-Block Mode

- Fancy visual block-mode kung-fu

#### Tip 25 - Change Columns of Text

- Not that block mode works like you think it should but you won't see the multiple cursor effect until you re-enter normal mode

#### Tip 26 - Append After a Ragged Visual Block

- Visual block-mode is actually quite useful. Similar to vscode native multi-cursor functionality
- Note `i` and `a` while in visual or operator-pending mode represent the `inside` and `around` part of a `text object`

```javascript
In the beginning, there was ed. ed begat ex, and ex begat vi, and vi begat Vim.
- The Old Testament of Unix
```

### Chapter 05 - Command-Line Mode (28 pages)

> In the beginning, there was ed, ed begat ex, and ex begat vi, and vi begat Vim
>
> - The Old Testament of Unix

#### Tip 27 - Meet Vim's Command Line

- _Ex commands strike far and wide_

#### Tip 28 - Execute a Command on One or More Consecutive Lines

- `:d`- delete range and place in register
- `:y`- yank range and place in register
- `:put` - [line] put [x] register at specified line
- `:normal` - apply normal commands to given range
- `[range]` - range #,#
- `%` - symbol for entire file

#### Tip 29 - Duplicate or Move Lines Using `:t` and `:m` Commands

- `:t` - copy range to address
- `:m` - move range to address
- `:[range] copy/move {address}`

#### Tip 30 - Run Normal Mode Commands Across a Range

- `:normal A;` - Add semicolon at the end of all lines
- `:normal i//` - Comment out all lines (JS)

#### Tip 31 - Repeat the Last Ex Command

- `@:` - repeat last Ex command; use `@@` - after one repeat for multiple repeats
- `<C-o>` - goes one step back in the jump list (may not work because of my fancy ctrl scheme)

#### Tip 32 - Tab-Complete Your Ex Commands

- Remember to make use of tab completions in Ex mod
- `<C-d>` - invokes completion menu

#### Tip 33 - Insert the Current Word at the Command Prompt

- `<C-r><C-w>` - inserts current word in command line prompt (Doesn't work in vscode)
  :

#### Tip 34 - Recall Commands from History

- `q:` - opens command line menu (doesn't work in vscode)

#### Tip 35 - Run Commands in the Shell

- `:!` - runs command in shell (doesn't work in vscode)
  - In vscode, output of external command is sent to neovim output console
- `%` - in command line mode, % represents the current file name
- `:shell` - opens (interactive) shell in command line mode (return to vim by typing `exit`)
- `:write {cmd}` - buffer is provided as input to cmd
- `:read {cmd}` - output of cmd is placed in buffer

#### Tip 36 - Run Multiple Ex Commands as a Batch

- `:source` - to execute a vim script; don't need leading `:`
- `:argdo source [filename]` - to run script on multiple files

### Chapter 08 - Navigate Inside Files with Motions (22 pages)

#### Tip 47 - Keep Your Fingers on the Home Row

- Just a reminder to use `h (left), j (down), k (up), l (right)` for movement in place of the arrow keys

#### Tip 48 - distinguish Between Real Lines and Display Lines

- `gj and gk` - move down/up display line wise
- `^` - move to first non-blank character of a display line
- Basically prefix the real line movement keys with `g` to get the analogues display line movement

#### Tip 49 - Move Word-Wise

- `w` - move forward to start of next word
- `b` - move backward to start of current/previous word
- `e` - move forward to end of current/next word
- `ge` - move backward to end of previous word
- `W, B, E, gE` - WORD movements

#### Tip 50 - Find by Character

- `f{char}` - move by character in current line, also `F, t, T`

#### Tip 51 - Search to Navigate

- `/{pattern}` - search forward for pattern, `?{pattern}` - search backward for pattern
- Consider setting `hlsearch` and `incsearch` settings; relates keys `n` and `N` o hop
- Using the `d{motion}` in combination with `/{pattern}` search is a powerful combination

#### Tip 52 - Trace your Selection with Precision Text Objects

- `t` - Text Object to reference HTML tags
- `i` - Inside text object
- `a` - All text object
- `b` - parentheses delimiter
- `B` - curly brackets delimiter
- Set of possible delimiters include: `), }, ], >, ', ", backtick, t, b, B`

#### Tip 53 - Delete Around, or Change Inside

- `i/a w/W/s/p` - Text objects are powerful when combined with `w`ord, `W`ORD, `s`entence, `p`aragraph
- Simple tip to use `a` when `d`eleting and `i` when `c`hanging

#### Tip 54 - Mark Your Place and Snap Back to It

- `m{a-zA-Z}` - mark a place in the file (capital are global)
- ``{mark}` - go to the marked place
- `double-backticks` - go to last jump in file
- ``.` - go to last change location

#### Tip 55 - Jump Between Matching Parentheses

- `%` - jumps between matching set of brackets
- `S"` - surround the selection with double quotes (surround.vim)

### Chapter 09 - Navigate Between Files with Jumps (8 pages)

#### Tip 56 - Traverse the Jump List

- `<C-o>` - goes backwards through the jump list
- `<C-i>` - goes forwards through the jump list
- `motions` - move around _within a file_
- `jumps` - move around _between files_
- `:jumps` - list the jump list
- `(, )` - jump to previous/next sentence
- `{, }` - jump to previous/next paragraph

#### Tip 57 - Traverse the Change List

- `g; and g,` - go to previous/next change
- `backtick.` - go to last change
- `gi` - go to last insertion and enter insert mode

#### Tip 58 - Jump to the Filename Under the Cursor

- `gf` - navigates to filename under cursor (`go to file`)
- `bundler.vim` - might be a useful plugin to incorporate to enhance gf power
- `<C-]>` - jump to method definition from invocation (may need some initial config to work)

#### Tip 59 - Snap Between Files Using Global Marks

- `m[Capital]` - sets a global mark
- `backtick[Capital]` - navigates to a global mark
- Handy trick, set `mV`, to init.vim for easy jumping to the vimrc file
- Handy trick, set `mS`, to .zshrc for easy jumping to the zshrc file
- Before going on a jump journey, set the global mark `mM` and return with `backtickM` to get back to the mark

### Chapter 10 - Copy and Paste (18 pages)

#### Tip 60 - Delete, Yank, and Put with Vim's Unnamed Register

- `xp` - transpose the next to characters using the unnamed register -- useful!!!
- `ddp` - transpose the next two lines
- `yyp` - line-wise copy and paste

#### Tip 61 - Grok Vim's Registers

- `"{register}[delete | yank | put]` - copy to a named `register`
- `_` - the `black hole` register (e.g. `_d{motion}` nothing escapes a black hole)
- `""` - the `unnamed register`
- `x`, `s`, `d{motion}`, `c{motion}`, `y{motion}` - all write to register
- `:reg` - inspect registers
- lowercase registers `override` any existing text; uppercase registers `append` to existing content
- `"+` - named register that reference the system clipboard
- Not sure how, but I also have normal `CMD+C` and `CMD+V` functional

#### Tip 62 - Replace a Visual Selection with a Register

- `v{motion}p` - replace visual selection with unnamed register content
- _Think of it this way: the visual selection in the document swaps places with the text in the register. Is it a feature? Is it a bug? You decide._

#### Tip 63 - Paste from a Register

- `p/P` - inserts register text `after` and `before` cursor position
- `<ctrl-r>{register}` - inserts register text while in INSERT or COMMAND mode
- `gp/gP` - alter the position of the cursor after the put operation. This is useful for pasting a block of text into a document.

#### Tip 64 - Interact with the System Clipboard

- Not relevant since I don't use nvim in terminal often

### Chapter 11 - Macros (21 pages)

#### Tip 65 - Record and Execute a Macro

- `:reg{register}` - inspects the content of the given register; useful to examine macros
- `@{register}` - executes the contents of the specified register
- `@@` - executes the contents of the last executed macro
- macros can be executed `serial` or in `parallel`

#### Tip 66 - Normalize, Strike, Abort

- _The golden rule is this: when recording a macro, ensure that every command is repeatable._
- `w, b, e, ge` - are more reliable movements when recording a macro

#### Tip 67 - Play Back with a Count

- `n@{register}` - repeats a macron times or until failure

#### Tip 68 - Repeat a Change on Contiguous Lines

- `:'<,'>normal @{register}` - repeat macro on each of highlighted lines

#### Tip 69 - Append Commands to a Macro

- use `q{A-Z}` - to append to an existing macro

#### Tip 70 - Act Upon a Collection of Files

- not useful since I don't use vim to manipulate across multiple files

#### Tip 71 - Evaluate an Iterator to Number Items in a List

- super niche. not going to bother with this tip until other tips are muscle memory
- makes use of `expression register, "=`

#### Tip 72 - Edit the Contents of a Macro

- skipping this as well, since I should first master basic macro syntax

## Internet Article Notes

### vscode-neovim github

kk
