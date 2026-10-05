# Version Control

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It allows multiple people to work on a project simultaneously, tracks changes, and helps manage conflicts when merging contributions from different collaborators. Popular version control systems include Git, Subversion (SVN), and Mercurial.
 
### Setup
To set up version control for your project, follow these steps:
1. **Install a Version Control System**: Choose a version control system (e.g., Git) and install it on your machine.
2. **Initialize a Repository**: Navigate to your project directory and initialize a new repository using the command `git init` (for Git).
3. **Add Files**: Add the files you want to track using `git add <file>` or `git add .` to add all files.
4. **Commit Changes**: Commit your changes with a descriptive message using `git commit -m "Your commit message"`.
5. **Create a Remote Repository**: If you want to collaborate with others, create a remote repository on platforms like GitHub, GitLab, or Bitbucket.
6. **Push Changes**: Push your local commits to the remote repository using `git push origin main` (replace `main` with your branch name if different).


### Branching
Branching allows you to create separate lines of development within your project. This is useful for working on new features or bug fixes without affecting the main codebase. 

To create a new branch, use the command `git branch <branch-name>`, and switch to it using `git checkout <branch-name>`.Or you can create and switch to a new branch in one command using `git checkout -b <branch-name>`.

After making changes, you can merge the branch back into the main branch using `git merge <branch-name>`.