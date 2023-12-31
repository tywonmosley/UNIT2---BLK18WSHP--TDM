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

- The function will take the argument
- The function will return a number with a product of the numbers provided
- The function will return an undefined or error when non-numeric characters are provided
- The function will return zero when the number zero is provided with other numbers
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
- The function will generate a new array when two arrays with odd numbers are provided within both arrays
- The function will generate will identify odd numbers 
- The function will generate no array when no odd numbers are provided
- The function will provide an undefine when non-numeric characters are provided

### Test Specs  (function call "concatOdds")

- Expect [concatOdds([3,3,2],[1,2,1])] to be to numbers
- Expect [concatOdds([3,3,2],[1,2,1])] to be [1,3]
- Expect [concatOdds([2,4,2],[6,2,8])] to be []
- Expect [concatOdds([a,b,c],[c,e,f])] to be []


## Functional Test -- Shopping Cart:
1. A shopping cart checkout feature that allows a user to check out as a guest (without an account) or as a logged-in user. They should be allowed to do either but should be asked if they want to create an account or log in if they check out as a guest.


### Expectations
- When user move forward with purchase an option is provided to moved forward with or without account
- If user want to use account or create one user can create an account or login and items remains in cart during transaction
- When user is able provide information like email, address, name and payment information and remain stored until transaction is completed


### Test Specs

Funtional test specifications should take the form of: (GIVEN) some context. (WHEN) some action is carried out. (THEN) a particular set of observable consequences should obtain

GIVEN I am a new user visiting the site as a guest purchase items

WHEN I have put items to cart THAN I should see the cart with items choose

WHEN I am the at the cart about to move for to finalize my purchase THAN I should see a button that will move me forward.

WHEN I hit the button to finalize my purchase THAN it should provide an option to move forward as a guest or create a new acount or log into a existing account

WHEN I choose to create or log into account THAN pop-up tab or window should appear

WHEN I am complete login or creating an account THAN I should be able to refresh with all the items stored for purchase with the account reflecting logged in

WHEN I confirmed all the information as for email, address, name and payment information THAN I should be able to hit the button to finalize the purchase


