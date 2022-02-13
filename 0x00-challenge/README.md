# Fix My Code Challenge
This directory contains my fix on the source code implementations

## 0. Fizz Buzz
### Language
**Python:** implementing the FizzBuzz challenge.

**Requirement**: The code should print `FizzBuzz` When a number is both a multiple of 3 and 5 not `fizz`

**Original code**
[0-fizzbuzz.py](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/0-fizzbuzz.py)

**My fixed code:**
[0-fizzbuzz.py](./0-fizzbuzz.py)

**Runnning the code**
$ ./0-fizzbuzz.py 89

**Fix**
- I swapped the order of the `if/elif` statements. 
- Started by checking if `number` was a multiple of `3` and `5`.

## 1. Print square
### Language
**Javascript:** code implementing the printing od a square.

**Requirement**: The code should print a square of size 10 when 10 is passed as the size.

**Original code**
[1-print_square.js](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/1-print_square.js)

**My fixed code:**
[1-print_square.js](./1-print_square.js)

**Runnning the code**
$ ./1-print_square.js 10

**Fix**
- The second argument of `parseint` (`base`) was supposed to be base `10` instead of base `16` in the original code.

## 2. Sort
### Language
**Ruby:** Implementing the sorting algorithm
**Requirement**: Sort command line arguments(integers) in ascending order

**Original code**
[2-sort.rb](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/2-sort.rb)

**My fixed code:**
[2-sort.rb](./2-sort.rb)

**Fix**
- Change the index passed to the insert method by removing the (-1)

## 3. User password
### Language
**Python** Implements a User class in python
**Requirements**: Pass all tests

**Original code**
[3-user.py](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/3-user.py)

**My fixed code:**
[3-user.py](./3-user.py)

**Fix**
- The call to `self.__password` was missing one underscore
- The hashing of the is_valid_password was hashing to uppercase instead of lower case as in the password setter.i

## 4. Double linked list
### Language
**C** Implementation of a Double linked list in C

**Original code**
[3-user.py](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/tree/master/4-delete_dnodeint)

**My fixed coe**
[delete_dnodeint](./delete_dnodeint)

**Fix**
- Replaced:
`delete_dnodeint_at_index.c` line 46 **(*head)->prev-prev = (*head)->prev;** with => **(*head)->prev-next = (*head)->next;** with:
