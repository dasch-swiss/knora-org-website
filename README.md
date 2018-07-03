# KNORA.ORG

This repository contains the source of the [knora.org](http://knora.org) website. It's built using Jekyll.

These instructions are mostly intended for committers who would like to update the site (i.e., adding a news item).

## Dependencies

Knora.org is built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

To see the generated site, just visit `http://localhost:4000`.
