Version Control: Github mastery
-------------------------------

#### Why? Motivations to use github!
- It's an awesome way to keep all of your code in one place and collaborate with others on code projects. 
- Don't use dropbox or google drive for code. 
- Everyone has a local copy of the code! :) You don't want one person's bugs to affect the rest of the team. 
- Make sure you can trace a bug back to a particular point in time (find out exactly what happened when).
- Pull requests - giving people an opportunity to approve a modification to the code.
- Ability to revert back to previous versions of the code - so it's safe to experiment and code new things without fear. (No control-Z sprees of panic!)

#### What's git? How does it work?
- git refers to the version control system. 
- Github is the collaborative code website for users to share their code with others and keep track of their projects over time.
- An overview of how to use git: Read the "basic usage" section of this webpage. Feel free to read more if you're interested though!:
http://marklodato.github.io/visual-git-guide/index-en.html

#### Setting things up on your computer
- You should already have git installed on your system. If not, then simply 

```
   $ sudo apt-get install git
```

#### #### Your first github repository :D and getting familiar with commands 

Clone this repository!
```
   $ clone ...
```

Open the text file called "Minions.txt"
Add your github username to the list.
When you're done, save the text file and get ready to push your updates.

```
   $ git status ... # it's a good habit to check what updates are going to be pushed
   $ git add Minions.txt # stage the file 
   $ git commit -m "Updated Minions.txt with github username"
   $ git push #pushes your updates to the github website

```

Oh noes! it turns out that you have a *dundundun* MERGE CONFLICT! 
But fear not, young code warrior! You can handle this...

- to be continued
- The hyphenated options/shortcuts
- maybe mention colors/ssh? 
- git config name and email things

#### Social github: fork, branch, or just a collaborator setup?
pcottle.github.io

merging!
origin/upstream/remote/etc terminology

#### Dundundun - Conflicts

#### HTTPs vs SSH
