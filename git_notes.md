23/06/2015
## GIT


If want to go back to a commit throwing away our last chages:
git reset --hard

The hystory keeps there forever. So take care with what you commit
If we accidently commit something private (e.g. a password), google for a solution..

REMOTES
All folder that are not on the current .git space. Could be a url (github), but also another folder in our computer
With a remote, we can:
 Send things from our current folder: git push
 Update our folder with the remote commetn: git pull

********************************************************************
To create an empty repo: do not click on add LICENSE nor README!!
********************************************************************

* Create link with github empty repo (inctruction also given by github)
git remote add origin https://github.com/jcerezochem/summer_school.git
git remote -v # check the remote
git push origin master # send my local repo to githum. Github says to use -u (which is used to add upstream (tracking) reference

Some notes abut markdown

--------------------------------
# Header 1
## Header 2
- bullets
- another

1. item 1
1. numbering does not matter
--------------------------------


