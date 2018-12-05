### **init:**

- git init / git clone
- git remote add origin [url]
- git push --set-upstream origin master


**pull problem with init initilization (vs clone)?**
- git pull --allow-unrelated-histories

------------
### **pull (i e fetch + merge):**
- git commit -am “[msg]” 
- git pull

------------
### **push:**
- git add .
- git commit -am “[msg]”
- git push
---
### **.gitignore**
- touch .gitignore
- vi .gitignore

**"catch-all"(ignore everything except this/path)**
- *!*/!/this/path/**

**gitignore not removing remote commits?**
- git rm -r --cached .
- add .
- git commit -m “msg”
- git push

------------


### **vi:**
- http://www.phaget4.org/seidel/vi.html

**command mode:**
- i - insert mode
- :wq - write & quit

**insert mode:**
- ESC - command mode


---
### **revert:**
- TODO

---
### **log stuff:** 
- git log --all --decorate --oneline --graph
- git log
- git shortlog (git shortlog -s för # commits)
---
### **.md**
- https://pandao.github.io/editor.md/en.html
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

---







