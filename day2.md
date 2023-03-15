#### 1. <mark>Creating Git Folder</mark><br /><br />
    cd Desktop/
    mkdir Exercises Play

* Now that we are in the correct directory. We can start by initializing Git!

#### 2. <mark>Initialize Git</mark><br /><br />
    git init 

* <u>Note</u>: Git now knows that it should watch the folder you initiated it on.
* Git creates a hidden folder to keep track of changes.

#### 3. <mark>Configure Git</mark><br />
*   Now let Git know who you are. <br />

        git config --global user.name userName
        git config --global user.email userEmail       


#### 4. <mark>Creat Note</mark><br /><br />
    touch day.md
    code day.md
#### 5. <mark>Check The Status</mark><br /><br />
     git status

 * Now Git is aware of the file, but has not added it to our repository!

* Files in your Git repository folder can be in one of 2 states:<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>Tracked</u> - files that Git knows about and are added to the repository
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>Untracked</u> - files that are in your working directory, but not added to the repository

* When you first add files to an empty repository, they are all untracked. To get Git to track them, you need to stage them, or add them to the staging environment.

* Staged files are files that are ready to be committed to the repository you are working on. 
So we can add it to the Staging Environment:<br />

        git add .

* Untracked files are files that have been created within your repo's working directory but have not yet been added to the repository's tracking index using the git add command.This is the state of new files you add to your repository. That basically means Git is aware the file exists, but still hasn't saved it in its internal database

#### 6. <mark>Check The Status</mark><br /><br />
     git commit -m 'First time Commit'
* When we commit, we should always include a message.

* By adding clear messages to each commit, it is easy for yourself (and others) to see what has changed and when.

* The commit command performs a commit, and the -m "message" adds a message.

#### 7. <mark>Git Commit Log</mark><br /><br />
     git commit log

* To view the history of commits for a repository, you can use the log command:


#### 8. <mark>Create Repository On GitHub</mark><br /><br />

#### 9. <mark>Add the Repo Link</mark><br /><br />
     git remote add origin url

#### 10. <mark>Push it to GitHub</mark><br /><br />
     git push -u origin master
     