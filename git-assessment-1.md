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
 
__ create git repo on github and then add it as remote origin ```git remote add origin https://github.com/github-user/name-of-repo.git``` 

__ check status of current git repository (will be blank if no repository linked) ```git remote -v```

__ remove remote repository ```git remote remove origin```

__ initial push from local machine to remote GitHub ```git push -u origin master```

__ view a log of git actions ```git log```

__ view current tags ```git tag```

__ add a simpe tag a shaw ```git tag tagname-without-quotes```

__ initial push to remote git repository ```git push -u origin master```

__ make a push that is not the initial push ```git push origin```

___
## Part 4: Ordering
### You need to create a new local repository and link it with your new GitHub repository. Order the git terminal commands accordingly.

__ git init

__ git status

__ git add .

__ git commit -m 'initial commit'

__ git tag '001-initial commit'

__ git remote add origin https://github.com/github-user/name-of-repo.git

__ git push -u origin master

___
## Bonus: Short Answer
### Provide a complete response to the following.

1) Given the following ```./style.css``` what does the ```./``` indicate? './' means 'relative to this file look there
1) Given the following ```npm install prettier -D```, what does ```-D``` meand? saves it as a developer dependency
