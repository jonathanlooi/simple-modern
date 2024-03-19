# this is my fork of the archie hugo theme, which i am calling 'simple modern', and i am using on my personal website, jonathanlooi.com

## Installation
In your Hugo website directory, create a new folder named theme and clone the repo
```bash
mkdir themes
cd themes
git clone https://github.com/jonathanlooi/simple-modern.git
```
Edit the `config.toml` file with `theme="simple-modern"`

For more information read the official [setup guide](https://gohugo.io/installation/) of Hugo.

## Writing Posts
Create a new `.md` file in the *content/posts* folder
```yml
---
title: Title of the post
description:
date:
tldr: (optional)
draft: true/false (optional)
tags: [tag names] (optional)
---
```

## Credits
Forked from [Archie Theme](https://github.com/athul/archie) and Licensed under MIT License

Design inspired by LaTex and academic papers.

----

## Config Options

### Custom CSS
Custom CSS files can be included though the `customcss` config parameter.

Note: CSS files should be placed under the `assets` directory e.g. `assets/css/first.css`.

```toml
[params]
	customcss = ["css/first.css", "css/second.css"]
```
