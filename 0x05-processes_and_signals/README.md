0x05. Processes and signals

+++++++++++++++++++++++++++++++

	TASKS

+++++++++++++++++++++++++++++++

0. What is my PID
mandatory
Write a Bash script that displays its own PID.

1. List your processes
mandatory
Write a Bash script that displays a list of currently running processes.

2. Show your Bash PID
mandatory
Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.

3. Show your Bash PID made easy
mandatory
Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.

4. To infinity and beyond
mandatory
Write a Bash script that displays To infinity and beyond indefinitely.

5. Don't stop me now!
mandatory
We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this.
Write a Bash script that stops 4-to_infinity_and_beyond process.

6. Stop me if you can
mandatory
Write a Bash script that stops 4-to_infinity_and_beyond process.

7. Highlander
mandatory
Write a Bash script that displays:

To infinity and beyond indefinitely
With a sleep 2 in between each iteration
I am invincible!!! when receiving a SIGTERM signal

8. Beheaded process
mandatory
Write a Bash script that kills the process 7-highlander.

9. Process and PID file
#advanced
Write a Bash script that:

Creates the file /var/run/myscript.pid containing its PID
Displays To infinity and beyond indefinitely
Displays I hate the kill command when receiving a SIGTERM signal
Displays Y U no love me?! when receiving a SIGINT signal
Deletes the file /var/run/myscript.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal


10. Manage my process


11. Zombie
