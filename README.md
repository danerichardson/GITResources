# GITResources
##Links to how-tos on GIT
Delete a GIT Repository https://help.github.com/articles/deleting-a-repository/

## Git Bash is the cli used for github
* pwd = print working directory - dispays full path to working directory
* clear = clear all commands in interface
* ls = list files and folders in current directory (dir)
* cd = change working directory
* mkdir = make directory (md)
* touch = create an empty file
* cp = copy
  * cp -r = recursive copying contained folders
* rm = remove (del)
  * rm -r = deltree
* mv = move
  * mv -r = move recursive
  * mv also will rename file (mv new_file renamed_file)
* echo prints arguments
* date prints date

## Intro to Git
  * most operations from command line (git bash)
  * setup
    * git config --global user.name "your name here"
    * git config --global user.email "your email here"
    * git config --list confirm changes
    * exit because setup is complete

## Github
  * Github is the web hosting service using git version control
  
## Creating a repository on github
  ### create from scratch
    * go to profile and click create a profile or go to github.com/new
     * create local copy
      * open git bash
      * make a directory
      * navigate to directory
      * initialize repo with **git init**
      * point to remote repo with **git remote add origin {url}**
  * fork another users repository
    * go to repo and click fork
    * make a local copy with **git clone[url]**
      
## Basic Git commands
  * http://gitready.com/beginner/2009/01/21/pushing-and-pulling.html
  * git add = adds new files to let git know they need to be tracked
  * git commit commits to local repo - ensure all adds are done first.
  * git push updates github
  * git checkout -b branchname create a branch
  * git branch identifies current branch
  * git checkout master goes back to master branch
  * to merge changes isse a pull request at the github web site
  * Git documentation http://git-scm.com/doc
  * Github help https://help.github.com
  
    
