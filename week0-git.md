1) I can add files with certain extension using git add '*.<extension_name>'
2) I can add a 'tunnel' to existing repository using git remote add origin https://github.com/<user_name>/<repo_name>.git
3) I can publish my changes to a certain branch of repo with git push <options> origin <branch_name>
3.1) git push -u origin master will push my changes to branch master and remember my credentials because of the -u option
4) I can take all the changes made on a certain branch by other repository collaborators with git pull origin <branch_name>
5) git diff --staged
6) git reset octofamily/octodog.txt
7) I can reset file back to it origin with git checkout <file_name>
8) I can remove files from repository and stage(put this into git history) it bwith git rm <file_name>
9) I can merge two branches with git merge <name_of_the_branch_i_want_to_merge> . Note: if i want to merge branch my_branch into branch master
i need to perform git merge my_branch located on master branch
10) 
