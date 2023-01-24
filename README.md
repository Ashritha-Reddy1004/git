
## GIT COMMANDS ##


**How to check your Git configuration:**
* The command below returns a list of information about your git configuration including user name and email:

      $ git config -l

**How to setup your Git username:**

* With the command below you can configure your user name:

      $ git config --global user.name "name"

**How to setup your Git user email:**

* This command lets you setup the user email address you'll use in your commits.

      
      $ git config --global user.email "email.com"

**How to cache your login credentials in Git:**

* You can store login credentials in the cache so you don't have to type them in each time. Just use this command:

      $ git config --global credential.helper cache
**How to initialize a Git repo:1**

* The first step is to initialize a new Git repo locally in your project root. You can do so with the command below:

      $ git init
**How to add a file to the staging area in Git:**

* The command below will add a file to the staging area. Just replace filename_here with the name of the file you want to add to the staging area.

      $ git add filename_here

**How to add all files in the staging area in Git**
 * If you want to add all files in your project to the staging area, you can use a wildcard . and every file will be added for you.

      $ git add .


**How to add only certain files to the staging area in Git**

 * With the asterisk in the command below, you can add all files starting with 'fil' in the staging area.

       $ git add fil*

**How to check a repository's status in Git:**

* This command will show the status of the current repository including staged, unstaged, and untracked files.

        $ git status

**How to commit changes in the editor in Git:**

* This command will open a text editor in the terminal where you can write a full commit message.A commit message is made up of a short summary of changes, an empty line, and a full description of the changes after it.

      $ git commit

    
**How to commit changes with a message in Git:**

* You can add a commit message without opening the editor. This command lets you only specify a short summary for your commit message.

      $ git commit -m "your commit message here"

**How to commit changes (and skip the staging area) in Git:**
* You can add and commit tracked files with a single command by using the -a and -m options.

       $ git commit -a -m"your commit message here"
**How to see your commit history in Git:**

* This command shows the commit history for the current repository:

      $ git log
**How to see your commit history including changes in Git:**

This command shows the commit's history including all files and their changes:

       $ git log -p
**How to see a specific commit in Git:**

* This command shows a specific commit.

* Replace commit-id with the id of the commit that you find in the commit log after the word commit.

      $ git show commit-id

**How to see log stats in Git:**

* This command will cause the Git log to show some statistics about the changes in each commit, including line(s) changed and file names.

       $ git log --stat

**How to see changes made before committing them using "diff" in Git:
You can pass a file as a parameter to only see changes on a specific file.**

* git diff shows only unstaged changes by default.

* We can call diff with the --staged flag to see any staged changes.

       $ git diff
       $ git diff all_checks.py
       $ git diff --staged
**How to see changes using "git add -p":**

* This command opens a prompt and asks if you want to stage changes or not, and includes other options.

        $ git add -p

**How to remove tracked files from the current working tree in Git:**

* This command expects a commit message to explain why the file was deleted.

      $ git rm filename


