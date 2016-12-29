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

### Remove blank lines
```
g/^$/d
```

### Add a string to the end of each line with *`foo`*
```
%s/$/foo/g
```

### Replace every comma with new line
```
%s/,/\r/g
```
