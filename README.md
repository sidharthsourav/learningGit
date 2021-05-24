# learningGit

Test trial for learning git.

## steps to use git of your own
1. first clone the repo using ssh as it will help you in minimizing loging time if you are using only a single machine.
2. second write code .
3. third use [ git add .] for update and add all files at once or use [ git add "file name" ] to add specific file.   
4. fourth check status if any file is red add it first.
5. fifth [git commit -m " message why are you commiting" -m "description"] second -m is optional.
6. finally [git push] and use the phrase entered while ssh key generation.
7. Note* the phrase is sourav.

## Repo started locally
* if the repo is locally move into th folder then [git init].
* Do the steps till commit but you can not push it it will shiow fatal error. to resolve this create a empty repository on github as same name as locally stored code folder.
* copy the ssh link and finally use [git remote add origin "ssh link"] after this you can check via git remote -v or directly try to push. the code it will work fine. for pushing the first time you have to use [ git push -u origin master ] after that normal git push will work.
