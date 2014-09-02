Rails Girls Atlanta Website
=========================

## Contributing to the Site
 - Submit a blog post or submit suggestions for changes via pull request
 - Changes to the Welcome or About sections of the home page can be made in
   `_confing.yml`

## Submit a Blog Post
 - Create posts to display your projects.
 - Use the following as an example:
```txt
---
layout: default
modal-id: my-blog-post
date: 2014-07-18
img: railsgirls-sq.png
category: Web Development
description: The description
title: My Blog Post

post text goes here
---
```
modal-id should be similar to the title. This is used to match the post to the 
corresponding modal block, so ids need to be unique.

Create a pull request against the master branch to have your post merged.

### Submitting Workshops & Stories

For workshop or story posts to be shown under the correct section, they must
be given the correct category:

Stories `category: Stories`

Workshps and Events `category: Events and Workshops`

## Contributing to the Site
 - Pull requests are welcome & encouraged!

### Build the Site Locally
 - Fork this Repo
 - `gem install jekyll`
 - `jekyll build && jekyll serve`
