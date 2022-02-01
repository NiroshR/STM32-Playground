# Playground

## Formatting
We will use UNIX formatting which also means the carriage-return character we
will use will not be the DOS format.

To make sure we arent' introducing any `^M` characters for newlines, run the 
following command in a UNIX terminal (ex. WSL):

```bash
dos2unix <filename>

# Alternatively open file in Vim
:e ++ff=dos         # tells Vim to read file forcing DOS format
:set ff=unix        # read again forcing UNIX format
:wq                 # save and exit
```