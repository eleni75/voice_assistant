This is a small attempt to create a simple voice assistant to help you in tasks with web searching and browsing or any other task you may think.

One of the main problems at the current stage is the low accuracy of the google speech-to-text conversion that this project uses

Instructions on adding new commands:

1)Create your command on a python script
2)Keep your code clean and clear and set a function that can be called to execute the operation
3)Go to the stringManipulation.py and import your file
4)Add another elif statement at the end of the if statement in the commandParser function
5)Find a keyword that invokes a call to your scripts driver function and add the statement "elif "<keyword>" in command
6)Call the scripts driver function by typing <filename>.<function-name>()
7)Make sure to properly claim your contribution at the start of your script by putting your name in a comment
