# SimpleFor-Ref

…or create a new repository on the command line
echo "# newref" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Vinay0905/newref.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/Vinay0905/newref.git
git branch -M main
git push -u origin main
