echo "# DisappearCode" >> README.md
git init
git add README.md
# This line should be removed without trace.
git commit -m "first commit"
git remote add origin git@github.com:Bluegear/DisappearCode.git
git push -u origin master

