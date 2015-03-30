---
layout: post
title: Hello world!
date: 2015-03-29 13:50:00
tags:
- Jekyll
- GitHub
---

*My first post about how this site was built up.*

This site is built by the most popular static site generator: [Jekyll](http://jekyllrb.com/) with the template [Jekyll Now](https://github.com/barryclark/jekyll-now).

A static site is nothing but plain text yet displayed in a rich format. To avoid manual typing in the format tags, bloggers make uses of static site generator to transform folders and files which followed a pre-defined structure. 

I had experience of building static site before, so I was trying to start from scratch to crate my site. Two hours later, I only come up with an ugly site without any plug-in support. So I changed my mind and forked Jekyll Now.

### Building this site
Here is the steps of creating this site:

1. installing [Jekyll for GitHub](https://help.github.com/articles/using-jekyll-with-pages/)
2. creating a GitHub repository with the `username.github.io` name
3. cloning the repository to local project root
4. download the Jekyll Now package
5. moving the content in the Jekyll Now folder to the local project root
6. running the local Jekyll server by

    bundle exec jekyll serve

7. viewing the site on `https:localhost:4000` 
8. customizing the site

Jekyll Now supports Google Analytics and Disqus. I created a widget on the services and filled the require information on the `_config.yml` file. Now, the site is ready for posts.

### Posting articles
Each post is a markdown file with a special name format mm-dd-year-title.md under the `_post` directory.

Each post should contain a [YAML](http://yaml.org/) format header. For example, the header for this post is:

    ---
    layout: post
    title: Hello world!
    date: 2015-03-29 14:50:00
    ---

The order of posts is organized using the date (or the alphabetical order of the filenames in `_posts` if the date is not provided).

OK, this is sufficient for starting a site. Hope I will jog down more here in the future.
