## **Version Control** 
- issue: sometimes you just want to keep the final version of many different revisions

- VERSION CONTROL: a way to manage the evolution of a set of files
 ![image](https://user-images.githubusercontent.com/82544669/211713111-98e09f13-0be2-4bc4-b90a-95cb99613e66.png)
  - enables multiple people to work on a single project at the same time 
  - each person edits their own copy of the files and chooses when to share those changes with the rest of the team 
  - ^ therefore, temporary of partial edits by one person do not interfere with another person's work 
  - **When using a version control system, you have one copy of each file and the version control system tracks the changes that have occured over time.**
  - **REPOSITORY (REPO)**: A way to manage the evolution of a set of files 
    - ![image](https://user-images.githubusercontent.com/82544669/211714571-003d2b65-f1a6-4297-a188-d28686c826d0.png)
  
---

## **git & GitHub**
- git: the version control system 
  - it tracks changes from microsoft word 
- GitHub (Bitbucket of GitLab) is the home where your git-based projects live on the internet 
  - kinda like the social media or dropbox (?) for programmers 
- GitHub repos are your coding social media
- A GitHub repo contains all of the files and folders for your project 
- GitHub is a remote host -- it is geographically distant from any files on your computer

---

## Questions 
- Q1: What does "pull" and "push" mean in version control 
- A1: pushing is transfering commits (more recent version of source code) from your local repository to a remote repo. pushing exports commits to remote branches. git pull copies changes from a remote repository to a local repository  
  - local repositories - on the computers of team members 
  - remote repositories - hosted on a server that is accessible for all team members (internet or local network)  
  - a **commit** is an operation which sends that latest changes of the source code to the repository --> making these changes part of the head revision of the repository 
    - commmits in version control update the repo with the latest commited version. therefore, commits in version control systems allow for rolling back to previous versions of the source code easily 
