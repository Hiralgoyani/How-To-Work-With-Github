# How-To-Work-With-Github

open cmd and go to directory where you want to download repository and follow as below

1) clone git to your machine : git clone https://github.com/nishit-manjarawala/newGittest.git

write cd command and go to repository folder

2) put your all files into repository folder

3) run new command : git status

This command show file status of our repository

4) run new command as below to add files to repository : git add Filename_goes_here

if you want to add all file use '.' insted of file_name ex : git add .

5) if you have not set up your git global email and name then set it as below else skip this point:

git config --global user.email "manjarawalanishit@gmail.com"

git config --global user.name "Nishit"


6) Now Commit your work with message :git commit -m "commit message go here"

-m is use for set message to commit int this message you can explain your work and what task you did.

on commit github ask for email and password give your github account email and password

7) after successfully commit still file not updated on github. for update on github run command : git push

8) if you want to get new or update file from github to your local system run command : git pull
