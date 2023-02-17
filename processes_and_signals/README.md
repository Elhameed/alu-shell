#  Shell, processes and signals

In this directory, I was able to understand the fllowing:
- The concept of a PID and how it is used to identify running processes.
- The concept of a process and how it represents a running program or application in the operating system.
- Learn how to find the PID of a running process.
- Learn how to kill a process using a signal.
- Understand the concept of a signal and how it can be used to communicate with a running process.
- Know the two signals that cannot be ignored, which are SIGKILL (signal 9) and SIGSTOP (signal 19).

## Tasks :page_with_curl:

**Task-0**: The [0-what-is-my-pid](./0-what-is-my-pid) file contains a Bash script that displays its own PID.

**Task-1**: The [1-list_your_processes](./1-list_your_processes) file contains a Bash script that displays a list of currently running processes.

**Task-2**: The [2-show_your_bash_pid](./2-show_your_bash_pid) file contains a Bash script that displays lines containing the `bash` word, thus allowing you to easily get the PID of your Bash process from the previous exercise command.

**Task-3**: The [3-show_your_bash_pid_made_easy](./3-show_your_bash_pid_made_easy) contains a Bash script that displays the PID, along with the process name, of processes whose name contain the word `bash`.

**Task-4**: The [4-to_infinity_and_beyond](./4-to_infinity_and_beyond) contain a Bash script that displays `To infinity and beyond` indefinitely.

**Task-5**: The [5-dont_stop_me_now](./5-dont_stop_me_now) file contains a Bash script that stops [4-to_infinity_and_beyond](./4-to_infinity_and_beyond) process.

**Task-6**: The [6-stop_me_if_you_can](./6-stop_me_if_you_can) file contains a Bash script that stops 4-to_infinity_and_beyond process without using `kill` or `killall`.

**Task-7**: The [7-highlander](./7-highlander) file contains a Bash script that displays:
- `To infinity and beyond` indefinitely
- With a `sleep 2` in between each iteration
- `I am invincible!!!` when receiving a `SIGTERM` signal

**Task-8**: The [8-beheaded_process](./8-beheaded_process) file contains  a Bash script that kills the process `7-highlander`

**Task-9**: The [10-process_and_pid_file](./10-process_and_pid_file) file contains a Bash script that:
- Creates the file `/var/run/myscript.pid` containing its PID
- Displays `To infinity and beyond` indefinitely
- Displays `I hate the kill command` when receiving a SIGTERM signal
- Displays `Y U no love me?!` when receiving a SIGINT signal
- Deletes the file `/var/run/myscript.pid` and terminates itself when receiving a SIGQUIT or SIGTERM signal

**Task-10**: The [11-manage_my_process](./11-manage_my_process) file is a Bash script that manages [manage_my_process](./manage_my_process).         
[manage_my_process](./manage_my_process) contains a Bash script that:
- Indefinitely writes `I am alive!` to the file `/tmp/my_process`
- In between every `I am alive!` message, the program should pause for 2 seconds
