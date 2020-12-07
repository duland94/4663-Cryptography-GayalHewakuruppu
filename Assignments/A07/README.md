## Assignment 7 - Finding Primes
## Author - Gayal Hewakuruppu

### Introduction
A primality test, like the name suggests, is a test to determine if a number is prime or not. It is different from factorization 
because it does not factor the given number.

### Main Categories
Primality tests can be divided under three main catogories.
1) Certification
2) Compositeness
3) Deterministic

### Deterministic
Like the name suggests, deterministic tests will determine if a number is prime or not. The accuracy of these tests are a 100%.
The The AKS primality test, Lucas-Lehmer test and elliptic curve primality proving are two examples of deterministic primality tests.
#### AKS primality test
This deterministic algorithm can identify whether a number is prime or compsite in polynomial time. In addition to being deterministic,
it is also general, polynomial and unconditional at the same time.
#### Lucas-Lehmer test
The main goal of this test is to determine if a Mersenne Number is prime.
#### elliptic curve primality proving
This is the fastest primality test available. It incorporates the theory of elliptical curves.

### Compositeness
This type of primality tests incorparates proof by contradiction.This test finds a prime by proving that it
is in fact not a prime. In other words, it checks for compositeness. The following are examples of such compositeness 
primality tests.
#### Fermat primality test
This is the most simple of them all. 
#### Rabin-Miller test
#### Solovay–Strassen test

### Certification
This type of of primality tests results in a certificate of primality. In that case it is not necessary to run time consuming 
algorithms again. Examples are as follows.
#### Shor/Pocklington test

