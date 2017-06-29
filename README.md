# Swen 303 Group Project
This is a group project for Swen303, involving the redesign of the [Victoria university ECS site](https://ecs.victoria.ac.nz/Main/WebHome "Ew") focussing on aspects of User Experience Design.

## Steps for contributing to this repository
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
For ease of coding, create your own branch for each feature so not everyone is modifying master at once. This simply avoids unnecessary merge conflicts.
```
git checkout -b <branch name you want to create>
```
For example:
```
git checkout -b home_page
```

## Style guidelines for pages
The Victoria university color is officially a dark green (#115737) so try to use this where possible as the background color.

The background image we're using is located in the img folder, and is called header.png (for now... this may change). This is what's going to be used as a default background persisting throughout pretty much the whole app, though at times there will be stuff on top of it. With this, try to use a white/gray color (#e7e7e7) as foreground text (eg. in the navbar).

We're going to be developing this for an ipad platform (though there is no functionality) so in your developer tools view this as a horizontal ipad (push f12 and then click the little square on a bigger square in the upper left corner of the screen to turn the device toolbar on, and then refresh the page and select 'ipad' from the dropdown menu. You may need to change the orientation to landscape as well).

## And now...
That's pretty much it. It's all css and hmtl with a little js here and there when we needed functionality. It's a design project, so it's not supposed to work.
