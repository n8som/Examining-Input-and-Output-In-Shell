# Examining-Input-and-Output-In-Shell

<h2>Activity Overview</h2>

When you communicate with the shell, the commands in the shell can take input and return output or error messages.

In this lab activity, I’ll use the ```echo``` command to examine how input is received and how output is returned in the shell. Next, I’ll use the ```expr``` command to further explore input and output while performing some basic calculations in the shell.

This activity will build foundations in understanding how to communicate with the Linux operating system through the shell. As a security analyst, I'll need to input commands into the shell and recognize when the shell returns either output or an error message.

<h2>Scenario</h2>

As a security professional, it’s important to understand the concept of communicating with your computer via the shell.

In this scenario, I have to input a specified string of text that I want the shell to return as output. I'll also need to input a few mathematical calculations so the OS (operating system) can return the result.

Here’s how I’ll do this: First, I’ll use the ```echo``` command to generate some output in the shell. Next, I’ll use the ```expr``` command to perform basic mathematical calculations. Finally, I’ll use the ```clear``` command to clear the Bash shell window.

Get ready to examine input and output in the Bash shell!

<h2>Task 1. Generate Output With The "echo" Command</h2>

The ```echo``` command in the Bash shell outputs a specified string of text. In this task, I’ll use the ```echo``` command to generate output in the Bash shell.

1. Type ```echo hello``` into the shell and press ENTER.

The hello string should be returned:

![image](https://github.com/n8som/Examining-Input-and-Output-In-Shell/assets/110139109/fc50d45d-18d0-44e1-914a-a6acfc2998ed)

The command ```echo hello``` is the input to the shell, and ```hello``` is the output from the shell.

2. Rerun the command, but include quotation marks around the string data. Type ```echo "hello"``` into the shell and press ENTER.

The hello string should be returned again:

![image](https://github.com/n8som/Examining-Input-and-Output-In-Shell/assets/110139109/adc858c2-cfdc-4880-928f-36e1c3f6b483)

Note: The output is the same as before. The quotation marks are optional in this case, but they tell the shell to group a series of characters together. This can be useful if you need to pass a string that contains certain characters that might be otherwise misinterpreted by the command.

3. Use the echo command to output a name to the shell.

Type ```echo "name"``` into the shell, replacing ```"name"``` with any name, and press ENTER.

The name entered as the string should return as the output:

![image](https://github.com/n8som/Examining-Input-and-Output-In-Shell/assets/110139109/4550e354-91b8-4cd4-ae27-97b3583959bc)

<h2>Task 2. Generate Output With The expr Command</h2>

In this task, I’ll use the ```expr``` command to generate some additional output in the Bash shell. The ```expr``` command performs basic mathematical calculations and can be useful for quickly performing a calculation.

Imagine that the system has shown that I have 32 alerts, but only 8 required action. I want to calculate how many alerts are false positives so that I can provide feedback to the team that configures the alerts.

To do this, I need to subtract the number of alerts that required action from the total number of alerts.

1. Calculate the number of false positives using the ```expr``` command.

Type ```expr 32 - 8``` into the shell and press ENTER.

The following result should be returned:

![image](https://github.com/n8som/Examining-Input-and-Output-In-Shell/assets/110139109/1f22b315-18d3-4a7a-a998-91d5e50f9e30)

Note: The expr command requires that all terms and operators in an expression are separated by spaces. For example: ```expr 32 - 8```, and not ```expr 32-8```.

Now, I need to calculate the average number of login attempts that are expected for a year. From the information I have, I know that an average of 3500 login attempts have been made each month so far this year.

So, I should be able to calculate the total number of logins expected in a year by multiplying 3500 by 12.

2. Type expr 3500 * 12 into the shell and press ENTER.

The correct result should now be returned:

![image](https://github.com/n8som/Examining-Input-and-Output-In-Shell/assets/110139109/bd391189-45d6-4150-b298-d1ede7c40d7b)

<h2>Task 3. Clear the Bash shell</h2>

In this task, I’ll use the ```clear``` command to clear the Bash shell of all existing output. This allows me to start with the cursor at the top of the Bash shell window.

When I work in a shell environment, the screen can fill with previous input and output data. This can make it difficult to process what I’m working on. Clearing the screen allows me to create a clutter-free text environment so I can focus on what is important then.

- Type ```clear``` into the shell and press ENTER.
  
Note: All previous commands and output will be cleared, and the user prompt and cursor will return to the upper left of the shell window.

<h2>Conclusion</h2>

I now have practical experience in using basic Linux Bash shell commands to

- generate output with the echo command,
- generate output with the expr command, and
- clear the Bash shell with the clear command.

Understanding input and output is essential when communicating through the shell. It’s important that I’m comfortable with these basic concepts before I go on to work with additional commands.

