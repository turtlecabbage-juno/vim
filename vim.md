# Vim cheat sheet

## Modes

i - insert mode
v - visual mode
esc - normal mode

## Navigation (Normal mode)

*h - move one left*
*j - move one down*
*k - move one up*
*l - move one right*
w - move to start of next word
W - same but ignores punctuation
e - move to end of next word
E - same but ignores punctuation
b - move to beginning of previous word
ge - move to end of previous word
$ - move to end of line
g_ - same but ignores blank characters
0 - move to beginning of line
^ - same but ignores blank characters
gg - move to top of file
G - move to bottom of file
H - move to top of screen
M - move to middle of screen
L - move to bottom of screen
% - move to matching character (like "(" to ")")

## Text editing (Normal mode)

*x - delete character under cursor*
*dw - delete word*
*cw - delete word and enter insert mode*
*dd - delete entire line*
*D - delete from cursor to end of line*
*d$ - same thing*
*d^ - delete from cursor to start of line*
*p - paste most recently deleted text*
*u - undo*
o - create new line beneath cursor and enter insert mode
O - same but create new line above instead
a - insert character after cursor
A - insert character at end of line
r - replace one character
R - replace characters until esc is pushed

## ":" commands (Normal mode)

*:w - save changes*
*:wq - save changes and exit vim*
*:q - exit vim (No changes made)*
:q! - exit vim and discard changes
:40 - moves to line 40, etc etc
:-40 - moves 40 lines up
:+40 - moves 40 lines down
:/The - moves to the next instance of "The"
:%s/20/40/g - replaces all instances of "20" with "40" (the /g at the end replaces all instances in a line, otherwise it does only the first instance)

## Notes

- You can type a number to repeat an action (ex. 4dd would delete current line and the 3 under. Also makes p paste all 4 lines. 50j would move 50 lines down.)
