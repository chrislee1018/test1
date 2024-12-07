# Project Euler Solutions



## Problem 1
### Problem

### Solution



#### h4 Heading
##### h5 Heading
###### h6 Heading

Alternatively, for H1 and H2, an underline-ish style:




zim zam
















// ////////////////////////////////////////////////////////
// # Title
// Multiples of 3 and 5
//
// # URL
// https://projecteuler.net/problem=1
// http://euler.stephan-brumme.com/1/



[https://projecteuler.net/problem=1](https://projecteuler.net/problem=1)


//
// # Problem
// If we list all the natural numbers below 10 that are multiples of 3 or 5,
// we get 3, 5, 6 and 9. The sum of these multiples is 23.
//
// Find the sum of all the multiples of 3 or 5 below 1000.
//
// # Solved by
// Stephan Brumme
// February 2017
//
// # Algorithm
// We are supposed to find of all multiples of 3 or 5 __below__ the input number,
// therefore we decrement it by one.
//
// In general, the sum of all numbers between 1 and `x` is `sum_{1..x}i=x * (x+1)/2`
// (see https://en.wikipedia.org/wiki/Triangular_number )
//
// There are `floor{x/3}` numbers between 1 and x which are divisible by 3 (assuming `floor{x/3}` is an integer division).
// e.g. the range `1..10` contains `floor{10/3}=3` such numbers (it's 3, 6 and 9). Their sum is `3+6+9=18`.
// This can be written as `3/3 * (3+6+9)` which is the same as `3 * (3/3+6/3+9/3)=3 * (1+2+3)`.
// Those brackets represent ` sum_{1..3}i = sum_{1..10/3}i` (or short: ` sum{10/3}`)
// and thus our overall formula for the sum of all multiples of 3 becomes `3 * sum{x/3}`.
//
// The same formula can be used for 5:
// The sum of all numbers divisible by 5 is `5 * sum{x/5}`
//
// However, there are numbers divisible by 3 __and__ 5, which means they are part of __both__ sums.
// We must not count them twice, that's why we (in addition to the aforementioned sums)
// compute the sum of all numbers divisible by 3*5=15 to correct for this error.
//
// In the end we print ''sumThree + sumFive - sumFifteen''
//
// # Alternative
// Looping through all numbers from 1 and 1000 and checking each of those numbers
// whether they are divisible by 3 or 5 easily solves the problem, too, and produces the result pretty much instantly.
// Even more, the code will be probably a bit shorter.
//
// However, Hackerrank's input numbers are too large for that simple approach (up to `10^9` with `10^5` test cases)
// and will lead to timeouts.













# test1
test1


lcm(a, b) = (a × b) /gcd(a, b)

When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are $$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$


![equation](http://latex.codecogs.com/gif.latex?O_t%3D%5Ctext%20%7B%20Onset%20event%20at%20time%20bin%20%7D%20t)
![equation](http://latex.codecogs.com/gif.latex?s%3D%5Ctext%20%7B%20sensor%20reading%20%7D) 
![equation](http://latex.codecogs.com/gif.latex?P%28s%20%7C%20O_t%20%29%3D%5Ctext%20%7B%20Probability%20of%20a%20sensor%20reading%20value%20when%20sleep%20onset%20is%20observed%20at%20a%20time%20bin%20%7D%20t)




When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

Some display math:
```math
e^{i\pi} + 1 = 0
```
and some inline math, $`a^2 + b^2 = c^2`$.

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$






# Sum of Multiples Formula

The sum of all multiples of a number \( k \) up to a limit \( n \) can be calculated using the formula:

$$
S = k \cdot \frac{p \cdot (p + 1)}{2}

$$

where:

- \( k \) is the number whose multiples are being summed.
- \( n \) is the limit (inclusive).
- \( p = \lfloor n / k \rfloor \) is the number of multiples of \( k \) up to \( n \).

$$

lcm(a, b) = |a * b| / gcd(a, b)

$$






