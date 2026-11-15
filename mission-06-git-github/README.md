## TASK-6.1 Understand the basic Git workflow

| Git operation | What it does |
|---------------|--------------|
| Check repository status | Displays the current state of the repository and shows modified, staged and untracked file |
| Stage selected changes | Selects the README file's changes and adds them to the staging area for the next commit |
| Create a Commit | Saves the staged changes permanently in the repository with a descriptive message |
| View Commit History | Displays the history of previous commits with their details and messages |

## TASK-6.3 Create a Pull Request

1. What is a Branch?
A branch is a separate version of a project where developers can make changes without affecting the main project. It allows developers to work on new features or fixes independently.
2. What is a Pull Request?
A Pull Request (PR) is a request to merge changes made in one branch into another branch. It allows other team members to review the changes before they are added to the main project.
3. Why are Branches and Pull Requests useful?
Branches and Pull Requests make teamwork easier because multiple developers can work on different parts of the same project without disturbing each other's work. Pull Requests also help in reviewing code, finding mistakes and discussing changes before merging them into the main project.

## TASK-6.4 Build your Git command Glossary

1. Initialise a repository (git init): Creates a new Git repository to start tracking changes in a project.

2. Check status (git status): Shows which files are modified, staged or untracked.

3. Stage changes (git add): Selects changes that will be included in the next commit.

4. Commit changes (git commit): Saves staged changes as a snapshot in the repository.

5. View history (git log): Displays the list of previous commits and their details.

6. Create or list branches (git branch): Creates a new branch or displays the existing branches.

7. Switch branches (git switch): Moves from one branch to another.

8. Publish changes (git push): Uploads local commits to a remote repository like GitHub.

9. Retrieve remote changes (git pull): Downloads and integrates the latest changes from a remote repository into the current local branch.

-------------------------------------------------------------------------------------------------------

## 1. Difference between add and commit 
git add: Moves selected file changes to the staging area, preparing them for a commit.
git commit: Saves the staged changes as a permanent snapshot in the Git repository's history.
git add selects the changes you want to save, while git commit actually saves those selected changes in Git history

## 2. - Branch: Allows developers to work on new features or make changes independently without affecting the main project.
- Branch: Allows developers to work on new features or make changes independently without affecting the main project.
- Pull Request: Allows developers to propose, review and discuss changes before merging them into the main branch.
Purpose: Both help multiple developers collaborate on the same project safely, avoid conflicts and maintain code quality.

