# 5 Things I have learned about Git and GitHub
1. Git Workflow
    - working directory 
    - staging area
    - local repository
    - remote repository
2. Connect local and remote repository 
    - use command for connecting
    - clone through https / ssh url for connecting
3. Undo git workflow
    - undo from working directory ('git checkout -- <FileName>')
    - undo from staging area ('git reset head <FileName>')
    - undo from staging and unstaging area ('git reset --hard head')
    - undo from local repo to staging area ('git reset --soft head^')
    - undo from local repo to unstaging area ('git reset head^')
    - undo from local repo to previous commit ('git reset --hard head^')
4. Collaboration 
    - firstly for collaboration clone remote repository 
    - secondly locally add mandatory file and make commit
    - then create pull request
5. Contribution
    - firstly fork anyone remote / github repository
    - secondly clone from your github reository
    - thirdly locally add required changes / file and make commit
    - then create pull request
# Adding 2 more things I have learnt
1. Branching & Merging
    - for creating branch use this command 'git branch BranchName'
    - for merging use this command 'git merge BranchName'
2. Merge conflict resolves on git and github
    - after resolves conflict add & make a commit before push remote repository
