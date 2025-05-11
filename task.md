# Installation  of git (DONE)
   - windows - gitbash online download
   - mac
    brew install git
   - linux - gitbash follow commands provided on docs

   common use git bash

# Create a git account | github , gitlab, bitbucket

# Generate SSH Key 
  - ssh-keygen -t rsa -b 4096 -C "your email" 
  - once above done copy and paste ssh keys on github, gitlab, bitbucket

  IN General
  Local Repo ----> SSH-kEY ----> Remote Repo 

  # test with ssh-agent 
  eval "$(ssh-agent -s)"
  ssh-add ~/.ssh/id_rsa_er_sachin_36

  Local Repo is Connected with Remote Repo through SSH-KEY

# Basic Git Commands

#


# Project 
  - any org 
      - will create a repo on (github , gitlab. bitbucket)
      - they will invite to collaborate
      - first you have to register there and then you can collaborate

 - first repo 


 =======

 1. Account Creation
 2. SSH Key Geneartion
 3. Make a folder
 4. initialize git  | git init
 5. git remote add origin <remote-repo-url> eg: if ssh using then use ssh url , origin play as variable name
 6. We can check file status | git status (read , green files)
    - red : untracked files
    - green : tracked files
    - yellow : modified files
