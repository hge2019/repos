# How to connect to GitHub from IntePlast?
Run
`git config --global http.proxy http://fuhqlxscb.fpcusa.com:8880`

`git config --global user.name 'Hongjun Ge'`

Clone the repository
`git clone https://github.com/hge2019/QAC_MTI_SYS.git`

Create/Modify a file

Create a file or revise an existing one. To add it to Git/GitHub, run:

`git add filename`

`git commit -m 'The comment you want to see in Git history'`

`git push`


# Simple workflow
Make changes on master branch, commit the changes and push to GitHub.

# Suggested Professional Workflow

Get the latest code from master

`git fetch`

`git checkout origin/master`

Create your own branch for the new feature

`git checkout -b coolfeature`

Make changes

`git add your_cool_files.cs`

`git commit -m "Save this cool feature"`

When pushing the first time, use:

`git push --set-upstream origin coolfeature`

And later on use:

`git push`

Find your branch at https://github.com/hge2019/QAC_MTI_SYS/branches, and click **Create Pull Request** to create a code review. 

When it's properly reviewed by your coworker(s), click "Merge Pull Request" to merge the pull request to master.