---
layout: post
title: "My First Draft Post"
categories: [blog, thoughts]
tags: [jekyll, drafts, example]
---

This is a draft post. It won't be published until you're ready to move it to the `_posts` directory and rename it with the proper date format.

## How Drafts Work in Jekyll

Drafts are posts without a date in the filename. They're stored in the `_drafts` directory instead of the `_posts` directory.

To preview your site with drafts, run:

```
bundle exec jekyll serve --drafts
```

This command will assign the current date to your drafts, making them visible in your local development environment.

## Publishing Drafts

When you're ready to publish a draft, simply:

1. Move it from `_drafts/` to `_posts/`
2. Rename it to include the date: `YYYY-MM-DD-my-first-draft.markdown`

And that's it! The post will now be published on your site. 