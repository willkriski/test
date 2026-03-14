# Signal Ledger

A custom Jekyll news-style template for GitHub Pages.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

## Publish on GitHub Pages

This repo is configured for a project site path:

`https://willkriski.github.io/test`

If you rename the repository or move this template to a user site repo, update `baseurl` in `_config.yml`.

## Add a new article

Create a Markdown file in `_posts` named like:

`YYYY-MM-DD-your-title.md`

Include front matter such as:

```yaml
---
title: My New Story
category: Update
author: Will Kriski
deck: A short summary that appears below the title.
---
```
