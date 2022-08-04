# Chapter 11 - Macros (21 pages)

## Tip 65 - Record and Execute a Macro

- `:reg{register}` - inspects the content of the given register; useful to examine macros
- `@{register}` - executes the contents of the specified register
- `@@` - executes the contents of the last executed macro
- macros can be executed `serial` or in `parallel`

## Tip 66 - Normalze, Strike, Abort

- *The golden rule is this: when recording a macro, ensure that every command is repetable.*
- `w, b, e, ge` - are more reliable movements when recording a macro

## Tip 67 - Play Back with a Count

- `n@{register}` - repeats a macron times or until failure

## Tip 68 - Repeat a Change on Contiguous Lines

- `:'<,'>normal @{register}` - repeat macro on each of highlighted lines

## Tip 69 - Append Commands to a Macro

- use `q{A-Z}` - to append to an existing macro

## Tip 70 - Act Upon a Collection of Files

- not useful since I don't use vim to manipulate across multiple files

## Tip 71 - Evaluate an Iterator to Number Items in a List

- super niche. not going to bother with this tip until other tips are muscle memory
- makes use of `expression register, "=`

## Tip 72 - Edit the Contents of a Macro

- skipping this as well, since I should first master basic macro syntax
