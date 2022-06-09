## Chapter 01 - The Vim Way (11 pages)

### Tip 1 - Meet the Dot Command

*The dot command lets us repeat the last change. It is the most powerful and versatile command in Vim.*

- The `dot` command is a micro macro. haha!

### Tip 2 - Don't Repeat Yourself

- Use combined shortcuts like `A` to be more efficient.

### Tip 3 - Take One Step Back, Then Three Forward

- `f{char}` which searches for the given character can be combined with `;` and `.` to be super powerful.

### Tip 4 - Act, Repeat, Reverse

- Handy commands and their reverse:
  - `.`: Repeat the last change. `u` reverses the last change.
  - `;`: Forward line search next char. `,` reverse line search previous char. Equivalent to `F{char}`.
  - `n`: Forward search next char. `N` reverse search previous char.
  - `:s/target/replacement`: Perform forward substitution. Repeat using `&` and undo using `u`.
  - `qx{changes}q`: Perform a macro. `u` reverses the macro.

### Tip 5 - Find and Replace by Hand

- `*` Searches for the next occurrence of the word under the cursor.
- `n` Let's you repeat the previous search. Handy for quick search/edits, repeat.
- `*`, `cw`, `edit`, `*`, `.` Boom!

### Tip 6 - Meet the Dot Formula

- *The goal: One Keystroke to Move, One Keystroke to Execute*

