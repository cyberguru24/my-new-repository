echo "# my-new-repository" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/cyberguru24/my-new-repository.git
git push -u origin main
