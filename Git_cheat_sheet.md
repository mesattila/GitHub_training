**Manual of git commands**

1. How to initialize it (create the staging area and local repository)
   
   `git init`

2. How to send it to staging area
   
   `git add <file_name>`
   
   Multiple files can be sent to the staging area at the same time (the commit will be also done on multiple files at the same time)
   
   How to use it cleverly? Use git status to check before you commit 
   
   `git add <file1><file2>`
   
   `git commit -m "message that expresses something for both files"`

3. How to commit (send to the local repository)
   
   `git commit -m "Meaningful message"`
   
   `git commit`-  it will pop up in an editor and the commit can be made there  (vi editor is the default)
   
   **VI editor - an alternative way to add commit**
   
   i = to start insertion (writing)
   
   when finished press <u>esc</u> to exit insertion mode
   
   then type <u>:wq</u> and enter to save and quit (this should appear on the bottom of the page)

4. How to check in what conceptual areas my files are
   
   `git status`
   
   P.S.: Uncommitted, Unstaged, Untracked files

5. How to get the history:
   
   `git log`
   
   `git log --help`
   
   `git log -n 2`
   
   `git log --abbrev-commit`

6. How to compare versions of the same file:
   
   `git show <commit ID1> <commit ID2>`
   
   `git diff <commit ID1> <commit ID2>`

        commit ID can be obtained from the `git log` 

7. How to create and use a link between a local and remote repository:
   
   - create a link (bridge): `git remote add <name4link> <ssh>`
     
     name4link is usually the same name as the name of my repository. It is just a nem for the link that is being created. Hence, it could be also a different name. 
   
   - send data via the link: `git push`

8. How to update from the remote to the local:
   
   `git pull`


