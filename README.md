# Induction and Modulo Calculator


Mathematical Induction Proof Technique:
1) For all n belongs to Natural Numbers (N) : P(n) is true
- Base case: show that the 1st/initial element of the sequence satisifies property P
- Induction Hypothesis (IH): Assume for each n belongs to N: P(n) is true, as stated above
3) Through this process, prove for each n belongs to N, that the next term P(n+1) is also true
- Choose an arbitrary variable to represent a new n, for example: k
- Now prove P(k+1) holds true
- Show that P(k+1) is true, using the Induction Hypothesis and invoking mathematical induction
4) As P(k) leads to P(k+1) and exists for an arbitrary k, P(n) leads to P(n+1) and must exist/hold for all values of n
5) Therefore, through the Principle of Mathematical Induction and following these steps, QED and the given statement is true.
Use cases to account for: Strong and weak Induction (https://www.math.cmu.edu/~mradclif/teaching/127S19/Notes/Induction.pdf)
  
Modulo:
1) a mod b -> 21 mod 5 (a = 21, b = 5), quotient is 4 and remainder is 1, return/expected output: 1
2) Using the % operator, asks for the user input
3) Calculates the remainder
4) Returns the remainder and output message
