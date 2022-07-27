# Git and Github cheat sheet - Everything in less than 30 seconds
## Create and setup a new repository in 15 seconds
Go to [Github](https://github.com/), log-in and find the green button to create a new repository. Click on it.

You should see this:

![Create a new repository](../Media/Create_Repository_Page.png)

Fill in the repository `name`, and the `description` and click on the green button “**Create repository**”. Do not initialize this repository with a README.

You should see this now:

![Fresh Repository Main Page](../Media/Fresh_Repository_Main_Page.png)

Now in your computer’s terminal, create the directory that will contain your code and `cd` into it:

![Create Directory](../Media/Create_Directory.png)

Now let’s setup our repository, and `push` a very simple README file:

![Pushing README.MD file](../Media/Pushing_README_file.png)

Now if you refresh your repository page on GitHub, you should see the `README.md` file there:

![README.md on main repository page](../Media/README_on_Repository_Main_Page.png)

On your computer, you should have a `.git` directory inside your directory.

![.git directory](../Media/git_Directory.png)

All done.


## Add new (versions of) files and commit in 5 seconds

After working on your project, you can add, commit and push new and modified files to your GitHub, with 3 commands:
```
git add <file(s) to add>
git commit -m <A meaningful commit message>
git push
```
Here’s an example. Let’s say we created a `main.c` file, and we want to push it:

![Pushing main.c file](../Media/Pushing_C_file.png)

Now on GitHub, we can see that the file was correctly pushed:

![main.c file on main repository page](../Media/C_File_in_Repository.png)

<p align="right"><sub>Copyright © 2022 ALX, All rights reserved.</sub></p>