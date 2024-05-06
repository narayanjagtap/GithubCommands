
# Github Commands


<b>Push your Project code on GitHub using this commands.</b>

//git instalation <br>
sudo apt update <br>
sudo apt install git
<br><br>

//check git version <br>
git --version
<br><br>

//information about the different git commands<br>
git help
<br><br>

//Check that git has your information username and password<br>
git config --list
<br><br>

//give your username and password to git <br>
git config --global user.name "narayanjagtap" <br>
git config --global user.email "example@gmail.com"
<br><br>

//initialize the git<br>
git init
<br><br>

//Check the file in your folder<br>
git status
<br><br>

//add these file in staging area<br>
git add .
<br><br>

//commit your files in local repositories<br>
git commit -m "first commit"
<br><br>

//change your branch master to main <br>
git branch -M main
<br><br>

//gives GitHub reposetorie URL
git remote add origin https://github.com/narayanjagtap/gitcommands.git

//push your files on GitHub 
git push -u origin main
