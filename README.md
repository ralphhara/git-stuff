# Git and Github first steps

This document describe the first steps with git and github.

Assumption: Git is already installed on your system

## Git Initial configuration

Take the first steps to configure the git global settings:

git config --global user.name "Your Name"

git config --global user.email "you@someplace.com"

### Check git global settings by running the following command:

git config --global --list

### Check git user-based config file

cat ~/.gitconfig

## Git initialization

Create or use an existing project directory on your system and, through the git bash or command prompt, navigate to your project directory, the issue the following command to initialize git:

git init (if you're inside the directory) or

git init <directory_name> (if you're one level up)