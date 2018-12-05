init:
git init
git remote add origin [url]
git push --set-upstream origin master

pull/push problem vid lokalt repo started med init (vs clone)?
git pull --allow-unrelated-histories

gitignore
touch .gitignore
vi .gitignore

gitignore ignore everything except this
*!*/!/your/path/here/**

gitignore not removing remote commits?
git rm -r --cached .
add .
git commit -m “msg”
git push

Pulling:
Gör alltid git commit -am “msg” först, sedan
git pull alternativt git pull origin [branch]

Pushing:
vid nya filer: git add .
git commit -am “msg”
git push origin [branch]

Reverting:
TODO

Fastnat? ESC, :q (:wq), ENTER 
Roligt:
prettified log: 
git log --all --decorate --oneline --graph
git log
git shortlog (git shortlog -s för # commits)








