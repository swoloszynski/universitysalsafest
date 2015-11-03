# University Salsa Fest
## Event Website

### Deploy to staging

To deploy to [the Github hosted page](http://swoloszynski.github.io/universitysalsafest/), merge master into the branch `gh-pages`.

```
(universitysalsafest) [master] $ git checkout master
(universitysalsafest) [master] $ git pull
(universitysalsafest) [master] $ git checkout gh-pages
(universitysalsafest) [gh-pages] $ git pull
(universitysalsafest) [gh-pages] $ git merge master
(universitysalsafest) [gh-pages] $ git push
```
