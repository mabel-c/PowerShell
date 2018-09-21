# PowerShell
Powershell Configuring Samples:
--------------

Configuring your git bash :

git config --global user.name "mabel-c"

git config --global user.email "mabelche@gmail.com"

git config --list

Copy a repo into your local machine (Copy from bitbucket) :
git clone https://github.com/mabel-c/PowerShell.git

git status

# Do a change

git status

git add .

git commit -m "Initial commit"

git status

…or create a new repository on the command line
echo "# PowerShell" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/mabel-c/PowerShell.git
git push -u origin master


…or push an existing repository from the command line
git remote add origin https://github.com/mabel-c/PowerShell.git
git push -u origin master