#Demo Git Repository
This is the first file in this rep.

new


new for github testing

cd .ssh
ssh-keygen -t ecdsa -b 521 -C "im.chuckc@gmail.com"
ssh -T git@github.com


git commit -am "Updating index page for GH"

git remote add origin git@github.com:imchuckc/git-demo.git
git branch -M main
git push -u origin main

