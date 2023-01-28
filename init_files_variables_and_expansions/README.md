#  Shell, init files, variables and expansions 

In this project, I learnt shell initialization files, expansions and variables. A few things I learnt include:
- The purpose and contents of the shell initialization files `/etc/profile` and `/etc/profile.d`
- The purpose and contents of the `~/.bashrc` file
- Differences between local and global variables and how to create, update and delete them
- Roles of reserved variables `HOME`, `PATH`, `PS1` and how to perform arithmetic operations in the shell
- How to create, list, and temporarily disable aliases in the shell
- Differences between single and double quotes and how to use command substitution with `$()` and backticks
- How to execute commands from a file in the current shell.

## Tasks :page_with_curl:

**Task 0**: The [0-alias](./0-alias) file contains a script that creates an alias with the name `ls` and variable `rm *`

**Task 1**: The [1-hello_you](./1-hello_you) file contains a script that prints `hello user`, where user is the current Linux user.

**Task 2**: The [2-path](./2-path) file contains a script that Add `/action` to the `PATH`. `/action` should be the last directory the shell looks into when looking for a program.

**Task 3**: The [3-paths](./3-paths) file contains a script that counts the number of directories in the `PATH`

**Task 4**: The [4-global_variables](./4-global_variables) file contains a script that lists environment variables.

**Task 5**: The [5-local_variables](./5-local_variables) file contains a script that lists all local variables and environment variables, and functions.

**Task 6**: The [6-create_local_variable](./6-create_local_variable) file contains a script that creates a new local variable with the name `BEST` and value `School`

**Task 7**: The [7-create_global_variable](./7-create_global_variable) file contains reate a script that creates a new global variable with the name `BEST` and value `School`
 
**Task 8**: The [8-true_knowledge](./8-true_knowledge) file contains a script that prints the result of the addition of 128 with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.

**Task 9**: The [9-divide_and_rule](./9-divide_and_rule) file contains a script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.

   * `POWER` and `DIVIDE` are environment variables

**Task 10**: The [10-love_exponent_breath](./10-love_exponent_breath) file contains a script that displays the result of `BREATH` to the power `LOVE`

   * `BREATH` and `LOVE` are environment variables

**Task 11**: The [11-binary_to_decimal](./11-binary_to_decimal) file contains a script that converts a number from base 2 to base 10.

**Task 12**: The [12-combinations](./12-directory_permissions) file contains a script that prints all possible combinations of two letters, except `oo`
  * Letters are lower cases, from `a` to `z`
  * One combination per line
  * The output should be alpha ordered, starting with `aa`
  * Do not print `oo`
  * Your script file should contain maximum 64 characters

**Task 13**: The [13-print_float](./13-print_float) file contains a script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable `NUM`

**Task 14**: The [14-decimal_to_hexadecimal](./14-decimal_to_hexadecimal) file contains a script that converts a number from base 10 to base 16.

**Task 15**: The [15-rot13](./15-rot13) file contains a script that encodes and decodes text using the rot13 encryption. Assume ASCII.

**Task 16**: The [16-odd](./16-odd) file contains a script that prints every other line from the input, starting with the first line.

**Task 17**: The [17-water_and_stir](./17-water_and_stir) file contains a shell script that adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result.
