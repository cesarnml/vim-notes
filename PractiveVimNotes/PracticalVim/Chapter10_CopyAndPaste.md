# Chapter 10 - Copy and Paste (18 pages)

## Tip 60 - Delete, Yank, and Put with Vim's Unnamed Register

- `xp` - transpose the next to characters using the unamed register -- useful!!!
- `ddp` - transpose the next two lines
- `yyp` - linewise copy and paste

## Tip 61 - Grok Vim's Registers

- `"{register}[delete | yank | put]` - copy to a named `register`
- `_` - the `black hole` register (e.g. `_d{motion}` nothing escapes a black hole)
- `""` - the `unnamed register`
- `x`, `s`, `d{motion}`, `c{motion}`, `y{motion}` - all write to register
- `:reg` - inspect registers
- lowercase registers `override` any existing text; uppercase registers `append` to existing content
- `"+` - named register that reference the system clipboard
- Not sure how, but I also have normal `CMD+C` and `CMD+V` functional

## Tip 62 - Replace a Visual Selection with a Register

- `v{motion}p` - replace visual selection with unnamed register content
- *Think of it this way: the visual selection in the document swaps places with the text in the register. Is it a feature? Is it a bug? You decide.*

## Tip 63 - Paste from a Register

- `p/P` - inserts register text `after` and `before` cursor position
- `<ctrl-r>{register}` - inserts register text while in INSERT or COMMAND mode
- `gp/gP` - alter the position of the cursor afte the put operation. This is useful for pasting a block of text into a document.

## Tip 64 - Interact with the System Clipboard

- Not relevant since I don't use nvim in terminal often
