# Git-WorkFlow-Team
echo "# Git-WorkFlow-Team" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/DUYNGO14/Git-WorkFlow-Team.git
git push -u origin main

Xóa git ở local
git branch -d <name branch>
Xóa git ở server
git push origin -d <name branch>