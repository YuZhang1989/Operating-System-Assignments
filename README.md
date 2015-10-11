# Operating-System-Assignments
OS Assignments
Assignment1:
Shell Program - Programming assignment

Implement a simple command line shell program in C that interacts with the user in the following way. By default, the shell gives a prompt to the user. When the user types in a command (in response to its prompt) and hits Enter, the shell creates a child process that executes the command he entered and displays the results if any. It then prompts for more user input by displaying the prompt again. 

For example, when the user types command ls, the shell should display a listing of files in the current working directory. Your program should achieve this by simply passing this command to the underlying shell and receiving the results generated by it. Do not try to implement the functionality of the command within your own program.

The shell can be limited to handling basic commands that do not involve piping and redirection.

Please submit a zip file labeled as Assignment1_Yourname.zip. It should include a PDF file with explanation of what your code does (this is optional if your code is self explanatory with comments) and the source C files.


Assignment2:
Multithreading - Programming Assignment
Study the example program in the attached file. This program creates a new thread. Both the main thread and the new thread then increment the variable counter infinitely. After incrementing the value of counter, each thread prints a message showing the value of the variable. One of the threads exits when it finds that the counter value has exceeded 25. Run the program and explain the output. Why do the print statements stop appearing after a certain point in the program ? Explain.

1. Compile and run the program on a Linux system. Find out what results it produces and explain the results.
Compile as follows:
$ gcc assignment_multithreading.c -o assignment_mt -lpthread 

Run using the following command
$ ./assignment_mt

2. Modify the program and write a correct version that fixes the problem that you just discovered. Explain how you fixed the program.

Please submit a zip file labelled as Assignment2_Yourname.zip. It should include a PDF file with explanations to questions above and a C source file with the modified program.
