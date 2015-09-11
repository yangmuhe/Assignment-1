# Assignment 1

Due September 18

The purpose of this short assignment to become familiar with the rudimentary Github workflow we'll be using throughout the class.

##Create a Github account##

Create a Github account and email it to me and Armin.

##Step-by-step guide##

###Step 1. Forking this repo###

Click on the "Fork" button on the top right while logged in to copy this repo to your account.

###Step 2. Clone repo to your local machine###

Using command line, navigate to a desired folder destination using `cd` or `dir` depending on your operating system. Then use `git clone` to clone this repo to your local machine.

Again, using command line to navigate into the folder that was just downloaded. Enter the following command
```
  git remote show origin
```
What do you see?

###Step 3. Make changes to your file###

Make changes to 'hello.txt' and enter your name where appropriate. You are done!

###Step 4. Stage, commit, and push your changes to Github###

This step involves three things. First, you "stage" the changes you've made locally so it's ready to be committed. The command is
```
  git add --all
```
where `--all` indicates that you are staging ALL changes you've made to all files, as opposed to individual files.

Then, use
```
  git commit -m "Commit message here"
```
This means that the changes have been "committed", and are henceforth tracked. `-m` indicates a message to be included with the commit. It's good practice to always include a concise, descriptive commit message.

Finally, push your committed change from your local machine to Github, using
```
  git push origin master
```
meaning "push changes from your local master branch to the remote desitination origin". We'll explain what this means later.

###In summary...###
You've just gone through the process of forking from someone else's Github repo, making your own changes, committing and tracking them, and push them to your own Github repo. We'll be doing a lot of this throughout the class, so do please get comfortable with it!
