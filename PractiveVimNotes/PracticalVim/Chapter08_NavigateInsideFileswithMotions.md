# Chapter 08 - Navigate Inside Files with Motions (22 pages)

## Tip 47 - Keep Your Fingers on the Home Row

- Just a reminder to use `h (left), j (down), k (up), l (right)` for movement in place of the arrow keys

## Tip 48 - distinguish Betwen Real Lines and Display Lines

- `gj and gk` - move down/up display line wise
- `^` - move to first nonblank character of a display line
- Basically prefix the real line movement keys with `g` to get the analoues display line movemen

## Tip 49 - Move Word-Wise

- `w` - move forward to start of next word
- `b` - move backward to start of current/previous word
- `e` - move forward to end of current/next word
- `ge` - move backward to end of previous word
- `W, B, E, gE` - WORD movements

## Tip 50 - Find by Character

- `f{char}` - move by character in current line, also `F, t, T`

## Tip 51 - Search to Navigate

- `/{pattern}` - search forward for pattern, `?{pattern}` - search backward for pattern
- Consider setting `hlsearch` and `incsearch` settings; relates keys `n` and `N` o hop
- Using the `d{motion}` in combination with `/{pattern}` search is a powerful combination

## Tip 52 - Trace your Selection with Precision Text Objects

- `t` - Text Object to reference HTML tags
- `i` - Inside text object
- `a` - All text object
- `b` - parentheses delimiter
- `B` - curly brackets delimter
- Set of possible delimiters include: `), }, ], >, ', ", backtick, t, b, B`

## Tip 53 - Delete Around, or Change Inside

## Tip 54 - Mark Your Place and Snap Back to It
