Readme file - Assignment 1

Program 1 - print-truth-table.c
Date : 14 - 08 - 2010

* How to build the program -
  gcc print-truth-table.c truth-table.c postfix.c

  Execute -
  ./a.out

Program 2 - tautology-check.c
Date : 14 - 08 - 2010

* How to build the program -
  gcc tautology-check.c truth-table.c postfix.c

  Execute -
  ./a.out

Program 3 - logical-equivalence.c
Date : 25 - 08 - 2010

* How to build the program -
  gcc logical-equivalence.c truth-table.c postfix.c

  Execute -
  ./a.out

* Algorithms used

 * Convert given Infix expression to Postfix - 
   Shunting Yard Algorithm
 * Evaluate a given Postfix expression for a given set of values
   Postfix Algorithm

* Issue(s) faced
  * Separating the common functions between the three programs into two files

* Testing of code
  1. With arbitrary characters, which should raise error
  2. With mismatched parentheses
  3. With too few tokens
  4. With too few variables given
  5. With different alphabets as variable names
  6. With spaces
  7. With postfix expressions (which should not be accepted)
  8. With correct Infix expressions, but without parentheses
     to test whether precedence of operators is being checked for
  9. With above as command line arguments

* References
 * Convert given Infix expression to Postfix - 
   Source - Wikipedia
   http://en.wikipedia.org/wiki/Shunting-yard_algorithm
   
 * Evaluate a given Postfix expression for a given set of values
   Source - Wikipedia
   http://en.wikipedia.org/wiki/Reverse_Polish_notation
