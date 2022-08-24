# how_push_to_github
Pushing code to GitHub means to upload your project code to the GitHub.com code-hosting service. In this short article, we'll show you how to do this using Git on the Command Line.

How to Create a Local Repository
First, you need to have a local repository for your actual project code. (If you already have this, skip to the next section below titled "How to Push to GitHub".)

Using Git on the Command Line
Open the command line ("Terminal" on the Mac, "Git Bash" on Windows) and change into your project's base directory. There, you can create a new Git repository:
$ cd projects/my-project
$ git init ----> first command

As a first step, you can add all of your current files to the repository and then bundle these in a commit:
$ git add .  -----> second command
$ git commit -m "Initial commit"  ------> third command

You can then connect this remote repository to your local Git repository with the following command:
$ git remote add origin <remote repository URL>  -----> fourth command

The final step is to push your changes from your local repository to your new remote repository:
$ git push origin master -------> fifth command

Give your github Username : sishir44
Give your token/password : **********

Ok !!!!!

