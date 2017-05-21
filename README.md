# 516FinalProject
This random number generator uses the basic Linear Congruential Generator

The formula is: r_n+1 = (a*r_n + c) % m

***

Where r_n is the random number generated

**r_0** is the "seed". In our program it is decided by the user.

**a** is constant multipler it can be anything

**c** is also another constant known as an incrementer 

**m** is the modulus which is also another constant

These numbers can be anything as long as m > a, m > c, m > r_0

***

Variables in our program:

**colcnt** (Column Counter) Used to output the numbers in 10x10 columns properly. When it reaches the value of 10 it outputs a newline (\n) then resets to 0

**cmp** (Complete) A global counter once it reaches 100 the program stops since we only need to output 100 values.
