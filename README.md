# GitHub Commands Guide

This guide provides a basic overview and examples of important Git commands for managing a project (a simple website with HTML and CSS files in this case).

## Getting Started with Git

1. **Install Git**
   - Before you start, make sure Git is installed on your system. If not, download and install it from [git-scm.com](https://git-scm.com/).

2. **Configure Git**
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "youremail@example.com"
   ```

## Initializing a New Repository

1. Navigate to your project directory.
   ```bash
   cd path/to/your-project
   ```

2. Initialize a new Git repository.
   ```bash
   git init
   ```

## Adding Files to the Staging Area

1. Add all HTML and CSS files to the staging area.
   ```bash
   git add *.html *.css
   ```

   Or add all files in the project to the staging area.
   ```bash
   git add .
   ```

## Committing Changes

1. Commit the files in the staging area to the repository.
   ```bash
   git commit -m "Initial commit"
   ```

## Connecting to a Remote Repository

1. Add the URL for the remote repository where your project will be pushed.
   ```bash
   git remote add origin <REMOTE_URL>
   ```

   Example:
   ```bash
   git remote add origin https://github.com/username/repository.git
   ```

## Pushing Changes to GitHub

1. Push your commits to the remote repository.
   ```bash
   git push -u origin master
   ```

## Pulling Changes from GitHub

1. To update your local repository with changes from the remote repository, use:
   ```bash
   git pull origin master
   ```

## Example Workflow

Given a project structure:

```
your-project/
├── index.html
└── style.css
```

Follow these steps:

1. Navigate to the project directory and initialize a new Git repository.
   ```bash
   cd path/to/your-project
   git init
   ```

2. Add all files to the staging area and commit the changes.
   ```bash
   git add .
   git commit -m "Initial commit"
   ```

3. Connect to the remote repository and push the changes.
   ```bash
   git remote add origin https://github.com/username/repository.git
   git push -u origin master
   ```

4. When you need to pull changes from the remote repository, use:
   ```bash
   git pull origin master
   ```

---

This guide should help you use Git commands to manage your HTML and CSS project on GitHub. Adjust the file types and paths as needed for different project structures.
