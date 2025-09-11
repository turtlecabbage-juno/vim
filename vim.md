## Vim cheat sheet

# Modes

i - insert mode
v - visual mode
esc - normal mode

# Navigation (Normal mode)

h - move one left
j - move one down
k - move one up
l - move one right
w - move to start of next word
e - move to end of next word
b - move to beginning of previous word
$ - move to end of line
^ - move to beginning of line
gg - move to top of file
G - move to bottom of file

# Text editing (Normal mode)

x - delete character under cursor
dw - delete word
dd - delete entire line
d$ - delete from cursor to end of line
d^ - delete from cursor to start of line
p - paste most recently deleted text
u - undo
o - create new line beneath cursor and enter insert mode
O - same but create new line above instead

# ":" commands (Normal mode)

:w - save changes
:wq - save changes and exit vim
:q - exit vim (No changes made)
:q! - exit vim and discard changes
:40 moves to line 40, etc etc
:-40 moves 40 lines up
:+40 moves 40 lines down
:/The moves to the next instance of "The"

# Notes

- You can type a number to repeat an action (ex. 4dd would delete current line and the 3 under. Also makes p paste all 4 lines. 50j would move 50 lines down.)
