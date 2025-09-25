# Intel8085-Get-Bit-Parity
(can run in sim8085) 

Write an Intel 8085 assembly language program that counts the number of 1s in a binary number stored in the accumulator. Use the algorithm below. Hand assemble (produce hexadecimal code using code tables) the code for the first 10 lines of the program.
Tally = 0;

For i = 1 to 8

Shift accumulator once to the right

If carry = 1 then increment ONES

Next i
