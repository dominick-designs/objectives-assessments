# Git assessment 

## Part 1: Ordering
### You need to create a new local git repository on your desktop named my-repo and create a README.md file in the repository. Order the git terminal commands accordingly.
**Example**: #1 — git command
___

Task                |       | Order
|------------------ |:-----:|---:  
___ cd ~            |       | 3     
___ cd Desktop      |       | 4
___ mkdir my-repo   |       | 2
___ touch README.md |       | 1

___
## Part 2: Short answer
### Provide the correct command for each scenario.
___

1) If you want to see your current path in the terminal, which command would you use? 

2) If you want to see a list of items in your current directory, which command would you use?

3) If you want to see a list of items in your current directory, including all invisible files, which command would you use?

4) If you want to remove a file named ```.git``` without being asked for confirmation, which command would you use?

5) If you want to view to contents of a file named README.md, which command would you use?

6) What are the general steps you would take in order to create a repository on GitHub in order to copy the URL of the repository and then link it with an existing locla repository?

___
## Part 3: Matching
### Proivde the correct corresponding letter to match the indicated task
**Example**: Question — A
___

Question         |             | Answer
|:---------------|:------------|:----
__ push to remote master branch| \| | |
__ tell git to STAGE a specific file | \| | 
__ tell git to STAGE a specific directory and everything in it | \| | 
__ commit to git with a message | \| |
__ create git repo on github and then add it as remote origin | \| |
__ check status of current git repository (will be blank if no repository linked)| \| |
__ remove remote repository | \| |
__ initial push from local machine to remote GitHub | \| |
__ view a log of git actions | \| |
__ view current tags | \| |
__ add a simpe tag a shaw | \| |
__ initial push to remote git repository | \| |
__ make a push that is not the initial push | \| |

#### Answer Bank: 

|Choose the Correct answer          |        |Add letter to correct answer above|
|:---                               |:---    |:---                               |
A: &nbsp; &nbsp; ```git remote -v```|        | B: &nbsp; &nbsp; ```git push -u origin master``` |
C: &nbsp; &nbsp; ```git add src/```|         | D: &nbsp; &nbsp; ```git push origin``` | 
  E: &nbsp; &nbsp; ```git push origin```|    | F: &nbsp; &nbsp; ```git tag``` ||
  G: &nbsp; &nbsp; ```git add .gitignore```| |H: &nbsp; &nbsp; ```git add src/```||
  I: &nbsp; &nbsp; ```git commit -m 'message in single quotes'```|  |J: &nbsp; &nbsp; ```git remote add origin https://github.com/github-user/name-of-repo.git```||
  K: &nbsp; &nbsp; ```git push origin```|   |L: &nbsp; &nbsp; ```git remote remove origin```||
  M: &nbsp; &nbsp; ```git push -u origin master```| |N: &nbsp; &nbsp; ```git log```||
  O: &nbsp; &nbsp; ```git tag tagname-without-quotes```



___
## Part 4: Ordering
### You need to create a new local repository and link it with your new GitHub repository. Order the git terminal commands accordingly.
**Example**: #1 — git command

___ git add .

___ git init

___ git tag '001-initial commit'

___ git push -u origin master

___ git commit -m 'initial commit'

___ git remote add origin https://github.com/github-user/name-of-repo.git

___
## Bonus: Short Answer
### Provide a complete response to the following.

1) Given the following ```./style.css``` what does the ```./``` indicate? 
2) Given the following ```npm install prettier -D```, what does ```-D``` meand?