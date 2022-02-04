# MIPS-Morse----ASCII
MIPS Program to convert morse code to ASCII &amp; vice versa


The algorithm I implemented to convert Morse Code to ASCII was relatively simple.
First, I receive the user input and save it. I then break down the user input into individual
characters, and compare these characters with the values for both dashes and dots,
0x2d and 0x2e respectively. When they match either of these characters, 01 for dash
and 10 for dots are added to a variable. This is looped until neither a dash nor dot is
found, in which case 11 is ended to signify the end of these variables, and 00 is added
repeatedly to the end to create the correct length for this variable. This variable is then
compared with the first 4 bytes of each value in the dictionary until a match is found.
When a match is found, the last 2 bytes of the value in the dictionary are printed, which
shows the ASCII value.
