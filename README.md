echo "# docker1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/genuineanger/docker1.git
git push -u origin main
