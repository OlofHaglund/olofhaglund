---
layout: post
title: "Jekyll on Fedora 34 and Missing Webrick Dependency"
description: "Setting up Jekyll on an Fedora 34 installation"
categories: [Software Development]
tags: [Fedora, Webrick, Jekyll]
redirect_from:
  - /2022/08/05/
---

# Jekyll on Fedora 34 and Missing Webrick Dependency
So I recently decided that I should get into updating my website a little bit but quickly run into the problem that I just couldn't get it to work through following the guide in the Jekyll template that I was using. So here comes a quick guide of how I got it to work for me.

## Setup Ruby
First step is to install Ruby, just installing Ruby is not enough. As some of the dependencies are compiled locally we also need some of the under lying tools.
```bash
sudo dnf install ruby ruby-devel openssl-devel @development-tools gcc-c++
```

Next step is to install the Bundler tool to manage Ruby packages.
```bash
sudo gem install bundler
```

I also highly recommend that set Bundler to use a local path when working. Otherwise we can end up in version collisions. Don't forget to add the folder `vendor` to your `.gitignore`.
```bash
bundle config set --local path 'vendor/bundle'
```

In theory we should now have everything set but it seems that in current version of Jekyll that ships on Fedora one crucial dependency is missing. Webrick, the http server that Jekyll uses for you to host the website locally while you work on the your site. We need to add that to bundle first before installing.
```bash
bundle add webrick
```

Now we can continue to download all the dependencies.
```
bundle install
```

## Running Jekyll
We now ask Bundler to run Jekyll for us.
```
bundle exec jekyll serve
```

Your site is now hosted on `http://localhost:4000`

## Closing words
I'm a quite a newbie working with Jekyll. My way of working has always been download a template, update the config file, send it to GitHub and hope for the best. So a lot of this was through hours of googling and brute force.

Hope you have a more pain free installation than me :)
