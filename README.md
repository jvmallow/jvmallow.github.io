[![pages-build-deployment](https://github.com/jvmallow/jvmallow.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/jvmallow/jvmallow.github.io/actions/workflows/pages/pages-build-deployment)

# jvmallow.github.io
Jeffry V. Mallow Website

This is the CMS for [Jeffry V. Mallow's website](https://jvmallow.github.io/).

# Automatic updates

Any change made to this repository will automatically update the public website. The update usually takes about 1 minute.  See [Actions](https://github.com/jvmallow/jvmallow.github.io/actions) for the status of the most recent updates.
# Local deployment
To run this locally you your laptop/desktop using `gem`, run the command

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

- [ ] Edit your tabs with the [navigation file](https://github.com/jvmallow/jvmallow.github.io/edit/main/_data/navigation.yml).
- [ ] Edit your tagline at Line 11 of the [Website configuration file](https://github.com/jvmallow/jvmallow.github.io/edit/main/_config.yml)
- [ ] Edit your [Welcome page](https://github.com/jvmallow/jvmallow.github.io/edit/main/welcome.md)
- [ ] Create a new post
  * Click the `Code` tab, click on `Add file`, and choose `+ Create new file` or click [here](https://github.com/jvmallow/jvmallow.github.io/new/main)
  * Name the file `_posts/YYYY-MM-DD-TITLE.md`
    - The date `YYYY-MM-DD` is the publication date. (Anything in the past or present is ok, future dates are not allowed).
    - The `TITLE` is for internal use only, it just has to be unique to your website. (Not necessarily unique to the world). Do not use spaces. Use underscores instead.
  * Use the following template
~~~
---
layout: post
mathjax: true
title: Your catchy article title
category: Tab title
tags: [Topic1,Topic2,Etc]
---

*One sentence for the article brief.*

The body of your article, which can include $math equations$ and images such as Figure 1.

![Jeffry Mallow](/images/jvmallow.jpeg "Jeffry V. Mallow")
Figure 1: A sample image
~~~

* Including `mathjax: true` is necessary if the article contains any Latex math equations.
* The `category` must match the tab title exactly
* The `tags` become the keywords when the page is published.  They will also be used to create the collection in the archive (if you use that feature).
* The first paragraph becomes the brief that is include the list of pages on each tab.
* The rest of the article can be any length and uses Markdown for formatting. See https://www.markdownguide.org/tools/jekyll/ for details.
  
