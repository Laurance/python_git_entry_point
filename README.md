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

### 3. Fork the Repository

Login into GitHub with your institutional email address.
In case you did not apply for the <b>GitHub Student Developer Pack</b>
you can do that now by following this link: https://education.github.com/pack

Once you are logged in you can fork this repository by following
the steps described here: [Forking a Repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#forking-a-repository)

### 4. Clone the Repository
Right now you have a fork of this repository in your account, 
but you do not have the files in that repository locally on your 
computer. Navigate to your repository and copy its URL.

Now that you also have Git installed and configured on your local machine
you can clone that repository to your machine using the following command:

```bash
git clone your-repository-url
```

Replace `your-repository-url` with the URL of your repository.

### 5. Create a Branch
Create a new branch to keep all the files that you will create
and all your progress. Use the following commands:

```bash
cd python_git_entry_point
git checkout -b experimental/your-name
```

Replace `your-name` with your name.


### 6. Start Developing
You are now ready to start developing!

Create a new Python file in the python_git_entry_point directory,
and add your code there. Make sure you don't have any errors and that
you follow all PEP8 Style Guide recommendations. 
You can check the status of your files with the following command:

```bash
git status
```

Once you consider you reached a step where your files can be saved
you can commit them, and push them to the remote version of your branch:

```bash
git add .
git commit -m "Add your commit message here"
git push origin experimental/your-name
```

Compose clear and concise commits using present tense verbs, without ending periods.
Read your commit message as: <i>"If applied, this commit will `<your commit message>`"</i>.

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