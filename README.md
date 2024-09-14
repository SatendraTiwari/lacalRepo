# loacalRepo

1. craete a repo on github 
2. clone the repo on local machine
3. git clone <link of repo> ":: https://github.com/SatendraTiwari/gitDemobyApnaCollage.git
4. check the git status > git status
5. Untracked files:
  (use "git add <file>..." to include in what will be committed)
        indxe.html
6.  type of status > untracked , modified, staged, unmodified
7.  git add a file by using : git add <file Name>
8.  git status > now the file is staged
9.  git commit -m "message" > commit the file
10. git log > check the commit history
11. git branch > check the branch
12. git push is  upload local repo to remote repo : git push origin main
13. mkdir is a create a folder by usin terminal > mkdir newfodlerName 
14. git init 
15. git remote add origin <link of repo> ":: https://github.com/SatendraT is a set a  origin 
16. git remote -v > check the remote repo origin 
17. git branch -m <BranchName> > rename the branch
18. git branch -d <BranchName> > delete the branch//
19. git checkout <BranchName> > switch to the branch//
20. git merge <BranchName> > merge the branch//
21. git push --set-upstream origin main

22. workflow on github {
    1. create a new repo on github
    2. clone the repo on local machine
    3. create a new branch checkout 
    4. make changes in the branch
    5. commit the changes
    6. push the changes to remote 
    optional
    7. create a pull request
    8. merge the pull request
}
BranchName
23. branch command {
    1. git branch <branchname> > create a new branch
    2. git branch > list all the branch
    3. git branch -b <BranchName> > to create a  the new branch -b : banana hai es branch ko jishaka name <demo> hai 
    3. git branch -d <BranchName> > delete the branch {
        1. yadi ham us branch ke aander hai jis branch ko delete karna hai to ham esh nahi kar sakte 
        2. ush branch ko delete karne ke liye ush branch se bahar aana hoga 
        3. git checkout <BranchName>
        4. terminal massage : Deleted branch festurel2 (was 65fa7b1).

    }
    4. git chechout <BranchName> is check to other branch this repo : terminal massage > Switched to branch 'main' Your branch is up to date with 'origin/main'.
    5. git push origin <BranchName> : yadi ham koi bhi branch ko banate hai to hame ush ko public ya github par show kare ke liye yha commnad chalni padti hai 
    6. Merge the two branch {
        1. git branch > checked a number of branch
        2. compeare to  brach : git diff <BranchName>
        3.git merge <BranchName> merge two brach 
        4. in the gitHub (remote) to any type of changes so you can changes your Loacal Code(file) so you can use the >>>> Git pull, command 
        problam of merge : Merge Conficts Resolving : Merge Conficts is a probla of Marge two and more brach and changes a evary brach is a same position > resolve {
            > git merge main
                Auto-merging index.html
                CONFLICT (content): Merge conflict in index.html
                Automatic merge failed; fix conflicts and then commit the result.
            > 
<<<<<<< HEAD
    <h2>this is festurel 1 branch(deopDown)</h2>
=======
    <h2>this is festurel 1 branch(button)</h2>
>>>>>>> main
        
         

         1. Accept Current Change > accept current change is a accept a current changes in file like chnage in the festurel barnch 
         2. Accept Incoming Change > accept incoming change is a accept a incoming change in file like
         3. Accept Both Change > accept both change is a accept a both change in file like
         4.
        }
    }
    7. pull Request {
<<<<<<< HEAD
        1. git pull <is a pull request >
    }

    8. check the a numebr of commit by usin this command > git log

=======
        1. 
    }

>>>>>>> b6b67ba73b7e4be4f7a2d281c9d2620faa3c0631

}