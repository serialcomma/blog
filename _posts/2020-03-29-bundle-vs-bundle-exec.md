---
layout: post
title: "Bundle vs bundle exec"
date: 2020-03-29 15:00:00 +0800
categories: [jekyll, tech]
tags: [jekyll, tech]
---

I manage this blog (and several others) with [Jekyll](https://jekyllrb.com).  While it is easy and efficient to add content once I've installed and configured it, I run across anomalies with every new installation.

I don't pretend to understand Ruby or most of the other components Jekyll is built from, including the 'gems' functionality. When running `bundle install` I would frequently encounter errors that seemingly came from nowhere--these were fresh installs and I hadn't touched the code. After some digging, I saw a recommendation to change the command to `bundle exec install`. Bingo! Problem solved.

The recommendation didn't explain why adding `exec` would fix the problem. Now I've found the answer on this [stackoverflow post](https://stackoverflow.com/questions/6588674/what-does-bundle-exec-rake-mean). See the *second* answer in that post for the most straightforward explanation.

Basically, a Jekyll blog is built from numerous Ruby gems. The specific versions of the gems needed for the blog are set out in a Gemfile. But there is also a system-wide Gemfile. When you execute `bundle install` it defaults to the system-wide Gemfile. If the blog is dependent on versions of gems that are different than the versions specified in the system-wide Gemfile, the bundler will show an error. Adding `exec` to the command instructs the bundler to use the Gemfile included with the blog, which presumably has the correct dependencies.

This method works when building and serving Jekyll blogs, too. If you encounter errors when using `jekyll build` or `jekyll serve`, try `bundle exec jekyll build` and `bundle exec jekyll serve` instead.