# Homework for the CLI/Git class

Except for the parts involving Github, the homework should be done using *only* the command line, i.e. git-bash for the windows users and the terminal for the linux and macOS users.

1. Using github, fork this repository
2. Using the command line, create a directory named potatoe, and enter the directory
3. Using the command line, clone the repository that you just forked 
4. Using git, create a branch named `yourfirstName_yourlastName` and move to that branch (hint: type `git branch` to see in which branch you are)
5. Use VIM (in the command line) to write ONE shell script named `yourfirstName_yourlastName.sh` to do following:
    5.1. Create a directory named cabbage
    5.2. Enter the directory cabbage
    5.3. Check the path for the directory where you are
    5.4. Create an empty file named orange.txt
    5.5. Write the content "Hello" five times to the file orange.txt
    5.6. Copy the file orange.txt and paste its contents into 1.txt, 2.txt, 3.txt, 4.txt and 5.txt
    5.7. Write the text "cat" to pets.txt
    5.8. Append the text "dog" to pets.txt
    5.9. Append the text "hamster" to pets.txt
    5.10. Check the contents of the file pets.txt
    5.11. Check the contents of the directory where you are
6. Use git to commit your shell script
7. Use git to push the changes in your branch to your hyf_cli_git_homework repository on github
8. Do a pull request to merge your `yourfirstName_yourlastName.sh` into this repository


Finally, run the script and make sure the directory and the files were created as expected.


Tips:
 - you should use the following commands: `cd`, `pwd`, `mkdir`, `>`, `ls`, `>>`, `cat`, `cp`
 - in git you should use: `git init`, `git clone <URL>`, `git checkout -b branch_name`, `git add`, `git commit`, `git push`
 - a shell script should have the extension .sh
 - to run a shell script use `sh file_name.sh`
 
