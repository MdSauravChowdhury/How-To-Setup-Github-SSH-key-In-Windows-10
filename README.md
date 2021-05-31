# How-To-Setup-Github-SSH-key-In-Windows-10
How to setup your github SSH key In Windows 10 

<h1>Step 1</h1>
<h3>Open Your Gitbash Terminal </h3>

<h1>Step 2</h1>
<h3>Config Your Github Name And Email</h3>

git config --global user.name "your-github-username"<br/>
git config --global user.email "your-github-email"


<h1>Step 3</h1>
<h3>Create A SSH Key </h3>

ssh-keygen -t rsa -b 4096 -C "yourEmail@gamil.com" (Enter)<br/>
passphrase (Password)

eval $(ssh-agent -s)
ssh-add ~/.ssh/id_rsa

<h1>Step 4</h1>
clip < ~/.ssh/id_rsa.pub

<h1>Step 5</h5>
Open Github SSH Setting And Past Here
