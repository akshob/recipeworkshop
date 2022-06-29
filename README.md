# Recipe Workshop

## Develop

This was built with [Jekyll](http://jekyllrb.com/) version 4.1.1

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ eval "$(rbenv init -)"
$ rbenv install
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

### Posts/Recipes

* Add, update or remove a post in the *Posts* collection.
* The recipes page is organised by categories.
* Change the defaults when new posts are created in `_posts/_defaults.md`.
