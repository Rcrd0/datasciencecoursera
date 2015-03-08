# datasciencecoursera

# Git quick rerference for beginners
http://www.dataschool.io/git-quick-reference-for-beginners/

## Useful videos about GitHub
http://datasciencespecialization.github.io/ 

## Markdown live editor
jrmoran.com/playground/markdown-live-editor/

## Git commands
git clone https://github.com/Rcrd0/datasciencecoursera.git

git remote -v

touch newfile.md

git status

git add . (o el nombre del fichero)

git commit -m "Texto del commit"

git log

git push origin master (desde master-local a origin-remote

git remote add upstream url
git fetch upstream
git merge upstream/master
git push origin master

-> progblem push
Crear repositorio test1 en gethub
Inicializarlo con readme.md
mkdir test1
cd test1
git init
git remote add origin url
cp fichero1 fichero2
git status
git add .
git commit -m "msg"
git push origin master -> error

-> error push rejected
git pull origin master (traerse el fichero readme)
git push orgin master (ahora funciona)

-> usar el cloning para evitarlo
git clone (url)
cp fich1 fich2
git add .
git commit -m "msg"
git push origin master
