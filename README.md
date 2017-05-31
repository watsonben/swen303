# Swen 303 Group Project
This is a group project for Swen303, involving the redesign of the [Victoria university ECS site](https://ecs.victoria.ac.nz/Main/WebHome "Ew") focussing on aspects of User Experience Design.

## Steps for contributing to this repository
I'm assuming minimal knowledge of git here...
### Step 1
On your home computer, initialize a git repository by navigating in the command line to the directory, and typing in the following:
```
git init
git remote add origin https://github.com/watsonben/swen303.git
git pull origin master
```
To make everything easier, executing the following will mean that in the future, you'll only have to type `git pull` to pull, and can leave off the 'origin master'
```
git branch --set-upstream-to=origin/master master
```
### Step 2
For ease of coding, create your own branch upon creation so not everyone is modifying master at once. This simply avoids unnecessary merge conflicts.
```
git checkout -b <branch name you want to create>
```
For example:
```
git checkout -b the-branch-of-ben
```
