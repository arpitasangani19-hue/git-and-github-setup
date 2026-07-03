# git-and-github-setup
install git --https://git-scm.com/install/windows<br>
add your config into git<br>
open git bash into computer<br>
paste below CMD:<br>
git config --global --unset user.name<br>
git config --global --unset user.email<br>
git config --global user.name "arpitasangani19-hue"<br>
git config --global user.email "arpitasangani19@gmail.com"<br>
check your git config (paste below cmd into gitbash) <br>
git config --list <br>
check your email and username in given output <br>
create a project folder in computer (ex. news-website) <br>
join your folder with github <br>
go to github website (login first) <br>
create a new repo (chech for new btn into dashboard -green color btn) <br>
give a name to repo (ex. news-website) <br>
click button --> create a repo (green button) <br>
find the link that start with --> git remote add origin --> copy that whole line <br>
open your vs code --> open terminal(chech the menu click the option terminal) --> new terminal --> first check last words( ex. /news-website) <br>
paste the copy link (repo link) --> close the terminal <br>
create files, edit files, delete files into your folder now <br>
open terminal and give below cmd one by one: <br>
git add .<br>
git git commit -m "give a msg"
git push origin main (main --> branch name {check your working brach first and after tha t write the branch name})
repeat the cycle
edit files --> git add . --> git commit -m "give a msg" --> git push origin main --> edit files
# Git Development Workflow

This project follows a standard iterative Git workflow. Use the guide below to track, commit, and push your changes.

---

## 🔄 The Cycle

Whenever you make changes to the project, repeat this 4-step loop:

1. **Edit** your files in your code editor.
2. **Stage** your changes.
3. **Commit** your changes locally with a descriptive message.
4. **Push** your changes to the remote repository.

```bash
# Step 1: Make your edits...

# Step 2: Stage all modified and new files
git add .

# Step 3: Commit the changes with a message
git commit -m "Your descriptive commit message"

# Step 4: Push to your current branch (e.g., main)
git push origin <branch-name>
