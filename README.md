Git --> allows to maintain the History of project (who did wt changes on which date)

 GitHub --> allows to host our git repository


Install git for windows

Open gitbash 
cd desktop
mkdir projectkunal
cd projectGit
git init(imp)
ls(empty)
ls -a(hidden files -- init)
touch names.txt(creates)
vi names.txt(type content to save esc - shift +: - x)
cat names.txt(display content)
git status(shows unsave names.txt)

To make a commit
--------------

touch surnames.txt
git add . (shows saves names.txt) to save all changes made
git add names.txt (to save only names.txt)
git commit -m "names.txt files added"

To undo 
------
git restore --staged names.txt(goes back to unsaved state)

To check number of commits
--------------------------
git log(all the commits made)(should commit for sure)

To make changes wait
--------------------

git stash (goes to unsaved state)
git stash pop(comes to saved state)
git stash clear(deletes the file)



To Collaborate with GitHub
------------------------


Open GitHub
create new repository named LearnGit and copy the url (https://github.com/sarayuCheganti/LearnGit)
In gitbash git remote add origin https://github.com/sarayuCheganti/LearnGit

git remote -v
git push origin master (check in GitHub under learnGit names.txt and wtever in the projectGit adds into GitHub)


To Work in someone's Project
-------------------------------


We cannot make changes to someones project so we need to fork it such that it copies in our account
once it copied we can do whatever changes we want

To clone it to our computer

git clone link(which is in code green button in repository)


Branches
-----------

Imp: Donot commit to main branch that is considered as default

to create new branch -- git branch feature
to makeit as head -- git checkout feature

head is a pointer to branch where we are working on




