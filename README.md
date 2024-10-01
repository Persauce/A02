Git, Webstorm, and Github all work together when it comes to the development process and keeping information in the cloud. To start the development, follow these steps:

Download git bash [git](git-scm.com)
Download webstorm- [here](https://www.jetbrains.com/webstorm/promo/?msclkid=94a1f89af03c1a42146f9e61a173a41e&utm_source=bing&utm_medium=cpc&utm_campaign=AMER_en_US-EST_WebStorm_Branded&utm_term=webstorm&utm_content=webstorm)
Make an account on github
Make a new repository and click add a readme.md file
Open git bash
Type in ssh keygen and follow the steps to make a new ssh key
Navigate through the files to find the added .pub file and cat that file
Copy the key and open github
Go to keys and click add a new key
In the name add your host name in bash and paste the key in the contents
Now you can use git bash and github and webstorm
So now in github copy the ssh implementation of cloning and on git to git clone and paste 
Now open up the project folder and do “code .” and that will open up webstorm if its your default IDE
Now for example lets add a file test.py and add some code in it
Now that its saved(ctrl+s) go to git bash and put “git add .”
Now type in git commit -m “whatever” as whatever could be anything like “added test.py” 
Then do git push and now the code is in github :)

- Branch - Different version of the project, can use it to solve a singular problem then merge back to main
- Clone- Create a local copy of the repository that is being copied
- Commit- Records little changes made on code, like steps that can be traced
- Fetch- update the locally stored repository with the changes made on the repo on the cloud
- GIT- Version control system that tracts changes/versions of files
- Github- Open source cloud that anyone can store their projects/host websites publicly or privately, is utilized alongside with git
- Merge- Combine 2 branches (that have different contents) mainly a lower branch into a branch higher in the hierarchy
- Merge Conflict  - When two branches are branched off a certain branch and modify the same file but they are both trying to be merged as git will not know which files to keep
- Push- Update the cloud repo with the changes you made locally
- Pull- similar to fetch but it merges changes from cloud into the current branch
- Remote - Git remote is a bookmark for different repository, where someone can access and pull/push code
- Repository- Collection of files in one separate space, similar to a project 

References: [What does "git remote" mean? - Stack Overflow](https://stackoverflow.com/questions/20889346/what-does-git-remote-mean#:~:text=A%20remote%20in%20Git%20is%20basically)
