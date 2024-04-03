giversion control is a tool that allow you to keep track of all changes in the project      

git commands

nb any folder or file that start with a dot it means it hidden

to configure git
$ git config --global user.name "Alexander Mfoniso"

$ git config --global user.email "alexandermfoniso18@gmail.com"

 git config --list

to view all folders in your document folder
navigate to your document path and type ls

to view hidden file
type ls -la

to create a folder on a particular directory type mkdir and the name of the folder
mkdir html demo

to swicth to a folder in a dicrectory
cd html-demo

to make ur project git enable or to star
git init

to clear your terminal
clear

to creat a file
vi index.html

to start typing 
i

to exist typing mode
press the Esc button

to save and quit
:wq

to check which mode ur file are in or ur stage 
git status

to move a file from a working director to a staging area
git add index.html

to add every file in ur folder 
git add .

to move to a local repository
git commit -m"this should contain ur message"

to move to a remote repository
git push
	
to see ur git commit u made
git log


 to format ur log message
git log --oneline

to view the last 2 commit
git log -n 2

to view ur last 2 commit in a formatted way
git log --oneline -n 2

to view more statstics on ur log
git log --stat

to navigate in ur screen when it has gone beyong d screen
u use "F" and "b" respectively

to use help in ur git
git help


to use help in ur git concerning a particular command
git help log

to view ur commit in graph form
git log --graph 



regular expression in git
git log --grep="string"
the string will act like the word u are looking for in ur commit message


to search based on author
git log --author="Alexander Mfoniso"

to search based on date
git log --since="date"

git log --until="date"
nb. since will  bring out all the date after d date and vice versa


to see the current changes made to ur file
git diff

to see a  a different between ur staging area and ur local repository
git diff --staged
nb. u will av to add ur file to  ur staging area first b4 running the above command

to delete a file
git rm contact.html
nb. contact.html should be ur file name

to rename an existing file in git

git mv about-us.html about.html
nb. take note of ur file name

ignoring file in git
to ignore a file o avto first of all create a file in ur folder called .gitignore  then add d file u want to ignore 
nb.before u ignore a file u must first add it in ur .gitignore b4 creating it

to ignore all file in ur folder
e.g *target/
nb target is d name of ur folder


to comment in ur .gitignore u use #



branch
to creete a new branch
git branch "name" 

to switch to d branch
git checkout yellow-website

to create and switch to d same branch
 git checkout -b "pink-website"

 to go back to the master
 git checkout master



git arictectture

1:working dicrectoty: this is ur project folder or a workbench.

2: staging area: it like a drafting space 

3:local repository: this is where we record all our changes											                         
