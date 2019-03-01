# Intructions to use git
 - `git pull` before starting anywork *To make sure everything is in sync*
 - `git push` to push your work
 - To commit your work
 	```
 	git add .
 	git commit -m "message"
 	git push --all
 	``` 
 - `git push mayank:master` To push the work to master
 - `git checkout <branch_name>` To change the branch
 - To set the username of github
   `git config --global user.email "email@email.com" `
   `git config --global user.name "unname"` 
 - To set the proxy
   `git config --global http.proxy http://proxyuser:proxypwd@proxy.server.com:8080` 
   To unset the proxy
   `git config --global --unset http.proxy`
