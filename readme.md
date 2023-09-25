# Hello World!

* git clone url.com // to clone the repository
* cd into the folder you have cloned
* git status // to see the status of our folder
* git add readme.md
* git status
* git commit -m "Readme file updated"
* git remote add origin https://github.com/mokshagaur7/test-app.git
* git push -u origin main

## Extra Comments

* 'git add' can have multiple endings:
 * git add readme.md
    * This will add a single file to the staging area.
* git add readme.md index.ts
    * This will add two files to the staging area.
* git add *
    * This will add all changes in the current directory but not the sub directory.
* git add -all OR git add -A