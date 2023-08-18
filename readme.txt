test2

mkdir TEST2
cd TEST2
git init 
vi readme.txt
git add ./readme.txt
git commit -m "first commit from CLI" --author="noregrof <noregrof@github.com>"
git push --set-upstream ssh://git@github.com/noregrof/TEST2 master

git commit -m "second commit from CLI, updatedd readme.txt" --author="noregrof <noregrof@github.com>"
git push --set-upstream ssh://git@github.com/noregrof/TEST2 master
