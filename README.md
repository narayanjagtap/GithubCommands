
# Github Commands


<b>Push your Project code on GitHub using this commands.</b>

//git instalation
sudo apt update
sudo apt install git

//check git version
git --version

//information about the different git commands
git help

//Check that git has your information username and password
git config --list

//give your username and password to git
git config --global user.name "narayanjagtap"
git config --global user.email "example@gmail.com"

//initialize the git
git init

//Check the file in your folder
git status

//add these file in staging area
git add .

//commit your files in local repositories
git commit -m "first commit"

//change your branch master to main
git branch -M main

//gives GitHub reposetorie URL
git remote add origin https://github.com/narayanjagtap/gitcommands.git

//push your files on GitHub 
git push -u origin main
