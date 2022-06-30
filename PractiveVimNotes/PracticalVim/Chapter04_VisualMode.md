# Chapter 04 - Visual Mode (14 pages)

## Tip 20 - Grok Visual Mode

- `c` - In visual mode, deletes the selected text and changes into Insert mode
  - Useful for wrapping changed selected text with quotes or brackets!!!

## Tip 21 - Define a Visual Selection

- `v` - *character-wise Visual mode*
- `V` - *line-wise Visual mode*
- `<C-v>` - *block-wise Visual mode*
- `gv` - reselect the last visual selection
- `o` go to end of highlighted text (ping-pong cursor)
  - `o` is handy for redefining the begin/end points of the selection

## Tip 22 - Repeats Line-Wise Visual Commands

- `.` - repeats the edit on the previously selected text when using visual-line mode
- `vit` - visual select in-between tags

## Tip 23 - Prefer Operators to Visual Commands Where Possible

- `gU` - uppercase the following motion
- *As a eneral rule, we should prefer operator commands over this Visual mode equivalents when working through a repetitive set of changes*

## Tip 24 - Edit Tabular Data with Visual-Block Mode

- Fancy visual block-mode kung-fu

## Tip 25 - Change Columns of Text

- Not that block mode works like you think it should but you won't see the multiple cursor effect until you re-enter normal mode

## Tip 26 - Append After a Ragged Visual Block

- Visual block-mode is actually quite useful. Similar to vscode native multi-cursor functionality
- Note `i` and `a` while in visual or operator-pending mode represent the `inside` and `around` part of a `text object`

```javascript
In the beginning, there was ed. ed begat ex, and ex begat vi, and vi begat Vim.
- The Old Testament of Unix
```

