# Question 2B

Modular multiplicative inverse is an important part of any cryptographic implementation. Write a code that calculates the Modular multiplicative inverse of a number using the Euclidean Algorithm?

**Solution**

A modular multiplicative inverse of an integer $a$ is an integer $x$ such that the product $ax$ is congruent to $1$ with respect to the modulus $m$.
The Euclidean algorithm determines the greatest common divisor (gcd) of two integers, say a and m. If a has a multiplicative inverse modulo m, this gcd must be 1. The last of several equations produced by the algorithm may be solved for this gcd. Then, using a method called "back substitution", an expression connecting the original parameters and this gcd can be obtained.

* [Modular Multiplicative Inverse Calculator using the Eculidean Algorithm implemented in C]()
