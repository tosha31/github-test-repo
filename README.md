# Demo

Some description...

Some more description...

## git navigation and commands

ls -la //show hidden folders from terminal

git status // show all files that were updated created or deleted but have not been saved into git

git add<file> ex // git add index.html this adds updated of new files to be tracked by git

git add . // tells git to track all files

git commit -m "commit message, changed readme, added index" // also git commit -m "commit message" -m "description"

git remote add origin <remote repository URL> //add url of remote repo you want to push to

git remote -v ///set the remote

git push origin master ///finally push changed to the remote repo

//If you do not have your git linked then link with ssh
ssh-keygen -t rsa 4096 -C "email@domain.com" // generate ssh for git connection
// there will be a private and publice or .pub key generated, .pub is for github
cat testkey.pub // this will print your public key to copy (assuming you named your key testkey)
