# GIT Notes 

# Installation of Git :- 
1. Download git from https://git-scm.com/downloads 
2. Install git by default default setting only (You have to do next next only)
3. To verify if git is installed or not. Open terminal for linux / Mac or cmd for Windows. and type
git --version

# Creating account over github :- 
1. Go to https://www.github.com/
2. Sign up and create your account.

# Creating a Repo :- 
1. Click on create repo or New button.
2. Write your repo name.
3. Click on create Repository.

# Making project in git :- 
1. Go to your terminal or cmd.
2. Intialize the git
git init
3. Configure the user.
git config --global user.name "user name"
git config --global user.email "email"

Note:- If you are using the same user next time so you can jump to 4th point skipping 3rd.
Note:- If you don't want to write two lines. 
git config --global -edit


4. Add the remote git origin / Add your repo.
git remote add origin https://github.com/vinaypatel1437/w3Schools.git

5. Add all the changes to stage. To tell the git that this are the changes we have to commit.
git add .
If you want to push all the files you have to write . else write the file name.
Note:- If you are creating repo first time than you all to push all the files.

6. Commit all the changes to current branch.
git commit -m "Message"

7. Push all the changes to the current branch.
git push origin master


# Pushing the New changes to current repo
1. Stage all the changes.
git add .

2. Commit all the changes.
git commit -m "Changed readme.md"

3. pushing all the changes.
git push origin master


# Creating github pages :-
1. Go to your github repository.
Requirements :- 
a. You should have only one index.html file in root of the folder.

2. Go to settings.
3. Open the Pages tab from left sidebar.
4. Select option as Deploy from branch
5. Select your branch as master/ main 
6. Click on save button.
7. Wait for 5 min.
8. Refresh the page and click on Visit Site.


# Getting the repository changes to local system.
1. Pull from repo.
git pull origin master

