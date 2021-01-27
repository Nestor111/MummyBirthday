## New Project
1. Make sure you are in the working project folder
2. $ git init
3. Edit projects
4. $ git add --all
5. $ git commit -m "<type some notes here>"

### Go to github
1. create new repository
2. Find out the link of your repository (e.g. https://github.com/Nestor111/sydneytravel.git) 
3. $ git remote add origin <repository link>
4. $ git push -u origin master
5. $ git checkout -b gh-pages
6. $ git push -u origin gh-pages


### Update Project
1. Make sure you are in your repository
2. $ git status
3. $ git add --all
4. $ git commit -m "<type some notes here>"
5. $ git push -u origin gh-pages