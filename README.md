### Commands used
###### Initiated the folder to git
>git init
###### Put up a password file and put it in .gitignore
>echo "*************" > password.txt  
>echo password.txt > .gitignore  
###### Staged all files, looked at which was files were changed and then commited.
>git add .  
>git status  
>git commit -m "First commit"  
###### Upploaded to Github.
>git remote add origin https://github.com/Matojotam/Workshop-1.git  
>git branch -M main  
>git push -u origin main  
###### new files into my git repository
>echo "My file after uploading to Github" > Notes.txt  
>echo "Another file to upload" > "More notes.txt"  
###### Adding just 1 file to staging, then all of them
>git add Notes.txt  
>git add .
###### Commiting to repository and uploading to Github
>git commit -m "Added txt files and README.md  
>git push  
>
###### Cloned a repository, then uploaded to my own profile and checked so it pointed towards my profile.
>git clone https://github.com/Lexicon-Smaland/Hello-World  
>git remote set-url origin https://github.com/Matojotam/Workshop-1-2  
>git remote -v
>
###### Pushed changes in README.md to github.
>git push  
###### Branching from Main
>git switch -c Task-1-3  
###### Add branch to github
>git push --set-upstream origin Task-1-3  
###### Switched back to Main branch and merged them
>git switch main  
>git pull
>git merge Task-1-3
>git push
>
>