---
categories: ["golang", "hugo", "dokku", "blogging"]
description: ""
tags: ["golang", "hugo", "dokku", "blogging"]
date: "2016-10-09T20:25:43+13:00"
title: "Get Blogging in Under 5 minutes with Dokku and Hugo"
---

**This assumes you already have a dokku server setup**

### 1. install [Hugo](https://gohugo.io/)

if your on a mac you can do with [homebrew](http://brew.sh/) 

    brew install hugo

### 2. clone my [repo](https://github.com/jaybeecave/scribe)  

    git clone https://github.com/jaybeecave/scribe.git

### 3. add content

    hugo new post/my-first-post.md



### 4. get ready to deploy to dokku

    git remote add dokku dokku@dokku.me:scribe


### 5. deploy

    git push dokku master


You can read more info on Hugo and Dokku using the links below:

1. [Hugo](https://gohugo.io/)
2. [Dokku](http://dokku.viewdocs.io/dokku/) - *seems a bit slow at the moment*

I also highly recommend DigitalOcean as you can create a droplet with Dokku running right out of the box.

Here is my [referral link](https://m.do.co/c/b326711cef08) with $10 free credit

<br>
*If you can't find dokku its under One-click apps* 

{{%img-responsive "/images/dokku-droplet.png"%}}

Thanks to james scott for his [article](https://jamescscott.io/2016/09/04/deploying-hugo-on-dokku/) and the original repo for getting Hugo setup with Dokku

Happy Blogging!!