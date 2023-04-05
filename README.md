# git-instructions
Instructions for using github from my local machine via command line
1. make certain you have configured git with email and user name  
  a. `git config --global user.email "samantha.roberts@gmail.com"`  
  b. `git config --global user.name "srobertsphd"`  
2. after creating a repository on github, copy the url  
3. `git remote add origin https://github.com/srobertsphd/jovian-assignment-2-responsive.git`
4. `git init`
5. `git add .`
6. `git commit -m "assignment-2"`
7. `git push --set-upstream origin master`  


with the push statement you will be prompted for login name and password  
There is not password access via command line anymore, so you will need to generate a tokenn on the website.  

Instructions for token generations:  
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token  

1. Upper right corner click profile image  
2. left sidebar click Developer Settings
3. Under Personal access tokens click Tokens (classic)
4. Select generate token (classic)
5. give name and expiration
6. check "repo"
7. click generate and copy the code

