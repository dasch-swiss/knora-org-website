# KNORA.ORG

This repository contains the source of the [knora.org](http://knora.org) website. It's built using Jekyll.

These instructions are mostly intended for committers who would like to update the site (i.e., adding a news item).

## Dependencies

Install the needed ruby stuff using bundler:

```
$ gem install jekyll bundler
$ bundle
```

If in doubt, head over to the github pages-page for instructions: 
https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#step-4-build-your-local-jekyll-site

Github lists their versions of Jekyll etc. here: https://pages.github.com/versions/

## Building

After cloning, cd into the `dhlab-basel/knora.org` directory and run:

``` 
$ bundle exec jekyll serve
```


To see the generated site, just visit `http://localhost:4000`.
