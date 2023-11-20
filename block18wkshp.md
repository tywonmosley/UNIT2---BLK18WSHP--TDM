# Unit Test - Workshop 18

## Prompts:

For each prompt below: 

- Read the prompt.
- Identify the expectations.
- Write specifications in pseudocode/plain English for all the tests that would be useful for that prompt.
   - Try to take any "edge cases," or unexpected circumstances, into account, and write test specs for them.
    - Try not to write extraneous tests!

## Overview

In this workshop, you are going to write instructions for tests, often known as test specifications, or test specs, for a series of prompts. 

## Unit Test 1 -- Function call multiplication:

1. A function called "multiplication" that returns the product of the two input numbers.

### Expectations

- The function will takes the argument
- The function will return a number with a product of the numbers provided
- The function will return a undefined or error when non-numberic charaters are provided
- The function will return zero when the number zero is provided with other number
- The function will provide a number and not a string

### Test Specs (function call multiplication)

- Expect [multiply(3,5)] to be number
- Expect [multiply(3,5)] to be equal to 15
- Expect [multiply(a,5)] to be result an error
- Expect [multiply(3,b] to be result an error
- Expect [multiply(a,b)] to be result an error
- Expect [multiply(0,5)] to be result of zero

## Unit Test 2 -- Function concatOdds():

2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

### Expectations

- The function will take the arguments
- The function will generate new array when two arrays with odd numbers are provided within both arrays
- The function will gererate will indentify odd numbers 
- The function will generate no array when no odd numbers are provided
- The function will provided a undefine when non numberic charaters are provided

### Test Specs  (function call "concatOdds")

- Expect [concatOdds([3,3,2],[1,2,1])] to be to numbers
- Expect [concatOdds([3,3,2],[1,2,1])] to be [1,3]
- Expect [concatOdds([2,4,2],[6,2,8])] to be []
- Expect [concatOdds([a,b,c],[c,e,f])] to be []


## Functional Test -- Shopping Cart:
1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.


### Expectations

- 
-
-
-

### Test Specs

- Expect [] to be []
- Expect [] to be []
- Expect [] to be []
- Expect [] to be []
- Expect [] to be []