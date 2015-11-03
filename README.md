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

### Deploy to production

1. Log into [Go Daddy](https://www.godaddy.com/).
2. Click on the account name and go to `Manage Your Hosting`.
3. Click `Manage` for `universitysalsafest.com`.
4. Click `File Manager`.
5. Select `Web Root (public_html/www)` and click `Go`.
6. Check `Overwrite existing files` and choose files to upload.
7. Once upload is complete, check [the site](universitysalsafest.com) for your changes.
