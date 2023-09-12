**My-1st-Git-project**

Git repository: is a single collection of documents where you want to track modifications. Offline/online.

GitHub: collections of different repositories that you want version control. Online.

command to create the empty timeline: git init (to generate .git file)

git commit -m "meaningful message"

why? how? effect? limitations? - be descriptive!!



**Conceptual areas:**

- Developing area - the folder where the project is developed - it is in your computer locally

- Staging area - Intermediate space to transfer from the developing area to your local repository.  Also locally in your computer locally.
  
  (location used to prepare new snapshots to the timeline)
  
  - why the staging is interesting: if several files are connected to check the correlated changes you can stage at the same time and commit them together

- Local repository - The repository where you keep your snapshots. It is found in the `.git` folder. Also locally in your computer locally.
  
  the history and tracking of all the changes (it is the .git file)
  
  P.S.: to check in what conceptual area my file are I can use `git status`

- Remote repository: Online repository linked to your local repository (works as a cloud-based backup for the local repository).  Represented by GitHub.
  
  .gitignore - List of files that should not be added to the repository
  
  README.txt - Detailed description of your project or tool usage
  
  `git remote add <name> <ssh>`to create bridge between local repository and GitHub
  
  `git push` to send to GitHub
  
  
  
  **VI editor - an alternative way to add commit**

i = to start insertion (writing)

when finished press <u>esc</u> to exit insertion mode

then type <u>:wq</u> and enter to save and quit (this should appear on the bottom of the page)

When comparing commits in the timeline we can do that with `git show` and `git dif` commands and we have to add the commit IDs that we want to compare. We can compare more than two as well. 



**How to collaborate with others? **

On Github, ask other people to collaborate in your project. 

 On git: 

- Make sure to work in the correct folder, not in one of your own folder!

- Clone the remote repository onto your own local computer using the git clone command and the SSH key. 

- Move into the cloned folder to proceed working into it. 



**Branches**

creating: `git branch <name_of_newbranch>`

switching: `git checkout <name_of_the_branch>`

Checking for new branch I need to pull: git fetch
