---
author: Aswath Ashok
categories:
- Example
- Hugo
- Guide
title: Base documentation guide
weight: 4
---

# Executive summary


# Introduction
Welcome to my website! This page is intended to be kind of a "guide" for myself primarily. This is more for my sake than yours...
I have a tendency to browse through many, many and manyyyy kinds of styles of personal websites and its quite common for people to have their uniqueness.
I strongly admire that and get gobbled up in their styles. So, my initial attempts mostly tend to look janky since its an agglomeration of many different things.
So, in order to not get fully lost, I thought having a "base" for grounding myself. If I tend to go wayward; Oh well, we'll worry about that then OwO.

## Dummy subsection 0.0

Codes in the website have this shadowy background (This shows the options for the four corners lines on the pages)
```html
<div class="crop-h"></div> <!-- horizontal lines -->
<div class="crop-v"></div> <!-- vertical lines -->
<div class="crop-c"></div> <!-- cover some segments -->
```

I believe there is language styling as default for html, yaml and css. Have to maybe add one for python and cpp?

### Dummy subsubsection 0.0.0

## Dummy subsection 0.1


## Blog and/or documentation

This theme supports two types of lists of pages: [blog](/blog/) and [documentation](/docs/).

- A blog list shows the post summaries in the list. You can either define a post summary via the `description` field in the YAML metadata of a post, or let this theme generate an automatic summary from the paragraphs of your post.
- A documentation list shows the tables of contents of documentation pages. This is similar to the table of contents of a book, so you could use this theme to write a book (or two).

By default, pages under the `content/blog` directory will use the blog list, and pages under `content/docs` will use the documentation list. If you want other pages to use the `blog` or `docs` list layout, you can specify the `layout` field in the YAML metadata of `_index.md` (e.g., `layout: docs` in `content/foo/_index.md`).

If you want to order pages manually in the list, you can set the `weight` field in the YAML metadata of pages.
