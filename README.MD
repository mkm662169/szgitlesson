#Introduction to GIT

1. Git: Software Code management (SCM)

2. Has a .git folder that holds the versions of the software like a database.

3. Repo: the organisational unit of a program or software library and you can combine git repo into larger project. Repos also use the org unit of code that is tested.

4. Think of git like a tree and that branches are like copies of the tree. The git repo has a trunk that we call master and that the branches are copies of the source in various states of completion.

5. Master: generally considered the production release/version of the software. You need to create a branch called development that is the working copy of the software that is currently being developed. Master is the copy that your users use and development is the copy that your developers use.

6. Git has a dance called "Git Flow".
   Step0: Make sure you have a git repo made or cloned
   Step 1: WHen you goto work on a feature, bug, or task, make a branch
   Step 2: Each working piece of code and/or test/action should have a commit tagged with Fix, Feature, or Task depending on what you are doing. Also, when you have project management system, you should include ticket number in the commit so that the commit can be tracked  to the original request from the project manager/PMS.
   Step 3: When your code is done, you nedd to merge development or master into your branch and check that your program still works. If it works then you should push it to github/central repo. Then someone will make a pull request and then the branch you created in step 1 will be merged usually into the development branch, unless your merging the development branch into master to send the software to the end users.

7. Terms:
        1. GIT - SCM
	2. Repo: Main org unit for program or library
	3. Branch: Copy of the program, makes copy from whatever branch you are on when you run the command git checkout -b <nameofbranch>
	4. Git Commit: Saving one working bit of code and branches usually many commits. Commits should tell the story of your work.
	5. Git status: SHows the status of the current branch files and what branch you are on
	6. Git branch: shows branches
	7. Git merge: takes from one branch and combines the code from the branch you are on with the branch you specify in the command eg on master branch: git merge development would combibne the development branch with master. **NOTE** you are merging to the branch you are on.

8. Tricks:
        1. Say you start working on master branch and fogot to make a branch before you start working. You can make a branch after you write code on another branch like master. Then make a new branch and then you cna commit. The changes to master or any branch are not officially saved in GIT until the commit.
