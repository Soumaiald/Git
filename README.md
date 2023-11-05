# Git
A Guide to Essential Git Commands 

Git is a powerful and widely used version control system that allows developers to manage and track changes in their code. It plays a crucial role in collaboration, code history tracking, and maintaining the integrity of software projects. To effectively harness the benefits of Git, it's essential to become familiar with some key Git commands. In this article, we will explore essential Git commands that every developer should know.

1. git init<br />
The git init command is the first step in creating a new Git repository. By running this command in your project directory, you initialize a new Git repository, allowing Git to start tracking changes to your files.<br />
Example:<br />
```
git init
```
<p align="center">
<img width="458" alt="Screenshot 2023-11-05 at 9 47 58 AM" src="https://github.com/Soumaiald/Git/assets/94118305/cef1a1b4-51ba-4441-a5e0-634919b1bf0e"><br />
</p>
<br />
2. git clone<br />
The git clone command is used to create a copy of an existing Git repository. This is particularly useful when you want to work on a project hosted on a remote server, such as GitHub, GitLab, or Bitbucket.<br />

Example:<br />
```
git clone  <repository-url>
```
<p align="center">
<img src="https://github.com/Soumaiald/Git/assets/94118305/8104c890-0464-4f6a-98a6-5410370ef0bc"> <br />
</p>
<br />
3. git add <br />
The git add command stages changes, marking them for inclusion in the next commit. You can specify files individually or use wildcards to stage multiple files at once. <br />

Example: <br />
```
git add <filename>
```
<br />
4. git status <br />
The git status command provides information about the current state of your repository. It displays which files have been modified, staged, or untracked. <br />

Example: <br />
```
git status
```
<p align="center">
<img width="352" alt="Screenshot 2023-11-05 at 10 06 49 AM" src="https://github.com/Soumaiald/Git/assets/94118305/f377b743-b9ef-4a08-b00e-ebb89a0d3cc0"> <br />
</p>
<p align="center">
<img width="453" alt="Screenshot 2023-11-05 at 10 09 01 AM" src="https://github.com/Soumaiald/Git/assets/94118305/803160cc-c7fc-4384-9729-be54051e0719"> <br />
</p>
<br />
5. git commit <br />
The git commit command saves the staged changes as a new commit in the project's history. Each commit should have a meaningful message describing the changes made. <br />

Example: <br />
```
git commit -m "commit description"
```
<p align="center">
<img src="https://github.com/Soumaiald/Git/assets/94118305/e51832b7-2b19-459d-9b93-4e6f27d91783"><br />
</p>
<br />
6. git log <br />
The git log command shows a chronological list of commits in the repository, including commit messages, authors, and timestamps. This is a useful tool for tracking project history. <br />

Example: <br />
```
git log
```
<p align="center">
<img width="424" alt="Screenshot 2023-11-05 at 10 11 58 AM" src="https://github.com/Soumaiald/Git/assets/94118305/d05d1ee2-f104-43fc-95d5-0720f2b430d6"> <br />
</p>
<br />
7. git pull <br />
The git pull command fetches changes from a remote repository and integrates them into your local branch. This is commonly used to stay up to date with the latest changes in a collaborative environment. <br />

Example: <br />
```
git pull
```
<br />
8. git push <br />
The git push command sends your local commits to a remote repository, making your changes available to others. It is essential for sharing your work with team members or collaborators. <br />

Example: <br />
```
git push
```
<br />
9. git branch <br />
The git branch command allows you to list, create, or delete branches within your repository. Branches are used to work on features or bug fixes without affecting the main codebase. <br />

Example: <br />
```
git branch branch1
```
<p align="center">
<img width="367" alt="Screenshot 2023-11-05 at 10 38 28 AM" src="https://github.com/Soumaiald/Git/assets/94118305/ee06a9a6-22ff-4c26-96be-1b6b43c15009"> <br />
</p>
 To remove a branch, you can use: <br />
 
```
git branch -d branch_name
```

<br />
10. git checkout <br />
The git checkout command is used to switch between branches or to restore files to their state at a specific commit. It allows you to move between different project states quickly. <br />

Example: <br />
```
git chechout branch1
```
<p align="center">
<img width="478" alt="Screenshot 2023-11-03 at 7 07 59 PM" src="https://github.com/Soumaiald/Git/assets/94118305/4fdb56e5-af95-4f74-aed5-e13fa2079b13"> <br />
</p>
After committing and adding another branch we get: <br />
<p align="center">
<img width="608" alt="Screenshot 2023-11-03 at 7 16 30 PM" src="https://github.com/Soumaiald/Git/assets/94118305/3f644b91-cfb4-4fbd-8987-5405c2407e75"> <br />
</p>
<br />
11. git reset <br />
The git reset --hard HEAD~1 command resets the current branch to the commit immediately preceding the current HEAD commit, discarding all changes in the process. <br />

Example: <br />
```
git reset --hard HEAD~1
```
<p align="center">
<img width="171" alt="Screenshot 2023-11-05 at 10 48 48 AM" src="https://github.com/Soumaiald/Git/assets/94118305/6f03e8ab-f188-437b-b61b-040ae2262913"> <br />
</p>
<br />
12. git merge <br />
The git merge command combines changes from one branch into another. This is commonly used when you want to incorporate the work done in a feature branch back into the main development branch. <br />
 
Example: <br />
```
git merge <branch-name>
```
<p align="center">
<img width="688" alt="Screenshot 2023-11-03 at 7 22 24 PM" src="https://github.com/Soumaiald/Git/assets/94118305/1191221d-0cb4-43b0-863a-b71845e5d9fb"> <br />
</p>
<br />
Conclusion <br />

Mastering these essential Git commands is crucial for effective version control and collaboration in software development. Git simplifies the process of tracking changes, managing branches, and collaborating with other developers, making it an invaluable tool for any coding project. As you become more proficient with Git, you'll discover additional commands and features that can streamline your development workflow and help you maintain a well-organized codebase.

<p align="center">
<img src="https://github.com/Soumaiald/Git/assets/94118305/a7709cde-79aa-4816-bb25-50cb1ce52205"> 
</p>


