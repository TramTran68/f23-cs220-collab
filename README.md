# f23-cs220-collab
CS220 Fall 2023 Collaboration
Let's collaborate!

Rules:
* Do **not** make changes to the main branch.
* **Always** make changes to a feature branch.
* Have fun creating and collaborating!

This repository serves as a comprehensive guide to understand and practice the concepts of forking and branching in Git.
This guide will walk you through the process of forking a repository, creating branches, making changes, and submitting pull requests.

**A. Forking a Repository**
1. Visit any Repo on GitHub
Choose a repository you'd like to contribute to or experiment with.

2. Fork the Repository
Click on the "Fork" button in the top-right corner of the repository page.
Choose your own GitHub account as the destination for the fork.
Now you have your own duplicate of the entire repository, including all branches at the time of forking. You have full control over this forked repository.

**B. Branching Within a Repository**
A typical repository has branches like main (or master), staging, dev, and feature branches.

1. Create a Feature Branch
1.1. To make changes, create a new branch using the following commands:
git checkout -b feature-branch
1.2. Make changes in this feature branch.

2. Commit Changes
2.1. Stage and commit your changes using:
  git add .
  git commit -m "Your commit message"

3. Push Changes to Forked Repository
Push your changes to your forked repository:
git push origin feature-branch

4. Create a Pull Request (PR)
4.1. Open your forked repository on GitHub.
4.2. Create a pull request:
4.2.1. Specify your feature branch as the source branch.
4.2.2. Specify the repository owner's branch (e.g., dev or staging) as the target branch.
   
**C. Contributing to an Open Source Project**
1. Fork the Project
Fork the open source project you want to contribute to and follow the forking steps mentioned above.

2. Make Changes and Submit a PR
2.1. Make changes in your forked repository's feature branch.
2.2. Create a pull request to the original repository:
2.2.1. Specify your feature branch as the source branch.
2.2.2. Specify the project owner's branch (e.g., dev or staging) as the target branch.
