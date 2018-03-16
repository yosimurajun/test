# how to use git hub 
1.  sing up github
2.  profile
3. google search 'github download for your OS' and install
4. repository create
  - new click >> repository name  >> create repository
  - turnel command 
    * git init 
    * git status
    * position : git remote add origin https://github.com/username/repository name.git
 5. file upload
  - git add filename
 6. please who you are 
  - git commit - m "test"(init)
    * git config --global user.email "XXXXXX"
    * git config --global user.name "XXXXXX"
    * after : git commit - m "test"
   
 7. push 
   - git push u origin master
 8. sources manage & new branch 
   - git commit -m "testest"
   - git push 
   - username : XXXXX
   - password : XXXXX
   
   - git checkout -b beta
      * checkout : enter
   - git push -u origin beta
   
 9. file merge
   - git checkout master
   - git merge beta 
      * beta data >> master file list 
   - git push 
   - username : XXXXX
   - password : XXXXX
   - 
