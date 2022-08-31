
# Computer Science I 
## Lab 2.0 Worksheet

Name(s) and Login(s):

Karla khg003
Jade jaderomero

1. Dennis Ritchie, the creator of the C programming language,
was born on September 9th, 1941.  If he were still alive,
how old would he be today?  Find out by running the `birthday`
program on the appropriate inputs and enter your solution here.

80 years 5 weeks 5 days 




2. Bjarne Stroustrup, the creator of the C++ programming
language, the object-oriented extension of C, was born on
December 30th, 1950.  How old is he today?

71 years 34 weeks 5 days


3. Software testing often involves testing code with known
"bad" input in an attempt to break it (sometimes this is
referred to as *fuzzing*).  Try breaking the `birthday_cli`
program by giving it "bad" input and observe the consequences.
Give at least two examples of potentially bad input and the
results you observe.

enter name: K arla
enter birth month: 01
enter birthday: 30th

the result would be an error or the breakage of the code because of how specific it is.



4. Complete all the size and range entries below.

* `char`
  size: 1 bytes
  range: -128 to 127
* `short int`
  size: 2 bytes
  range:-32768 to 32767
* `int`
  size: 4 bytes 
  range: -2147483647 to 2147483647
* `long int`
  size: 8 bytes
  range:-9223372036854775808 to 9223372036854775807
* `float`
  size: 4 bytes 
  range: 7 digits of accuracy
* `double`
  size: 8 bytes 
  range: 15 digits of accuracy


5. Use your working currency conversion to determine
the exchange amounts for the following inputs:

  a) $250.25 = 
  fee: 25.03
  316.77 Pounds
  1.96 Yen 
  
 
  b) $1,000.52 = fee: 100.05
                 1266.48 pounds
                 7.84 Yen

  c) $968,410.12 = 
                     fee: 96,841.01
                     1,225,835.59 pounds
                     7,586.45 Yen 



6. Suppose that you had used only `int` types
in your conversion program.  Would you be able
to use it to convert the US national debt
(which as of 2020 was \$26,009,754,625,487)?
Why or why not?

No because there would be no decimal places or compute accuratly. 


7. Mixed types

a) Run the `area` program with 3 and 4 as inputs.  
What value do you get?  Is this result correct?
6 yes 


b) Execute the program again with inputs 3 and 5.
Does the program give correct results?  Why not?
7.5 yes 

c) Fix the program by editing the `area.c` source
code so that the program produces correct results.
