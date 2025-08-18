# JavaScript Problem Solving Collection

A collection of fundamental JavaScript problem-solving functions covering various programming concepts and algorithms.

## Overview

This repository contains 10 JavaScript functions that solve common programming problems. Each function demonstrates different programming concepts including string manipulation, array operations, mathematical calculations, and control flow.

## Problems and Solutions

### 1. Reverse a String
**Function:** `reverseString(str)`
- **Purpose:** Reverses the characters in a given string
- **Method:** Splits string into array, reverses it, then joins back
- **Example:** 
  ```javascript
  reverseString("hello") // Returns: "olleh"
  ```

### 2. Count Vowels in a String
**Function:** `countVowels(str)`
- **Purpose:** Counts the number of vowels (a, e, i, o, u) in a string
- **Method:** Iterates through each character and checks against vowel set
- **Example:**
  ```javascript
  countVowels("hello world") // Returns: 3
  ```

### 3. Check for Palindrome
**Function:** `isPalindrome(str)`
- **Purpose:** Determines if a string reads the same forwards and backwards
- **Method:** Compares original string with its reverse
- **Example:**
  ```javascript
  isPalindrome("racecar") // Returns: true
  isPalindrome("hello") // Returns: false
  ```

### 4. Find the Maximum Number
**Function:** `findMax(arr)`
- **Purpose:** Finds the largest number in an array
- **Method:** Iterates through array comparing each element
- **Example:**
  ```javascript
  findMax([1, 5, 3, 9, 2]) // Returns: 9
  ```

### 5. Remove Duplicates from an Array
**Function:** `removeDuplicates(arr)`
- **Purpose:** Creates a new array with unique elements only
- **Method:** Builds new array by checking if element already exists
- **Example:**
  ```javascript
  removeDuplicates([1, 2, 2, 3, 4, 4, 5]) // Returns: [1, 2, 3, 4, 5]
  ```

### 6. Sum of All Numbers in an Array
**Function:** `sumArray(arr)`
- **Purpose:** Calculates the total sum of all numbers in an array
- **Method:** Iterates through array accumulating sum
- **Example:**
  ```javascript
  sumArray([1, 2, 3, 4, 5]) // Returns: 15
  ```

### 7. Find Even Numbers in an Array
**Function:** `findEvens(arr)`
- **Purpose:** Filters and returns only even numbers from an array
- **Method:** Uses modulo operator to check divisibility by 2
- **Example:**
  ```javascript
  findEvens([1, 2, 3, 4, 5, 6]) // Returns: [2, 4, 6]
  ```

### 8. Capitalize First Letter of Each Word
**Function:** `capitalizeWords(str)`
- **Purpose:** Converts the first letter of each word to uppercase
- **Method:** Splits string into words, capitalizes first letter of each
- **Example:**
  ```javascript
  capitalizeWords("hello world") // Returns: "Hello World"
  ```

### 9. Find the Factorial of a Number
**Function:** `factorial(n)`
- **Purpose:** Calculates the factorial of a given number
- **Method:** Iteratively multiplies numbers from 1 to n
- **Example:**
  ```javascript
  factorial(5) // Returns: 120 (5 × 4 × 3 × 2 × 1)
  ```

### 10. PingPong Challenge
**Function:** `pingPong()`
- **Purpose:** Prints numbers 1-20 with special rules (similar to FizzBuzz)
- **Rules:**
  - Numbers divisible by both 3 and 5: "PingPong"
  - Numbers divisible by 3: "Ping"
  - Numbers divisible by 5: "Pong"
  - All other numbers: the number itself
- **Example Output:**
  ```
  1, 2, Ping, 4, Pong, Ping, 7, 8, Ping, Pong, 11, Ping, 13, 14, PingPong, ...
  ```

## How to Use

1. Clone or download this repository
2. Open the `problems.js` file in your JavaScript environment
3. Call any function with appropriate parameters
4. For the `pingPong()` function, simply call it to see the output in console

## Concepts Demonstrated

- **String Manipulation:** Reversing, character checking, word processing
- **Array Operations:** Filtering, mapping, reducing, finding elements
- **Loops and Iteration:** For loops, for...of loops
- **Conditional Logic:** If-else statements, modulo operations
- **Mathematical Operations:** Factorial calculation, sum accumulation
- **Problem Solving Patterns:** Search, filter, transform, validate

## Files in Repository

- `problems.js` - Contains all 10 problem-solving functions
- `README.md` - This documentation file

## Author

Created as part of JavaScript problem-solving practice and algorithm implementation exercises.
