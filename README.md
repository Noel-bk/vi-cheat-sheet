# vi-cheat-sheet
A list of cool features of Vi.

### Replace the beginning of each line with *`foo`*
```
%s!^!foo!
```

### Replace the beginning of each selected line with *`foo`*
```
'<,'>s!^!foo!
```

### Add a string to the end of each line with *`foo`*
```
%s/$/foo/g
```

### Remove blank lines
```
g/^$/d
```

### Replace every comma with *new line*
```
%s/,/\r/g
```

### Delete every new lines
```
%s/\n/
```

### Insert text at beginning of a multi-line selection
> `Ctrl+V` to enter visual block mode.
>
> select the columns of text in the lines you want to comment.
>
> `Shift+I` and type the text you want to insert.
>
> Hit `Esc`.

### Open a new line *below* the current line
`o`

### Open a new line *above* the current line
`O`
