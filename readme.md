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


# Suggested Workflow
Get the latest code from master
`git fetch`
`git checkout master`

Create your own branch for the new feature
`git checkout -b coolfeature`

Make changes
`git add your_cool_files.cs`
`git commit -m "Save this cool feature"`

When pushing the first time, use:
`git push --set-upstream origin coolfeature`
And later on use:
`git push`


# …or push an existing repository from the command line
git remote add origin https://github.com/hge2019/QAC_MTI_SYS.git
git push -u origin master

# …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.