The video demo: https://www.youtube.com/watch?v=S0OAOJWJMuA


Description:  TaskVault is a command line manager built with python. It is like a to do list application. It allows the users to:  I) Add tasks with a tag 
2 View the tasks provided 
3 Complete tasks
4 Get a report of complete and incomplete tasks

Each task is saved in a CSV file, it’s saved with the name of the task, the date and its status of completion.

Features:

Add Tasks: The user can add any task they want by pressing the letter “A”/“a” then the program asks for a tag as well to categorize the task.

View Tasks: The user can view the tasks that the user has entered into the program by entering the letter “V”/“v” and check the status of completion of each task.

Complete Tasks: The set can mark a task as complete by entering “C”/“c”, then choosing the task’s number in the list.

Report: The user can see a report of the tasks by entering “R”/“r” then the user can see the number of tasks completed or incomplete.

How it works:

The data is saved in a csc file using python’s csv module. Each function is written in project.py and handles a certain feature and there is also test_project.py that contains pytest tests for adding tasks, viewing tasks, and reports, to test project.py.  Files:

project.py - Main file with functions and menu  
test_project.py - Contains tests using pytest  
README.md - This file

Developer:

Name: Yuvraj Singh  
GitHub Username: NextGenEcon
