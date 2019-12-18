#Introduction to GIT

1. Git: Software COde management (SCM)

2. Has a .giti folder that hoolds the versions of the software like a database.

3. Repo: the organisational unit of a program or software library and you can combine git repo into larger project. Repos also use the org unit of code that is tested.

4. Think of git like a tree and that branches are like copies of the tree. The git repo has a trunk that we call master and that the branches are copies of the source in various states of completion.

5. Master: generally considered the production release/version of the software.

6. Git has a dance called "Git Flow".
   Step0: Make sure you have a git repo made or cloned
   Step 1: WHen you goto work on a feature, bug, or task, make a branch
   Step 2: Each working piece of code and/or test/action should have a commit tagged with Fix, Feature, or Task depending on what you are doing. Also, when you have project management system, you should include ticket number in the commit so that the commit can be tracked  to the original request from the project manager/PMS.
   Step 3: When your code is done, you nedd to merge development or master into your branch and check that your program still works. If it works then you should push it to github/central repo. Then someone will make a pull request and then the branch you created in step 1 will be merged usually into the development branch, unless your merging the development branch into the software...
