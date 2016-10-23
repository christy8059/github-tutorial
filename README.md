# GitHub Tutorial

_by Christy Li_

---
## Git vs. GitHub
_Git_ is a version control that keeps "snapshots" of your code, while _Github_ stores your code in the cloud. Since the code is stored on the cloud we are able to visually track changes. Also we're able to collaborate on the same project.   
* The difference is that _Git_ does not require github, but _github_ requies git. 


---
## Initial Setup
**_Making a github account_**  
If you already have a github account you may skip steps 1-3  
1. To make an account you need to go to [github.com](https://github.com/)  
2. Then you press on the green button that says "sign up" 
3. And then you get to a page where you type into your user name, email and password  

**_Creating an SSH key between Github and C9_**  
NOTE: THESE STEPS ARE ONLY DONE ONCE AFTER YOU MAKE YOUR GITHUB ACCOUNT 

1. Go to the top right, and press on your profile icon ![profile icon](profile_icon.png)   
2. Then press setting  
3. On the left there are different options. Press "SSH and GPG keys" which is the sixth one counting from the top.  
4. Then you name it cloud9 for the title section.  
5. Then to get the SSH Key you would have to go back to your cloud9 tab (the page where you choose which workspace to open). 
6. On the top right, press the gear icon. After you press that you should see "SSH Key" on the left.  
7. Copy everything that is in that gray box, and then go back to github and paste everything on the section that says Key. 
8. Then press add SSH Key.  
9. To check if it works you can open to your workspace and in the terminal type "ssh -T git@github.com". If it works "Hi <your username>! You've successfully authenticated, but GitHub does not provide shell access._" should appear as a repsonse.  



---
## Repository Setup 
To make a repository on Github
1. on the home page of github you will see a green button that says "new repository"
2. Then you give it a name that is the same as the one you put for cloud9. For example: if its "first-repo" on cloud9, you would put "first-repo" on github. 


---
## Workflow & Commands