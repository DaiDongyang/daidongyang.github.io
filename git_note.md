#Git Note
## Ignore Some Files
+ vim .gitignore
+ git rm -r --cached .
+ git add .
+ git commit -m "ignore some files"

## Merge
###If you are in dev branch.
+ merge local master
	+ git merge master

+ git pull origin master
	+ this command will merge dev with origin/master automatically! 
	+ So it is very importanct to look out which branch your are in when pulling!