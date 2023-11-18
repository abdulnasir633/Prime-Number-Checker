Title: Prime Number Checker

Description:
This Python script contains a function, is_prime(n), designed to determine whether a given number n is a prime number. A prime number is defined as a natural number greater than 1 that is divisible only by 1 and itself. The function utilizes a basic primality check algorithm.

Function Details:

is_prime(n): This function takes a single parameter, n, and returns a boolean value indicating whether the number is prime or not. The function checks if the input number is less than 2 (in which case it returns False). Next, it iterates through the numbers from 2 to the square root of n to check for factors. If any factor is found, the function returns False, indicating that the number is not prime. If no factors are found, the function returns True, signifying that the number is prime.
