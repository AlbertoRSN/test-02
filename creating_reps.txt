# create a new repository on the command line

echo "# test-02" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/andrzejmp/test-02.git
git push -u origin master

# push an existing repository from the command line

git remote add origin https://github.com/andrzejmp/test-02.git
git push -u origin master