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

 

  **VI editor - an alternative way to add commit**

i = to start insertion (writing)

when finished press <u>esc</u> to exit insertion mode

then type <u>:wq</u> and enter to save and quit (this should appear on the bottom of the page)
