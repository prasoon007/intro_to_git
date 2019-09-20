THREE STAGES OF GIT

#working directory
all the files resides here


#staging area
store the files which git tracks for changes and are ready for commit


#.git repository
snapshots which are stored on our repository permanently


======================================================================

#adding files of certain file type

command:- git add *.html  //we can specify any format of file


#adding all files in a directory(including hidden files)

command:- git add . or git add -A (includes hidden files too)


#removing files from staging area

command:- git restore --staged "filename" 


#ignoring files

STEPS
1. create a file ".gitignore"
2. open it in text editor
3. whatever file you wanted to ignore just add the name of that file in .gitignore
4. add and commit the file for future refernce
5. done

======================================================================


INTRO TO GIT BRANCHING

#adding a branch

command:- git checkout -b "name of new branch" //and it automatically switched to new branch
command:- git branch //list all the branches

#changing a branch

command:- git checkout "branch name"

#merging a branch

#removing a branch






======================================================================