# How-To-Setup-Github-SSH-key-In-Windows-10
How to setup your github SSH key In Windows 10 

Step 1
Open Your Gitbash Terminal 

Setp 2 
Config Your Github Name And Email

git config --global user.name "your-github-username"
git config --global user.email "your-github-email"


Step 3 Create A SSH Key

ssh-keygen -t rsa -b 4096 -C "yourEmail@gamil.com" (Enter)
passphrase (Password)

eval $(ssh-agent -s)
ssh-add ~/.ssh/id_rsa

clip < ~/.ssh/id_rsa.pub

Open Github SSH Setting And Past Here
