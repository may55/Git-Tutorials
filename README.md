# Intructions to use git
 - Before starting anywork *To make sure everything is in sync*<br/>
   `git pull`

 - To push your work <br/>
   `git push`<br/>
   `git push origin <branch>`

 - To commit your work
   ```
   git add .
   git commit -m "message"
   git push --all
   ```
 - To push the work to master<br/>
   `git push`<br/>
   `git push origin <branch>` <br/>
   `git push origin mayank:master` 

 - To change the branch<br/>
   `git checkout <branch_name>` 
 - To set the username of github<br/>
   ```
   git config --global user.email "email@email.com" 
   git config --global user.name "unname" 
   ```
 - To set the proxy<br/>
   `git config --global http.proxy http://proxyuser:proxypwd@proxy.server.com:8080` <br/>
   To unset the proxy<br/>
   `git config --global --unset http.proxy`

 - To handle the conflicts<br/>
   `git checkout --thiers .`<br/>
   `git checkout --ours .`
 
 - To add user credentials
   `git config --global credential.https://github.com.username <your_username>`

- To make an existing directory a git repo<br/>
   `git init`

 - To host an existing directory on GitHub<br/>
   ```
   git init
   git add -A
   git commit -m''
   git remote add original <url>
   git pull <url> master --allow-unrelated-histories
   git push --set-upstream origin master  
   ```
- To check status of working tree<br/>
   `git status`