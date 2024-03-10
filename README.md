# python_git_entry_point

Welcome to the [python_git_entry_point](https://github.com/Laurance/python_git_entry_point) repository!

## Overview

This repository is designed to help students quickly get started with Git for Python projects, 
providing essential information on installation, setup, and basic commands. 
Whether you're new to version control or looking to refresh your skills, 
this guide will assist you in setting up your development environment.

## Getting Started

### 1. Install Git

#### Windows (using TortoiseGit):

1. Download and install [TortoiseGit](https://tortoisegit.org/download/).
2. Follow the installation instructions provided by the installer.

### 2. Configure Git

After installing Git, it's essential to open a Git Bash terminal and 
configure your identity with the following commands:

```bash
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

Replace `you@example.com` with your GitHub account email address 
and `Your Name` with your name.

You may also set up SSH keys by following the steps here: 
[Connecting to GitHub with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh).

### 3. Clone the Repository
Now that you have Git installed and configured, 
clone this repository to your local machine using the following command:

```bash
git clone https://github.com/Laurance/python_git_entry_point
```

### 4. Start Developing
You are now ready to start developing! 
Create a new branch for your changes using the following commands:

```bash
cd python_git_entry_point
git checkout -b experimental/your-name
```

Replace `your-name` with your name.

Make your changes, commit them, and push to your branch when ready:

```bash
git add .
git commit -m "Add your commit message here"
git push origin experimental/your-name
```

#### Basic Git Commands
- `git status`: Check the status of your working directory and staging area.
- `git add <file>`: Add changes in <file> to the staging area.
- `git reset`: Reset the changes added to the staging area.
- `git commit -m "Your commit message"`: Commit staged changes with a descriptive message.
- `git pull origin master`: Fetch and merge changes from the remote repository.
- `git push origin <branch>`: Push your changes to the remote repository.


## Additional Resources

For more information, refer to the official [Git documentation](https://git-scm.com/docs/git) or 
[GitHub Docs: Getting started with Git](https://docs.github.com/en/get-started/getting-started-with-git)

<i>Happy coding! If you encounter any issues or have questions, feel free to reach out! </i>