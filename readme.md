### Media jekyll blog
(I need a better name for this)

A [Jekyll](https://jekyllrb.com/) site for me to keep a list of movies, tv, games, books, and music I've consumed. I thought about making a full-on web app for it but to be honest that seemed like a lot of hassle for what is basically a list.

### Usage

Posts live under the `_posts` directory (I've put them in folders for year and category but you don't need to do that). Each post has the following metadata:

```
---
layout: post
title:  string
category: game | tv | movie | book | music
rate: 0 | 1 | 2
---
```

If you want to add more categories (for the archive pages) add a new file to the `archive` directory and set the category to the category you'll use for the posts. e.g. `comics.md` with the category `comic`. You'll also want to update the category links in `_layouts/archive.html` to match your new categories.

The links in the header are located in `_includes/header.html`.

[MIT licence](http://rmlewisuk.mit-license.org/)