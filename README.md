# vi-cheat-sheet
A list of cool features of Vi.

### Replace the beginning of each line with *`foo`*
```
%s!^!foo!
```

### Replace the begging of each selected line with *`foo`*
```
'<,'>s!^!foo!
```

### Remove blank lines
```
g/^$/d
```
