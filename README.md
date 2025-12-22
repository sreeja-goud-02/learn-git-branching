# LEARN-GIT-BRANCHING

Learn Git Branching is one of the most visual and interactive ways to learn Git on the web.

## LEVEL-1 (Git Commits)

A commit in a Git repository represents a snapshot of all tracked files at a specific point in time.

<img width="1270" height="681" alt="Screenshot 2025-12-22 144436" src="https://github.com/user-attachments/assets/52139fd2-f591-4764-a4a4-8dac61497f94" />


## LEVEL-1 (Git Branches)
In Git, branches are extremely lightweight. A branch is simply a pointer to a specific commit—nothing more

<img width="1361" height="824" alt="Screenshot 2025-12-22 144828" src="https://github.com/user-attachments/assets/98a7e540-2ae1-4158-a7ee-0fbdacad1939" />

The following command is used to create and switch to a new branch in a single step:
git checkout -b bugfix


 
## LEVEL-1(Branches and Merging)
Now that we understand how to create commits and branches, the next important step is learning how to combine work from different branches. This process is called merging.
What is git merge?
The git merge command is used to combine changes from one branch into another.


<img width="1370" height="799" alt="Screenshot 2025-12-22 144957" src="https://github.com/user-attachments/assets/0b4083ec-96a6-47ac-89ad-7ce6c89d7dff" />

Commands Executed
The following commands were executed step by step to complete the level:
git checkout -b bugfix
git commit
git checkout main
git commit
git merge bugfix

