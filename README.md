# 516FinalProject
This random number generator uses the basic Linear Congruential Generator

The formula is: r_n+1 = (a*r_n + c) % m

***
##Understanding of variables 
Where **r_n** (user input) is the random number generated

**r_0** is the "seed". In our program it is decided by the user.

**a** is constant multipler it can be anything

**c** is also another constant known as an incrementer 

**m** is the modulus which is also another constant

These numbers can be anything as long as m > a, m > c, m > r_0

***

##Variables in our program:

**colcnt** (Column Counter) Used to output the numbers in 10x10 columns properly. When it reaches the value of 10 it outputs a newline (\n) then resets to 0

**cmp** (Complete) A global counter once it reaches 100 the program stops since we only need to output 100 values.

***

##How to Properly Use the Program

1. Make sure to clear your memory in PEP 9. (Refer to **Setup1.png**) 

2. Then Build the program by Assembling *(Ctrl + Shift + A)*, Loading *(Ctrl + Shift + L)*. **(Refer to Setup2.png)**

3. Then Input a random number that is greater than zero and less than 100 in the input box. **(Refer to Success1.png and Success2.png)**

***

### Errors 

* There are certain limits to the program. So any number that is less than 0 or greater than 100 will result in the same cycle of numbers. Thus resulting in a cycle of numbers that is not random. **(You can refer to the Limits screenshots to see the cycle created by these numbers)**
