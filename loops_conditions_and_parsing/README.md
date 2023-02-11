#  Shell, loops, conditions and parsing

In this directory, i learnt about the advantage of using `#!/usr/bin/env bash` over `#!/bin/bash`. I also learnt how to use the `while`, `until` and `for` loops.
How to use `if`, `else`, `elif` and `case` condition statements and how to use the `cut` command

## Tasks :page_with_curl:

**Task-0**: The [1-for_best_school](./1-for_best_school) file contains a Bash script that displays `Best School` 10 times using `for` loop.

**Task-1**: The [2-while_best_school](./2-while_best_school) file contains a Bash script that displays Best School 10 times using `while` loop.

**Task-2**: The [3-until_best_school](./3-until_best_school) file contains a Bash script that displays Best School 10 times using `until` loop.

**Task-3**: The [4-if_9_say_hi](./4-if_9_say_hi) contains a Bash script that displays `Best School` 10 times, but for the 9th iteration, displays `Best School` and then `Hi` on a new line using `while` loop.

**Task-4**: The [5-4_bad_luck_8_is_your_chance](./5-4_bad_luck_8_is_your_chance) contain a Bash script that loops from 1 to 10 and:
- displays `bad luck` for the 4th loop iteration
- displays `good luck` for the 8th loop iteration
- displays `Best School` for the other iterations

**Task-5**: The [6-superstitious_numbers](./6-superstitious_numbers) file contains a Bash script that displays numbers from 1 to 20 and:
- displays `4` and then `bad luck from China` for the 4th loop iteration
- displays `9` and then `bad luck from Japan` for the 9th loop iteration
- displays `17` and then `bad luck from Italy` for the 17th loop iteration

**Task-6**: The [7-clock](./7-clock) file contains a Bash script that displays the time for 12 hours and 59 minutes:
- display hours from 0 to 12
- display minutes from 1 to 59

**Task-7**: The [8-for_ls](./8-for_ls) file contains a Bash script that displays the content of the current directory in a list format.

**Task-8**: The [8-concat_edges.py](./8-concat_edges.py) file contains a Bash script that gives you information about the school file.
Requirements:
 - You must use `if` and, `else` (`case` is forbidden)
 -Your Bash script should check if the file exists and print:
   -if the file exists: `school file exists`
   -if the file does not exist: `school file does not exist`
  -If the file exists, print:
   -if the file is empty: `school file is empty`
   -if the file is not empty: `school file is not empty`
   -if the file is a regular file: `school is a regular file`
   -if the file is not a regular file: (nothing)

**Task-9**: The [9-easter_egg.py](./9-easter_egg.py) file contains a script that prints “The Zen of Python”, by TimPeters, followed by a new line.

**Task-10**: The [100-write.py](./100-write.py) file contains a Python script that prints exactly `and that piece of art is useful - Dora Korpar, 2015-10-19`, followed by a new line without using the `print()` function.

**Task-11**: The [101-compile](./101-compile) file contains a script that compiles a Python script file.

**Task-12**: The [102-magic_calculation.py](./102-magic_calculation.py) is a script that contains the Python function `def magic_calculation(a, b)`: that does exactly the same as the following Python bytecode:

```sh
	 3          0 LOAD_CONST               1 (98)
              	    3 LOAD_FAST                0 (a)
                    6 LOAD_FAST                1 (b)
                    9 BINARY_POWER
                   10 BINARY_ADD
                   11 RETURN_VALUE
```
