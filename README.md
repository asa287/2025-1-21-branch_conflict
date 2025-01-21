# 2025-1-21-branch_conflict

`git switch -c <branch name>`: Switched to a new branch 'bash_script_1' in one command


- `code script.sh`: creat a file named script.sh and open the file in vscode
- `bash script.sh`: run the commends in this type of file, the output shows up on the terminal panel

In the process of rebase, merge command is done as well

git switch main
git pull
git switch b2
git rebase main
(now the conflict shown in the vscode, edit the file and save)
git rebase --continue