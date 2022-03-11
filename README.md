# Navigating around with VIM

:syntax on → highlight the text  <br>
:set number → activate line numbering <br>
j → goes down one line <br>
k → goes up one line <br>
l → move to the right one character <br>
h → move to the left one character <br>
w → moves forward word by word <br>
b → moves to the previously word <br>
0 → goes to the beginning of the line <br>
$ → goes to the end of the line <br>
^ → beginning of the line after the white space <br>
gg → goes to the first line <br>
G → goes to the end of the file <br>
shift + [ → goes up sentence by sentence <br>
Shift + ] → goes down sentence by sentence <br>
33gg → goes to line 33 (change the line number as you wish) <br>
vim +33 file.js → opens vim and jumps right into the line 33 <br>

# Insert Mode

i → enter insert mode (starts where the cursor is) <br>
esc → go back to command mode <br>
u → undo <br>
ctrl + r → redo <br>
a → append, enter insert mode starting after the cursor <br>
o → insert text after the current line <br>
O → insert text before the current line <br>
shift + a → append text to the end of the line <br>
:q! → exit file without saving <br>
:qw! → exit saving file <br>

# Deleting, Cut and Paste

dw → delete a word <br>
dd → delete a entire line <br>
4dd → delete 4 lines <br>
dG → delete the entire file <br>
y, p → copy, paste <br>
dd, p → paste the line that was deleted (cut actually) <br>
db → delete word backwards <br>
d0 → delete from the cursor to the beginning of the line <br>
d$ → delete from the cursor to the end to the line <br>

# Saving and Quitting

:q! → close file abandoning changes <br>
:wq! → save and close the file <br>
:w → save and continue in vim <br>
:q → just quit vim <br>

# Search and Replace

/final → finds the word "final" in the file, press n to go to the nex,, N to the previous occurrence  <br>
:%s/UUID/Integer/gc → search and replace the word UUID to Integer, globally with confirming  <br>
:%s/UUID/Integer/g → same as the least but without confirming (be careful) <br>
:noh → clear the highlighted search <br>

# Creating Files

Vim config.js → Creates a file called config.js <br>

# Configure .vimrc

vim ~/.vimrc → to create a vim configuration file, inside it write your preferences: <br>
:set number <br>
:syntax on <br>

The ultimate Vim configuration guide on GitHub: <br>
https://github.com/amix/vimrc <br>

