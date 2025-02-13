# Uncommon JavaScript Null Handling Bug

This repository demonstrates a subtle bug related to null handling in JavaScript functions. The bug is not necessarily a syntax error or runtime exception but can lead to unexpected behavior or incorrect results if not handled correctly.

The `bug.js` file contains the problematic code. The `bugSolution.js` file offers a potential solution. 

## Bug Description

The function `foo` in `bug.js` attempts to add two numbers. It correctly handles null inputs by returning 0; however, in certain situations, this might not be the most appropriate solution. A more robust solution might involve throwing an error or handling null differently depending on the specific requirements.

## Solution

The `bugSolution.js` file demonstrates a possible improvement to the function. The improved solution throws an error in case any null or undefined values are passed, providing more informative error handling.

## How to Run

1. Clone this repository.
2. Navigate to the repository directory.
3. Run `node bug.js` and `node bugSolution.js` to observe the behavior of the buggy and fixed code respectively.