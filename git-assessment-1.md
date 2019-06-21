# Git assessment 

## Part 1: Ordering
### You need to create a new local git repository on your desktop named my-repo and create a README.md file in the repository. Order the git terminal commands accordingly.
___

__ cd ~

__ cd Desktop

__ mkdir my-repo

__ touch README.md

___
## Part 2: Short answer
### Provide the correct command for each scenario.
___

1) If you want to see your current path in the terminal, which command would you use? 


2) If you want to see a list of items in your current directory, which command would you use?
```ls```

1) If you want to see a list of items in your current directory, including all invisible files, which command would you use?
```ls -la```

1) If you want to remove a file named ```.git``` without being asked for confirmation, which command would you use?
```rm -rf .git```


1) If you want to view to contents of a file named README.md, which command would you use?
```cat package.json``` or ```vim package.json```

1) What are the general steps you would take in order to create a repository on GitHub in order to copy the URL of the repository and then link it with an existing locla repository?

___
## Part 3: Matching
### Proivde the correct corresponding letter to match the indicated task
___

__ push to remote master branch ```git push origin```

__ tell git to STAGE a specific file ```git add .gitignore```

__ tell git to STAGE a specific directory and everything in it ```git add src/```

__ commeit to git with a message ```git commit -m 'message in single quotes'```
 
__ create git repo on github
```git remote add origin https://github.com/dominick-designs/react-project.git```
```git remote -v```
to check status of this
```git remote remove origin```
to remove git
```git remote -v```
to check it's removed



git init
git status
git add .
git commit -m 'initial commit'
git tag '001-initial commit'



```git add banana https://github.com/dominick-designs/react-project.git```
```git remove -v```
```git push -u origin master```
to push to github.
```origin```
can be any name. does not have to be 'origin'

```git log```
and then  
```git tag tagname-without-quotes```
to tag a shaw
```git tag```
to see tag


```./style.css```
 './' means 'relative to this file look there


```git add src/index.html```
```git commit -m 'single-quote-message'```
```git push origin```


```npm install prettier -D```
saves it as a developer dependency

Dominick Inglese [1:38 PM]
 ```git add .```