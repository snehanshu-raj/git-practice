## Initialise
1. open terminal/git bash here where you want your repo.
2. do **git init**.
3. do **ls -a** to view the _.git_ folder.
## Get the repository
```
git clone _url_
```
or
```
git init
git remote add _url_
git pull origin _branch_name_
```
## Make changes and commits
```
git pull 
```
If you are trying to pull but made changes to some file then it will first ask you commit your changes and abort the pull, if its a new file not present there in the branch then it will pull it sucessfully.
```
git status
git add file_name _or_ git add .
git commit -m "message"
git push
```


