# Git and Github


## Task 1:

### Demonstrate minimum 15 basic Git command with explanation and screenshot.


```
git config –-global user.name "ni3choudhary"
git config --global user.email "xyz@gmail.com"
```
This command sets the author name and email address respectively to be used with your commits.
![image](./readme_resources/git_config.JPG)


```
git init 
```
This command is used to start a new repository.
![image](./readme_resources/git_init.JPG)


```
git clone
```
This command is used to obtain a repository from an existing URL.
![image](./readme_resources/git_clone.JPG)


```
git status
```
This command lists all the files that have to be committed.
![image](./readme_resources/git_status.JPG)

```
git add main.py
```
This command adds a file to the staging area.
![image](./readme_resources/git_add.JPG)


```
git add .
```
This command adds one or more to the staging area.
![image](./readme_resources/git_add_all.JPG)


```
git commit -m 'Added main.py'
```
This command records or snapshots the file permanently in the version history.
![image](./readme_resources/git_commit.JPG)


```
git commit -a
```
This command commits any files you’ve added with the git add command and also commits any files you've changed since then.
![image](./readme_resources/git_commit_a.JPG)


```
git diff
```
This command shows the file differences which are not yet staged.
![image](./readme_resources/git_diff.JPG)


```
git merge developer
```
This command merge the mentioned branch[developer] into current branch[master].
![image](./readme_resources/git_merge.JPG)


```
git rm -f index.html
```
This command deletes the file from your working directory and stages the deletion.
![image](./readme_resources/git_rm.JPG)


```
git log
```
This command is used to list the version history for the current branch.
![image](./readme_resources/git_log.JPG)

```
git branch
```
This command lists all the local branches in the current repository.
![image](./readme_resources/git_branch.JPG)


```
git branch developer
```
This command creates a new branch.
![image](./readme_resources/git_branch_name.JPG)


```
git checkout developer
```
This command used to change the branch.
![image](./readme_resources/git_checkout.JPG)


## Task 2:

### Consider that your want to start an open-source project in your organization. Perform all the standard operation to create a repository with minimal permision for all the users. It should contain.

1. Proper open source structure
2. Proper Readme
3. Add 2 collaborator
4. Host GitHub Pages using settings (Designed to host your personal, organization, or project pages from a GitHub repository)


## Task 3:

1. Create a Issue in your github repository.
2. Raise a pull request.
3. Merge A pull request.
4. Reject a pull request with proper comments.
5. Add a Dependabot alerts in your github.(for above cases)
6. Stash changes
7. Create a release your package
8. Setup a Projects Board for your project.
