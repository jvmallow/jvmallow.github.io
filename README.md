# jvmallow.github.io
Jeffry V. Mallow Website

[![pages-build-deployment](https://github.com/jvmallow/jvmallow.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/jvmallow/jvmallow.github.io/actions/workflows/pages/pages-build-deployment)

This is the CMS for [Jeffry V. Mallow's website](https://jvmallow.github.io/).

To run this locally using `gem`, run the command

~~~
bundle exec jekyll serve --livereload
~~~

To install `jekyll` and build the website, run the commands

~~~
gem install jekyll bundler
bundle exec jekyll build
~~~

Note that if you change the file `_config.yml`, you must rebuild the website.

# Action items

- [ ] Edit your [Welcome page](https://github.com/jvmallow/jvmallow.github.io/edit/main/welcome.md)
- [ ] Edit your [About page](https://github.com/jvmallow/jvmallow.github.io/edit/main/about.md)
- [ ] Create a new post
  * Name the file `_posts/YYYY-MM-DD-TITLE.md`
  * Use the following template
~~~
---
layout: post
mathjax: true
title: Your catchy article title
tags: [topic1,topic2,etc...]
---

_One sentence for the article brief._

The body of your article, which can include $math equations$.
