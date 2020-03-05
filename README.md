# Git for Teams - Lecture

### Branching
* Create a new branch called `edit-read-me`
* Checkout your new branch
* Add a message to the end of your `README.md` file
* Push the local changes to your branch

### Pull Request
* Open the repo in GitHub
* Create a pull request
* Review the changes made in the `README.md` file

### Merging
* Approve the pull request opened
* Merger the pull request
* View the merge in GitHub from the code tab of the master branch
* In VSCode checkout the master branch
    * notice that the remote changes are not reflected in your local repository
* Pull the changes from your merge into the master branch locally

### Creating and Resolving Conflicts
* In the master branch edit add a bullet point to the beginning of the branching section
* Push your local changes to the master branch
    * no merge required because you are making changes to the master branch
* Checkout the `edit-read-me` branch
    * notice the change from master is not reflected
* Add a bullet point to the beginning of the branching section (this bullet point should be different that the one from master)
* Push your local changes to that branch
* Open a pull request in GitHub
    * you should get a merge conflict message
* In VSCode pull remote changes from master into your branch
* Merge conflicts should be generated in the `README.md` file
* Accept incoming changes and push your local changes to your branch
* Open a pull request
    * notice the merge conflict has been resolved
* Approve and merge the pull request

### Ways to avoid merge conflicts
* communicate with your team
* `git pull origin master` before making any changes on your branch and after each push
* push local changes from your branch often (smaller pull request are better) 