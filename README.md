README.md

# Create a repository on the command line (github repo must exist)
echo "# hello-git" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Antares1980/hello-git.git
git push -u origin master

#Push an existing repository from the command line
git remote add origin https://github.com/Antares1980/hello-git.git
git push -u origin master


