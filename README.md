See my [One Page Resume](http://stnava.github.io/CV/ "1-Pg-Resume") inline link. 

  git branch -D gh-pages

  git push origin --delete  gh-pages

  git checkout --orphan gh-pages

  git add index.html

  git add images/

  git commit -a -m "pages commit"

  git push origin gh-pages

  git checkout master
