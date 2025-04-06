# Git-basics
This repository is a hands-on guide to learning Git. 
It covers fundamental concepts like commits, branches, merging, and remote repositories with practical exercises.


# Introduction To Version Control and Git. 
 
Every developer, from the beginner to the seasoned professional, faces one certainty: code evolves. As projects grow and teams expand, tracking and managing changes to your code becomes critical. This is where version control systems, particularly Git, come into play.


Think of working on a document that goes through multiple edits with several collaborators. Version control acts as an advanced "track changes," allowing you to record every modification, restore previous versions, and review your change history—all without the risk of losing progress.

Git is a distributed version control system that allows developers to track changes in their code, collaborate with teams, and manage project versions efficiently. It is widely used in software development to ensure code integrity, facilitate teamwork, and maintain a history of modifications.

# Why Do We Need Git?

#1. Version Control – Git helps keep track of every change made to a project, allowing developers to revert to previous versions if needed.

#2. Collaboration – Multiple developers can work on the same project simultaneously without conflicts, making teamwork seamless.

#3. Backup & Recovery – With Git, project files are stored safely in repositories, preventing data loss.

#4. Branching & Merging – Developers can work on new features independently using branches and merge them into the main project when ready.

#5. Open-Source & Widely Used – Git is free, open-source, and used by major tech companies and open-source projects worldwide. 

# Setting Up Git. 
Before using Git, configure your username and email using the commands below: 

#git config --global user.name "Name" 

#git config --global user.email "your email@xyz.com"

To verify the configuration: 

#git config --list 


# Understanding Basic Git Commands 

Understanding Basic Git Commands
- git init: This is where it all begins. Running `git init` in your project’s directory sets up a new Git repository, creating the hidden `.git` directory. This directory is where Git starts tracking changes, essentially setting the stage for all the version control magic.
 
- git add: Think of this as selecting what changes you want to remember. `git add` takes the current state of your files and prepares them to be saved in your project history. It’s like bookmarking pages you want to return to.

- git commit: If `git add` is about selecting, `git commit` is about taking a snapshot of those selections. It records your changes to the local repository. Each commit has a unique ID, allowing you to keep a detailed history of what changed, when, and by whom.

- git push: After committing your changes locally, `git push` uploads your commits to a remote repository. This is how you share your changes with the team and ensure everyone has access to the latest version of the project.

- git status: This command gives you a quick overview of your repository's current state. It shows which files have been modified, which are staged for commit, and if there are any untracked files. Think of it as a dashboard that helps you stay informed about your changes before committing them.

- git log: Want to see the history of changes in your project? git log displays a list of past commits, along with details like commit messages, authors, timestamps, and unique commit IDs. It's like flipping through a project diary that records every significant update.

- git branch: Branching in Git allows you to work on different features or fixes without affecting the main project. Running git branch shows a list of all existing branches, and adding a branch name (git branch new-feature) creates a new one. This lets you experiment safely before merging changes.

- git checkout: If you need to switch to a different branch, git checkout branch-name moves you there. It’s like jumping between different versions of your project. You can also use git checkout commit-ID to go back to a specific past commit.

- git merge: Once you’re done working on a branch, git merge branch-name combines those changes into the main branch. This command helps integrate new features or bug fixes without losing any previous work.

- git pull: If you're working with a team, you’ll want to keep your local repository updated with the latest changes. git pull fetches and merges updates from a remote repository, ensuring you're always working with the newest version of the project.

- git reset: Made a mistake? git reset allows you to undo changes. You can reset individual files (git reset filename), unstage changes before committing, or even roll back to a previous commit with git reset --hard commit-ID.

- git revert: Unlike git reset, which rewinds history, git revert commit-ID creates a new commit that undoes the changes from a specific past commit while keeping everything else intact. This is useful when you want to reverse changes without losing subsequent progress.

- git clone: Want to work on an existing project hosted on GitHub or another remote repository? git clone repository-URL downloads the entire repository to your local machine, letting you contribute or experiment with the codebase.

- git stash: Need to switch tasks but don’t want to commit unfinished work? git stash temporarily saves your changes without committing them. Later, you can retrieve them using git stash pop or view stored stashes with git stash list.














