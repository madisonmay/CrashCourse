Version Control: Github mastery
-------------------------------

Note: This tutorial was made by and for Linux users. It is meant to be a friendly introduction to Github for anyone who wants to learn more about Github/version control, and by no means is an all-encompassing document about the topic. We've sprinkled in a few links and resources that go into more detail, and feel free to talk to us if you have any questions or witty conversation starters. :)

#### Why github?
- It's an awesome way to keep all of your code in one place and collaborate with others on code projects. Yay for open source code!
- Don't use dropbox or google drive for code. These version control programs update the files in the cloud whenever someone saves it (which is advantageous in some situations, but probably not for code prototyping when you want to run things and make progress in between "versions"). 
- Everyone has a local copy of the code! :) You don't want one person's bugs to affect the rest of the team. 
- Make sure you can trace a bug back to a particular point in time (find out exactly what happened when).
- Pull requests - giving people an opportunity to approve a modification to the code.
- Ability to revert back to previous versions of the code - so it's safe to experiment and code new things without fear. (No control-Z sprees of panic!)

#### What's git? How does it work?
Brief definitions for these buzzwords:
- git refers to the version control system. 
- Github is the collaborative code website for users to share their code with others and keep track of their projects over time.
- An overview of how to use git: Read the ["basic usage" section](http://marklodato.github.io/visual-git-guide/index-en.html) of this webpage. Feel free to continue further if you're interested though!
- ![Basic usage](http://marklodato.github.io/visual-git-guide/basic-usage.svg)


#### Setting things up on your computer
- [Make a github account](https://github.com/join) if you don't have one already.  
- You should already have git installed on your system. If not, then simply type this into a terminal window:

```
   $ sudo apt-get install git
```

#### Your first cloned github repository :D and getting familiar with commands 

Shall we 'git to it'? :)

Navigate to wherever you want to start working on your computer, and clone this repository!
```
   $ git clone https://github.com/madisonmay/CrashCourse.git 
```
Navigate into the CrashCourse repository on your computer. 
Open the text file called "Minions.txt" with your favorite text editor.
Add your github username to the list.
When you're done, save the text file and get ready to push your updates.

```
   $ git status # it's a good habit to check what updates are going to be pushed
   $ git add Minions.txt # stage the file 
   $ git commit -m "Updated Minions.txt with github username"
   $ git push #pushes your updates to the github website

```

Oh noes! it turns out that you have a *dundundun* MERGE CONFLICT! 
But fear not, young code warrior! You can handle this...

As suggested, pull the project code from Github.
Then, open the file of interest and look for the masses of chevrons >>>>>>>>>. This is the chunk of code that Github is currently freaking out about, and is telling you to fix it. 

#### Social github: fork, branch, or just a collaborator setup?
pcottle.github.io

merging!
origin/upstream/remote/etc terminology


#### HTTPs vs SSH

- Insert a short description/definition of protocols
- Search for pros/cons of each
- Depends on what other services want when interacting with github (heroku, etc)
- In the end it's personal preference and it's a good idea to be at least aware of the different options

http://stackoverflow.com/questions/11041729/why-does-github-recommend-https-over-ssh
https://help.github.com/articles/using-ssh-over-the-https-port
http://serverfault.com/questions/430059/what-are-the-pros-and-cons-of-ssh-and-http-for-a-git-server

#### Other options/preferences
- The first time you use git, your computer may ask you about --config settings. Go ahead and do this with your email address so your commits from that computer are associated with your github account. :)
```
$ git config --global user.email youremailnamehere@students.olin.edu
```
- Color coding is your friend! We recommend doing this so your git terminal activities are easier to read and more exciting.
```
$ git config --global color.ui true
```
- You may or may not have heard of "shortcuts" and hyphenated options for git commands. They do exist, and are very googleable if you want to improve your mastery of github in the command window.

- Click here for [additional github configuration shenanigans](http://git-scm.com/book/en/Customizing-Git-Git-Configuration)

#### Any questions, comments, or concerns after doing this tutorial?
- Ask away! We love feedback and iterations. :)

#### Onwards!
- Github is a great place to have a "code portfolio" for the sake of past/current code projects. 
- As always, whenever you have a project, make sure you have a version control system that works well given the project/team member context. Github is almost certainly the best choice for code shenanigans but be aware and choose wisely. :)