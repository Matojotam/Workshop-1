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
###### Adding just 1 file to staging,l then all of them
>git add Notes.txt
>git add .
###### Commiting to repository and uploading to Github
>git commit -m "Added txt files and README.md
>git push
>
>
>
>
>
>