# Chapter 09 - Navigate Between Files with Jumps (8 pages)

## Tip 56 - Traverse the Jump List

- `<C-o>` - goes backwards through the jump list
- `<C-i>` - goes forwards through the jump list
- `motions` - move around *within a file*
- `jumps` - move around *between files*
- `:jumps` - list the jump list
- `(, )` - jump to previous/next sentence
- `{, }` - jump to previous/next paragraph

## Tip 57 - Traverse the Change List

- `g; and g,` - go to previous/next change
- `backtick.` - go to last change
- `gi` - go to last insertion and enter insert mode

## Tip 58 - Jump to the Filename Under the Cursor

- `gf` - navigates to filename under cursor (`go to file`)
- `bundler.vim` - might be a useful plugin to incorporate to enahnce gf power
- `<C-]>` - jump to method definition from invocation (may need some initial config to work)

## Tip 59 - Snap Between Files Using Global Marks

- `m[Capital]` - sets a global mark
- `backtick[Capital]` - navigates to a global mark
- Handy trick, set `mV`, to init.vim for easy jumping to the vimrc file
- Handy trick, set `mS`, to .zshrc for easy jumping to the zshrc file
- Before going on a jump journey, set the global mark `mM` and return with `backtickM` to get back to the mark
