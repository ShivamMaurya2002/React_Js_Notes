## Git & GitHub:-

---

**What is Git?**<br>
&nbsp; &nbsp; Git is a Version Control System (VCS) use to:- <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1. Track changes in code.<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 2. Save Different Version of Projects.<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 3. Work safely without losing code.<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 4. Collaborate with other Developers.<br>

**In Simple Words:-** Git helps us to manage and track code our code history. 

**Interview:-** Git is a Version Control System (VCS) that track changes in source code.<br>
 
---

**What is GitHub?**<br>
&nbsp; &nbsp; GitHub is an online platform that:-<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1. Stores Git Repositories on GitHub.<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 2. Helps Developers share code.<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 3. Allow team collaborations.<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 4. Provide features like <b>pull request</b> and <b>pull issues</b>.<br>

**In Simple Words:-** GitHub is a place where Git projects are stored online.

**Interview:-** GitHub is a cloud-based platform used to host Git Repositories.

---

## Basic Git & GitHub Commands:- <br>

**(I). git init:-** Initializes a new git repository in a project.<br>
<pre> git init </pre> <br>

**(II). git status:-** Shows the current status of a files(modified, staged, untracked).<br>
<pre> git status </pre> <br>

**(III). git add:-** Add files to staging area before committing.<br>
<pre> git add . <br> git add File_Name </pre> <br>

**(IV). git commit:-** Save staged changes with a descriptive message.<br>
<pre> git commit -m "Your_Message" </pre> <br>

**(V). git log:-** Displays the commit history of the project.<br>
<pre> git log <br> git log --oneline </pre> <br>

**(VI). git branch:-** Switch the branch or connects a new branch.<br>
<pre> git checkout branch_name <br> git checkout -b new-branch </pre> <br>

**(VII). git remote:-** Connects the local repository to remote GitHub repository.<br>
<pre> git remote add origin "Your_repo_url".git </pre> <br>

**(VIII). git push:-** Upload local commits to GitHub repository.<br>
<pre> git push -u origin main </pre> <br>

**(IX). git pull:-** Fetches and merge changes from the remote repository.<br>
<pre> git pull origin main </pre> <br>

**(X). git clone:-** Create a local copy of a GitHub repository.<br>
<pre> git clone "source_repo_url" </pre> <br>

**(XI). git rm:-** Remove all files from Git tracking and the project.<br>
<pre> git rm File_Name </pre> <br>

**(XII). .gitignore:-** Specifies files and folders that Git should ignore.<br>
<pre> node_models/ <br> .env </pre> <br>

**(XIII). git fetch:-** Downloads changes from remote repository without merging.<br>
<pre> git fetch <br> git fetch origin <br> git fetch origin main </pre> <br>

**(XIV). git merge:-** Combines changes from one branch into another.<br>
<pre> git merge branch_Name </pre>

**(XV). git mv:-** Rename or move a file or folder in a Git repository while keeping its history.<br>
<pre> git mv old-name new-name </pre>

---

## Git Username and Email Commands:-<br>

**1️⃣ Set Username (Global):-** <br>

**(I). git config --global user.name:-** Sets the username for all Git projects on your system.<br>
<pre> git config --global user.name "Your Name" </pre>

**2️⃣ Set Email (Global):-** <br>

**(II). git config --global user.email:-** Sets the email for all commits. The email should match your GitHub account email.<br>
<pre> git config --global user.email "youremail@gmail.com" </pre>

**3️⃣ Check Username and Email:-** <br> 

**(III). git config --global --list:-** Check username and email.<br>
<pre> git config --global --list <br> Or <br> git config user.name <br> git config user.email </pre>

**4️⃣ Set Username for a Single Project (Local):-** <br>

**(IV). git config user.name:-**  Sets username for Single Repository.<br>
<pre> git config user.name "Project User" </pre>

**5️⃣ Set Email for a Single Project (Local):-** <br>

**(V). git config user.email:-** <br>
<pre> git config user.email "projectemail@gmail.com" </pre>
