# CSC-122-Wk5
## Collatz conjecture
1) Ask the user for an input

2) Print the Collatz sequence for that number, using -> between each step like I did above.
  2.1) The Collatz Sequence must be aquired via recursion.
3) End once you reach 1 for the first time

4) Ask the user if they want to input another number!

## Well that's just prime
We would like to calculate a list of prime factors for a number.

E.g. 100 = 2 * 2 * 5 * 5


Write a function that accepts an integer argument, and returns a vector containing all of that number's prime factors.

If the number is <= 1, return an empty list.

Remember that 1 is not a prime number.

This lab must be solved using recursion.

Your function should be tested with a variety of assert-based unit tests.

Then answer these TPQs:

How might you solve this using a loop instead of recursion? Would this be easier or harder?
Using recursion often involves breaking a problem up into smaller "subproblems". How did you apply this concept here, and how did you determine what your base case should be?
