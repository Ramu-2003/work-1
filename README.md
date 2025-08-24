# this is the first text which i was written using git comands using the vs code 

#edited inside the git-hub to check the pull command

# git commands

git init

git add remote origin <https>

then if it is connected it's ok if not then 

git config --global user.name "Ramu-2003"

git config --global user.email "ramu4012y@gmail.com"

then enter 

code .
 

it opens vs code in the location which we have open the file using cmd 

then  open terminal use powershell or git bash

select git bash

git init

git status

git add .     or git add "filename"

git commit -m "README.md"

git add remote origin <https>

git push -u orgin master    # because using git bash it uses branch name as master 


#if you have changed in GitHub then if we want to change that in the vs code then use 

git pull origin master


# if I have added the text in the readme file inside the vs code then it should update in GitHub then we use

git status 

git add "README.md"

git commit -m "updated README with new text"

git push

then check inside the GitHub  the text will update 

that's it 


if you want to change the master to main then 


git branch -M main

git push -u origin main


then the master has changed to main




