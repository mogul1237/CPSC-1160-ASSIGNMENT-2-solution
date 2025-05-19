# CPSC-1160-ASSIGNMENT-2-solution

Download Here: [CPSC 1160: ASSIGNMENT 2 solution](https://jarviscodinghub.com/assignment/cpsc-1160-assignment-2-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Exercise 1 [20 marks]
Write a program that estimates the probability P that if N people are in a room, at least two people in that room will have the same birthday.
By the same birthday, we don’t mean the same date of birth, we mean the same day and the same month in a year that is not a leap year.
The ‘birthday paradox’ is described as follows: for relatively small values of N, there is a surprising high probability that two people in the same room happen to share the same birthday.
Write a program to implement the ‘birthday paradox’. Your program will use simulation to approximate the value of P for the given value of N as follows:
• Your program should read in N, which is the number of people in the room, and it should read T, which is the number of trials. • Run a trial or experiment (of determining whether at least 2 people in the room have the same birthday) T times and then count the number of those trials C where at least two people in the room do have indeed the same birthday. • Output the value N and the value of C/T which will be an estimate for P. • Repeat for several values of N printing their corresponding estimated value P, in fact, choose and print a reasonable range of values for N with their estimated probabilities P. (To clarify what a range means here is that you could read a starting value of N and then compute the next few (10?) values for a range from N to N + 10?)
Note: the larger the value you use for T, the more accurate C/T will be for the probability P. Make T, which is the number of trials, to be at least 3000.
Of interest in the birthday paradox is finding the smallest value of N such that P is 0.5. That is, for such a value of N there is a 50/50 chance that two people have the same birthday in the room. Before you run the experiment, guess what the value of N should be (just for fun – you don’t need to include your original guess). Run your program and see. The value of N that you are looking for should be less than 30. (Thus the values for the range of N should be less than 30 and greater than some another value.)
Submissions
Make sure that your code is neat and is well commented [5 marks]
Check that all of your programs work the way they are intended to work by running them with different inputs
Before the submission date test input will be giving, your program should run on those examples and any other examples.
Submit to D2L a zip/archive file containing the .cpp you have written
If you do not zip your file or if you submit the .class files, you will receive ZERO for this lab (https://www.wikihow.com/Zip-Files-Together)
