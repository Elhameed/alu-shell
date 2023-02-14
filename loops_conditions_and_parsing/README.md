#  Shell, loops, conditions and parsing

In this directory, I learnt about the advantage of using `#!/usr/bin/env bash` over `#!/bin/bash`. I also learnt how to use the `while`, `until` and `for` loops.
How to use `if`, `else`, `elif` and `case` condition statements and how to use the `cut` command

## Tasks :page_with_curl:

**Task-0**: The [1-for_best_school](./1-for_best_school) file contains a Bash script that displays `Best School` 10 times using `for` loop.

**Task-1**: The [2-while_best_school](./2-while_best_school) file contains a Bash script that displays `Best School` 10 times using `while` loop.

**Task-2**: The [3-until_best_school](./3-until_best_school) file contains a Bash script that displays `Best School` 10 times using `until` loop.

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

**Task-8**: The [9-to_file_or_not_to_file](./9-to_file_or_not_to_file) file contains a Bash script that gives you information about the school file.
- Requirements:
  - You must use `if` and, `else` (`case` is forbidden)
  - Your Bash script should check if the file exists and print:
    - if the file exists: `school file exists`
    - if the file does not exist: `school file does not exist`
  - If the file exists, print:
    - if the file is empty: `school file is empty`
    - if the file is not empty: `school file is not empty`
    - if the file is a regular file: `school is a regular file`
    - if the file is not a regular file: (nothing)

**Task-9**: The [10-fizzbuzz](./10-fizzbuzz) file contains a Bash script that displays numbers from 1 to 100.
- Requirements:
  - Displays `FizzBuzz` when the number is a multiple of `3` and `5`
  - Displays `Fizz` when the number is multiple of `3`
  - Displays `Buzz` when the number is a multiple of `5`
  - Otherwise, displays the number
  - In a list format

**Task-10**: The [11-read_and_cut](./11-read_and_cut) file contains a Bash script that displays the content of the file `/etc/passwd`. The script should only display username, user id and Home directory path for the user.

**Task-11**: The [12-tell_the_story_of_passwd](./12-tell_the_story_of_passwd) file contains a Bash script that displays the content of the file `/etc/passwd`, using the `while loop` + IFS.

**Task-12**: The [13-lets_parse_apache_logs](./13-lets_parse_apache_logs) is a Bash script that displays the visitor IP along with the HTTP status code from the Apache log file.

**Task-13**: The [14-dig_the-data](./14-dig_the-data) is a Bash script that groups visitors by IP and HTTP status code, and displays this data.
