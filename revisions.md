# Revisions in the Cloud

[Back to main](README.md)
[Where I learned this stuff](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

This is where I will put put my reading notes for Revisions in the cloud

## How to setup a git repository

### Importing

- switch to the target folder for the project
- `git init`
- do an initial commit 
-- `git add *.c` 
-- `git add LICSENSE`
-- `git commit -m "commit note"`

### Cloning

- Create repository 
- terminal > access desired location `cd directory`
- create project fodler if needed `mkdir lab 03`
- On github code > clone > copy
- Terminal > `git clone` paste clone code
- `code .` to open repo in text editor

## Workflow

### Local Repo Structure

1. Working Directory: where the real files are
1. Index: staging area
1. Points to the most recent commit
![Flowchart](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

### Saving Changes

**All files are either tracked or untracked** 
Untracked files are essentially unknown to the Index
I'm still not quite sure what this means

### Day in the Life of a File

1. Gets edited
1. You prepare it to be saved or stage it
1. It's changes are saved

#### Checking your work

`git status`
This allows us to see what changes have been made recently

### Tracking and Staging Files

#### One File

`git add filename`

#### All Files

`git add *`

### Completing a change

1. `git add . ` or name of file
1. `git commit -m "commit notes"`
1. `git push origin main`
