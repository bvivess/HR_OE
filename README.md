# myweb
Situados en c:\myGBD, descargar rama inicial:
git clone https://github.com/bvivess/myweb.git

# Working wihin branches
git checkout -b "myBranch" --> Creates a new branch and moves to it
git checkout "myBranch"    --> Moves to this branch
git branch                 --> Shows all branches

# Pushing up the content of "myBranch"
git add --all
git commit -m "myBranch"
git push --set-upstream origin "myBranch"  --> first time, creates the branch on 'github'
git push                                   --> any time. Once create, push up the content

