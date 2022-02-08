# Fix-my-code-0
In this project I will be fixing code without recoding everything.

## Tasks
* **0. FizzBuzz**
Python implementing the FizzBuzz challenge.

**Requirement**: The code should print `FizzBuzz` When a number is both a multiple of 3 and 5 not `fizz`

### Original code
[0-fizzbuzz.py](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/0-fizzbuzz.py)

### My fixed code:
[0-fizzbuzz.py](./0-fizzbuzz.py)

### Runnning the code
$ ./0-fizzbuzz.py 89

## Solution
I swapped the order of the `if/elif` statements. Started by checking if `number` was a multiple of `3` and `5`.

* **1. Print square**
Javascript code implementing the printing od a square.

**Requirement**: The code should print a square of size 10 when 10 is passed as the size.

### Original code
[1-print_square.js](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/1-print_square.js)

### My fixed code:
[1-print_square.js](./1-print_square.js)

### Runnning the code
$ ./1-print_square.js 10

## Solution
The second argument of `parseint` (`base`) was supposed to be base `10` instead of base `16` in the original code.
