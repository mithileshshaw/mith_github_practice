# mith_github_practice
This is first github learning session and exploring command

command:
git --version

git clone https://github.com/mithileshshaw/mith_github_practice.git
git status

git config --global user.name "mithilesh shaw"
git config --global user.email "mithiles9shaw@gmail.com"
git config --list   #check git configured details

4 types of status :-
1. untracked -- new file that git doesn't yet track
2. modified -- changed
3. staged -- add # status becomed staged file is ready to committed
4. unmodified -- commit # unchanged


ADD and Commit :-

1.  git add <-filename-> or git add . -- to add multiple file
        # add -- adds new or changed files in your working directory to the Git staging area
        
2. git commit -m "some message
        # commit - it is the record of change
3. git push origin main -- push the changes form GIT system to GIT Repository. Here origin is self decrlared or nick name to the repo we are using
        

PUSH :-
git push origin main 


INIT Command:
git init
git remote add orgin https://github.com/mithileshshaw/mith_github_practice_localrepo.git
git remote -v
git branch
git branch -M main : for renaming the branch
git push origin main or git push -u origin main : -u set to push by default to origin
