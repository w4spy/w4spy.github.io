---
title: How this site was born 👶
date: 2023-02-25 22:05:17 +01:00
modified: 2023-03-11 17:40:11 +01:00
tags: [blog, netlify, jekyll, github]
description: All the services are free, a source code of this site placed on github repository and intergration with netlify service, another service that you can use is github page for hosting your own static site.
---

The website was made using Jekyll the open source static sites generator, and klisé simple theme.
<hr>

All the services are free, source code of the site was placed on [github](https://github.com/piharpi/mahendrata.now.sh) repository and intergration with [netlify](https://netlify.com) service, another service that you can use is [github pages](https://pages.github.com/) for hosting your own static site.

<hr>

#### Let's do this

So, before we start creating our site, we need some tools, you can seek how to install each one by yourself , in this guide i will just show you how to install jekyll and deploy your site on  netlify, but make sure you have installed the following tools.

#### Prerequisites

Requirements before the magic show.

- [Ruby](https://www.ruby-lang.org/en/downloads/) programming language
- [Git](https://git-scm.com) (version control)
- [Netlify](https://netlify.com) and [Github](https://github.com) account
- [Bundler](https://bundler.io)

#### Installation

First, you need some [SSG](https://www.staticgen.com/), there are many kinds of ssg, but in case i'm using Jekyll cause i'm already familiar with it, open your terminal and type command on below

```bash
$ bundle install jekyll # installing jekyll in your machine
$ jekyll new my-site && cd my-site # create new jekyll project
$ jekyll s # run jekyll server
```

Now, jekyll is running on your local machine, open your browser and go to `localhost:4000` is default address from jekyll, press <kbd>CTRL</kbd> + <kbd>C</kbd> to stop the jekyll server.

#### Adding remote repository

Before we add a remote repository, you must have [github](https://github.com/new) repository, if you already have a repository, just add github remote address to your local folder, with the following commands

```bash
$ git init # initializing project folder
$ git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git # change UPPERCASE with your own!
$ git add -A && git commit -m "Initialize" && git push -u origin master # push code to github
```

Now check your github repository, make sure the files is uploaded correctly.

#### Deploying to netlify

Go [netlify](https://netlify.com) dashboard, and follow these steps.

1. click `new site from git`, then choose `Github`.
2. then choose your repository where is the jekyll sources uploaded.
3. netlify smart enough to set it up, we just need to click `Deploy site button`.

Wait for a moment, and voila..! your site is up and using `.netlify.com` domain, if want your  website to look professional, just buy a domain from your favorite domain store, or you can use free domain names such as freenom.

So, what are you waiting for, just create your own website for free.

happy coding!!
