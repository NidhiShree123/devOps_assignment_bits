
# Declaration 
This repo contains the assignment details for the project work of subject - Introduction to DevOps. Every effort is made to indicate this clearly, with due reference to the literature, and acknowledgement of collaborative research and discussions.

I have kept my sample code in different repo - https://github.com/NidhiShree123/assignment.git .

Please have a look and let me kow what we can make improvements in the project . 

# Contents 
1. Problem Statement
2. Methodology
3. Steps
   - Create a repository
   - Add Tow Directory and some raw code files to the repository
   -  Move Code from One directory to Another Directory
   -  Update one source code file and display the difference
   -  Create a Branch
   -  Add some raw code to the branch
   -  Merge the Branch with Main line
   -  Create the Jenkins pipeline, which is checking out the code and build and compiling it on every commit automatically.

4. Advantages of moving from Centralized Source Code to Distributed Version Control.

# Problem Statement 
ABC Organization would like to opt for the distributed version control system to upgrade their environment; where Git has been selected as the solution.
You been assigned as a consultant to educate the migration process to move their Source Code from Centralized to Distributed systems. As a phase one, you would like to go ahead with a workshop to demonstrate below operation to make the ABC team comfortable.

1. Create a Repository
2. Add Tow Directory and some raw code files to the repository
3. Move Code from One directory to Another Directory
4. Update one source code file and display the difference
5. Create a Branch
6. Add some raw code to the branch
7. Merge the Branch with Main line
And at the end provide the Summary of advantages of moving from Centralized Source Code to Distributed Version Control.

Part 2:
Create the Jenkins pipeline, which is checking out the code and build and compiling it on every commit automatically.

# Steps
Git Commands for specific operation :
1. To initialise the directory

- git init: used to initialise a new git repository within a directory
- This command is used to initilaise a new directory to a git repository. Here we did the same for our Assignment directory.

- Post this we created a new repo on github as devOps_assignment_bits.


![git init](https://github.com/NidhiShree123/devOps_assignment_bits/assets/70796956/ebcb2b7a-b5e2-4d8d-a590-19b420c7320d)

2. Link the remote repo to github
   
- git remote add <remote_name> <remote_link>: 
- Post craetion of ou repos , we linked our remote repository to our github repository.


![git add remote](https://github.com/NidhiShree123/devOps_assignment_bits/assets/70796956/fc1c461f-ed32-4b97-b61a-5362cee28fe0)


3. Add two directories and some raw code files to the repository
- git add: This command is used to start tracking files, and to stage changes.
- git commit: This command is used to commit the staged changes.
- git status: This command is used to view which files are untracked, tracked, and staged for commit.
- We create two directories directory1 and directory2, and then add two files directory1/firstfile.py and directory2/secondfile.py with raw codes in python.


![git commit](https://github.com/NidhiShree123/devOps_assignment_bits/assets/70796956/ba47124c-fe35-4e39-afb7-375d32506343)

![git commit second](https://github.com/NidhiShree123/devOps_assignment_bits/assets/70796956/e0aeb498-f11c-40d5-bfb7-75c2f8c3c4de)


4. Move code from one directory to the other directory
- We shifted firstfile.py from directory1 to directory2.
- Similarly, we move secondfile.py from directory2 to directory1.

- Once the files got interchanged , we committed the changes and add the message with commit<'your message'> and staged the changes to look for unstaged or staged 
  changes.

![interchange file](https://github.com/NidhiShree123/devOps_assignment_bits/assets/70796956/bdd9f6f4-22cc-4c44-99b9-7811da8ede10)

5. Update one source code file and display the difference
- git diff: used to display delta for files or commits.


![git diff](https://github.com/NidhiShree123/devOps_assignment_bits/assets/70796956/8270ceee-7fc2-4f93-9607-7c505a708ca6)

6. Create a branch (feature branch)
- git branch: used to create a new branch
- git checkout: used to switch to an existing branch
- We create a new branch feature-branch. Normally, we first create a new branch like git branch feature-branch and then switch to it with git checkout feature- 
  branch

![git new branch](https://github.com/NidhiShree123/devOps_assignment_bits/assets/70796956/7f8aa4dc-28ed-495f-9c64-819c079bc374)

  
7.Merge the changes (master branch)
- git checkout:This command is used to switch to an egixisting branch
- git merge : This command is used to merge the changes from specified branch to existing branch.

![git merge](https://github.com/NidhiShree123/devOps_assignment_bits/assets/70796956/a7aa797b-a32f-4573-83a0-bbedee4761d3)

8. Push the changes
- git push : This comand is used to push the changes all from remote to gihub repository.
- command can be written as --  git push <remote_name> <branch_name>


![git push](https://github.com/NidhiShree123/devOps_assignment_bits/assets/70796956/2c234295-b686-4d49-baca-b82c8cf6953a)


## Advantages of CVCs 

 - Faster and more efficient, because operations can be performed on local machines, and then later pushed / pulled to the version control server, when required.

 - Multiple levels of redundancy, because each developer would have a copy of the code on their system, even if the main server loses its copy, it can easily be recovered.

 - Much better branching support, where each new feature can have its own branch, which can be tested in isolation with each other and then later merged into the main branch once ready.


## Jenkins Pipeline Script 
 -  Please refer to repo - https://github.com/NidhiShree123/assignment.git
