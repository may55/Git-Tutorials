# Intructions to use git
 - `git pull` before starting anywork *To make sure everything is in sync*
 - `git push` to push your work
 - To commit your work
   ```
   git add .
   git commit -m "message"
   git push --all
   ```
 - To push the work to master
  `git push origin mayank:master` 
 - To change the branch
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
