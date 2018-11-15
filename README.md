# University Salsa Fest Event Website

## Local development

To run the Jekyll site locally:

```
(universitysalsafest) [master] $ rvm use 2.2.9
(universitysalsafest) [master] $ jekyll serve
```

To run tests:

```
(universitysalsafest) [master] $ htmlproofer _site/
```

Add flag `--disable-external` to avoid calling external links.


## Jekyll + Github Pages Hosting

To push changes to public GitHub Pages hosting:

```
(universitysalsafest) [master] $ git checkout master
(universitysalsafest) [master] $ git pull
(universitysalsafest) [master] $ git checkout gh-pages
(universitysalsafest) [gh-pages] $ git pull
(universitysalsafest) [gh-pages] $ git merge master
(universitysalsafest) [gh-pages] $ git push
```

GitHub Pages automatically manages Jekyll deploys.

## Updating the Ruby Version

```
(universitysalsafest) [master] $ rvm ls
(universitysalsafest) [master] $ rvm install 2.2.9
```

Change the ruby version in the Gemfile.

```
(universitysalsafest) [master] $ gem install bundler
(universitysalsafest) [master] $ bundle
```

Confirm that the `bundle` command automatically changed the ruby version in the Gemfile.lock. Update the ruby version in .ruby-version and .travis.yml.

```
(universitysalsafest) [master] $ jekyll build
```
