# Git Guide

Welcome to the Git Guide repository for the Ruggles Lab. This resource is designed to help team members understand and utilize Git for version control in our projects.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Basic Git Commands](#basic-git-commands)
- [Branching and Merging](#branching-and-merging)
- [Collaboration Workflow](#collaboration-workflow)
- [Additional Resources](#additional-resources)

## Introduction

Git is a distributed version control system that allows multiple people to work on a project simultaneously without overwriting each other's changes. It tracks changes in source code during software development, enabling collaboration and maintaining a history of modifications.

## Installation

To start using Git, follow these steps:

1. **Download Git**: Visit the [official Git website](https://git-scm.com/) and download the installer for your operating system.
2. **Install Git**: Run the installer and follow the on-screen instructions.
3. **Verify Installation**: Open your terminal or command prompt and type `git --version` to confirm that Git is installed correctly.

## Basic Git Commands

Here are some fundamental Git commands to get you started:

- `git init`: Initialize a new Git repository.
- `git clone [repository URL]`: Clone an existing repository.
- `git status`: Check the status of your working directory.
- `git add [file]`: Stage changes for commit.
- `git commit -m "commit message"`: Commit staged changes with a message.
- `git push`: Push your changes to the remote repository.
- `git pull`: Fetch and merge changes from the remote repository.

## Branching and Merging

Branching allows you to work on different parts of a project simultaneously. To create and manage branches:

- `git branch [branch-name]`: Create a new branch.
- `git checkout [branch-name]`: Switch to the specified branch.
- `git merge [branch-name]`: Merge the specified branch into the current branch.

## Collaboration Workflow

To collaborate effectively using Git:

1. **Clone the Repository**: `git clone [repository URL]`
2. **Create a Branch**: `git checkout -b [branch-name]`
3. **Make Changes**: Edit files and use `git add` to stage changes.
4. **Commit Changes**: `git commit -m "description of changes"`
5. **Push Changes**: `git push origin [branch-name]`
6. **Create a Pull Request**: On GitHub, navigate to the repository and create a pull request to merge your changes.

## Additional Resources

For more in-depth information, consider the following resources:

- [Pro Git Book](https://git-scm.com/book/en/v2): A comprehensive guide to Git.
- [GitHub Guides](https://guides.github.com/): Tutorials on using Git and GitHub.
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf): A quick reference for common Git commands.

