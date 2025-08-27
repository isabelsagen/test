# test

Åpne repo i vscode:

cmd + ctrl + P
Git: Clone https://github.com/isabelsagen/test.git

Lag ny fil, ikke lag i .git

touch myfile.py
git status

comitte 

git add myfile.py
git commit -m "Update myfile.py with new changes"
git push origin main

hente fra git 

git pull origin main



…or create a new repository on the command line
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/isabelsagen/test.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/isabelsagen/test.git
git branch -M main
git push -u origin main
