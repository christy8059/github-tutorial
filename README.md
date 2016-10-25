# GitHub Tutorial

_by Christy Li_

---
## Git vs. GitHub
_Git_ is a version control that keeps "snapshots" of your code, while _Github_ stores your code in the cloud. Since the code is stored on the cloud we are able to visually track changes. Also we're able to collaborate on the same project.   
* The difference is that _Git_ does not require github, but _github_ requires git.  

---

## Initial Setup  
**_Making a Github account_**   
If you already have a github account you may skip steps 1-3    
1. To make an account you need to go to [github.com](https://github.com/)  
2. Then you press on the green button that says "sign up". ![](sign_up_button.png)  
3. Then it redirects you to a page where you can type in a user name, email and password.   


**_Creating an SSH key between Github and C9_**  
NOTE: These steps are only done ONCE after you make your _Github account_. 

1. Go to the top right, and press on your profile icon   ![](profile_icon.png)   
2. Then press setting  
3. On the left there are different options. Press "SSH and GPG keys" which is the sixth one counting from the top. ![](new_SSH.png)   
4. Then you name it cloud9 for the title section.  
5. Then to get the SSH Key you would have to go back to your cloud9 tab (the page where you choose which workspace to open).  ![](C9_workspace_page.png)  
6. On the top right, press the gear icon. After you press that you should see "SSH Key" on the left.  
7. Copy everything that is in that gray box, and then go back to github and paste everything on the section that says Key. ![](SSH_key.png)    
8. Then press add SSH Key.  
9. To check if it works you can open to your workspace and in the terminal type "ssh -T git@github.com". If it works "Hi <your username>! You've successfully authenticated, but GitHub does not provide shell access._" should appear as a repsonse.  

---
## Repository Setup 
_To make a repository on C9_   
1. Open your terminal and double check if your in your workspace.    
2. Then in the terminal type `mkdir` (make directory) to make a new repo.   
3. Then `cd` (change directory) into the folder that.   
4. After you make the folder you can create a file using `touch.txt`.  
5. To open the file you can type `c9` with the file name and you can type in the file.   
6. After you make your changes you would want to add to your workspace by typing `add .`.   
7. After you add to the staging are you would want to commit it. To commit it you would type `commit -m "message"`. (The -m just means message)  
8. After commiting you push it to github using `git push`, but since you're not connected to your github you would have to connect it first. (only if you made a repo on Github already)  
9. To connect them you would type `git remote add origin git@github.com:christy8059/nameofrepo.git` and then
`git push -u origin master`    
10. Afterwards you can go back to your shell and type `git push`, and it will push it to github. 

_To make a repository on Github_  
1. On the home page of github you will see a green button that says "new repository"  ![](new_repository.png)  
2. Then you give it a name that is the same as the one you put for cloud9. For example: if its "first-repo" on cloud9, you would put "first-repo" on github.

---
## Workflow & Commands
Tips-   
1. if you are lost and not sure if you add/commited your work you can also use `git status`. If its red it means its not commited or added, and if its green that means its added or commited.  
2. To keep track of your work you should add (which means to take a snap shot and add it to your staging area). After adding you would want to commit (take the picture) and add a message. 
3. After commiting you would want to push it to github. Which on github it keeps track of your changes.    

_These steps should be done as frequently as possible_ 