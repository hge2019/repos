# How to connect to GitHub from IntePlast?
Run
`git config --global http.proxy http://fuhqlxscb.fpcusa.com:8880`

Clone the repository
`git clone https://github.com/hge2019/QAC_MTI_SYS.git`

Create/Modify a file
Create a file or revise an existing one. To add it to Git/GitHub, run:
`git add filename`
`git commit -m 'The comment you want to see in Git history'`
`git push`




# …or create a new repository on the command line
echo "# QAC_MTI_SYS" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/hge2019/QAC_MTI_SYS.git
git push -u origin master

# …or push an existing repository from the command line
git remote add origin https://github.com/hge2019/QAC_MTI_SYS.git
git push -u origin master

# …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.