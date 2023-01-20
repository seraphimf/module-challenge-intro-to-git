## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a version control system that helps developers keep track of every time any change has been made to the project. 

2. What is the difference between Git and GitHub?
Git hub is a where you store every version of the code and it lets the developers know what has been changed and when. It is also a place where you can submit a change for someone to approve of before adding it onto the main code. 

3. Why do we create a branch?
So the section of the main code we are working on is separate from the main project/code.

4. What is the purpose of a Pull Request?
For a supervisor or team lead to have a chance to check your work before making it final.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
git switch main

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git fetch shows you the changes from a remote repo but doesn't merge them
git merge lets you merge a remote branch into the main branch or any branch you are currently in on terminal.
git pull lets you pull a file from the same branch you are working in with other people when git fetch lets you do something similar except their work is in a remote branch.

7. What is a merge conflict?
When you try to merge 2 branches together that both have changes made to it.

8. How do you resolve a merge conflict?
You have to go in and update/edit any of the files that have merge conflicts and then use the git add . then git commit commands to successfully merge.
