# Instruction for working with Git 
*for Mac OS*

## install
* **brew install git**
    >*if Homebrew is installed*
* **git --version** 
    >*else*

## Settings 
1. Set username 

    **git config --global user name"<your_name>"**

2. Set email

    **git config --global user.email "<mail_adress@email.com>"**

## Creating a repository
1. Specify the path to the project folder

    **cd <project_folder_path>**  
    > *example*: cd </Users/ilnursibgatulin/Downloads/Git>

2. Initiate / Creating a repository

    **git init**

## Creating a commit
1. Add project files

    * **git add .** 
        >*add all files*

    * **git add --all** 
        >*add all files*

    * **git add <file_name>** 
        >*add a file*
        >>*example*: git add instruction.md

2. Create a commit with a comment 

    * **git commit -m "<comment>"**

## Other Git сommands

* **git help** 
    > *help for all commands*

* **git clone**
    > *creating a clone of the current repository*
* **git status** 
    > *status of the working directory and section of indexed files*
* **git branch** 
    >*create, view, rename and delete a branch*
* **git checkout** 
    > *move between branches*
* **git merge** 
    > *merging branches*

* **git rm**

    >*delete a file*