---
id: x7I
permalink: /
title: This is an Example Post 1
date: 2025-03-19 10:29:28
tags: [Markdown, Best Practices]
---

This document is a template for a blog post. You can copy and rename it and write a blog post based on it.

## Key 'id'

- `id` is **required**. Post will not be created on the blog without an `id`.
- `id` should be **unique**. If multiple posts have the same `id`, only one post will be published on the blog.
- For an `id` value, upper and lower case letters, numbers, and `_` are valid.
- You can name the Markdown file anything you want. The file name doesn't matter because we use `id` to identify a blog post.

## Key 'permalink'

### When 'permalink' is Empty, '/', or Invalid

- If the `permalink` value is empty, `/`, or invalid, we will automatically generate a `permalink` based on the value of `title`.

  For example, if the title is `This is an Example Post`, the corresponding permalink will be `this-is-an-example-post`.

  Spaces are replaced with `-`, illegal characters will be deleted, and uppercase letters are converted to lowercase letters.

  Next time you modify the `title`, the value of `permalink` will also change accordingly.

### You can modify the 'permalink' at any time without worrying about SEO weight of the post being reduced.

- That's because we append a `-` and the `id` to the end of each post link.

  So for this post, the real URL would be like https://your-domain.com/this-is-an-example-post-x7I

- Visiting a stale URL will be redirected to the fresh URL with status `301`.

## Categories

- Here, `categories` are **directories**, and they are **equivalent**. `posts` are placed in directories in the form of markdown files.

- No matter you name the directory `ruby_on_rails`, `Ruby_on_Rails`, `ruby-on-rails`, `Ruby-on-Rails`, `Ruby on Rails`, or `Ruby On rails`, from the blog's point of view, they are the same `category`. The category's URL path name is `ruby-on-rails`, and the category's blog display name is `Ruby On Rails`.

## How to add pictures to your posts?

Remember to put the images in the [/images](/images) directory. The blog **cannot** recognize other directories as image directory!

For referencing an image, it is completely Markdown syntax.

![](/images/example_1.jpg)

*A Little Penguin*

## What are the best practices for using markdown?

Please read [Markdown Guide ](https://markdownguide.offshoot.io/basic-syntax/).
