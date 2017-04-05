---
layout: post
title: Override Author Byline Test Post
excerpt: An article to test overriding the default site author.
categories: articles
tags:
  - sample-post
  - readability
  - test
author: billy_rick
comments: true
share: true
modified: {}
image:
  feature: so-simple-sample-image-7.jpg
  credit: WeGraphics
  creditlink: 'http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/'
published: true
---
# This is perfect!

Previously the theme used a global author for the entire site and those attributes would be used in all bylines, social networking links, Twitter Card attribution, and Google Authorship. These `owner` variables were defined in `config.yml`lsdkjfsdfd

Start by modifying or creating a new `authors.yml` file in the `_data` folder and add your authors using the following format.

```yaml
# Authorssf

billy_rick:
  name: Billy Rick
  web: http://thewhip.com
  email: billy@rick.com
  bio: "What do you want, jewels? I am a very extravagant man."
  avatar: bio-photo-2.jpg
  twitter: extravagantman
  google:
    plus: BillyRick

cornelius_fiddlebone:
  name: Cornelius Fiddlebone
  email: cornelius@thewhip.com
  bio: "I ordered what?"
  avatar: bio-photo.jpg
  twitter: rhymeswithsackit
  google:
    plus: CorneliusFiddlebone
```

To assign Billy Rick as an author for our post. You'd add the following YAML front matter to a post:

```yaml
author: billy_rick
```
