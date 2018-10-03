# Primes-on-Interval
Primes on Interval
描述
You've decided to carry out a survey in the theory of prime numbers. Let us remind you that a prime number is a positive integer that has exactly two distinct positive integer divisors.

Consider positive integers a, a + 1, ..., b (a ≤ b). You want to find the minimum integer l (1 ≤ l ≤ b - a + 1) such that for any integerx (a ≤ x ≤ b - l + 1) among l integers x, x + 1, ..., x + l - 1 there are at least k prime numbers.

Find and print the required minimum l. If no value l meets the described limitations, print -1.

输入
A single line contains three space-separated integers a, b, k (1 ≤ a, b, k ≤ 106; a ≤ b).
输出
In a single line print a single integer — the required minimum l. If there's no solution, print -1.
样例输入
2 4 2
6 13 1
1 4 3
样例输出
3
4
-1
