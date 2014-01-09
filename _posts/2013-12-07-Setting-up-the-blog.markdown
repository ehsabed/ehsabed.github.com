---
layout: post
title: "Setting up the blog"
date: 2013-12-07 19:40
comments: true
external-url:
categories: [blog, jekyll]
published: true
---
I had started e few months ago setting up this blog on [Github](http://github.com "GitHub"). But then I really not got around to finish it. After reading a few blogposts about [Jekyll](http://jekyllrb.com/ "Jekyll") and [Github](http://github.com) I decided that now was the time.

Since my memory is not what it used to be, I have naturally forgotten what I was doing the last time I started this. So, I better start all over...

Looking at how other clever people have done is the best way to learn new things. One example is [Phil Haack's blog](http://haacked.com "Haacked"), so I started with cloning his [Github repo](https://github.com/Haacked/haacked.com).

When looking in his repo and editing my files, I noticed a reference to [Octopress](http://octopress.org/). This is a framework for [Jekyll](http://jekyllrb.com/ "Jekyll") that intends to make it easier to blog with [Jekyll](http://jekyllrb.com/ "Jekyll") by including javascripts, css etc and most importantly the possibility to theme your blog. After some reading there, it looked like a nice way to setup the blog. Following the instructions from them, I started cloning that repo and then opened a shell and installed the dependencies. All according to instructions.

One thing I noticed was that when I started setting up the blog, Github used <code>username.github.com</code> as URL, but they are now switching to <code>username.github.io</code>. Not sure what I will have to do, but I'll leave it as it is right now. Everything seems to work with the github.io-address.

Since I have a domain-name that I want to use with this blog, I followed the instructions for setting up a custom domain-name at [Github's helppages](https://help.github.com/articles/setting-up-a-custom-domain-with-pages). I'm using a subdomain, so setting up <b>CNAME record</b> did the trick.

In case anyone wants to leave any comments, I'm using [Disqus](http://disqus.com/ "Disqus").

For RSS feed, [Feedburner](http://feedburner.com/ "Feedburner") is a nice alternative.

Now the blog is live, but I'll probably have to do some cleaning and modifications since I haven't really gone through all files and settings. So what's left is:

* Design. It is not very unique...
* Figure out where to store images. In the Github repository?
* Find the work process that suits me. Right now I edit posts in the browser and maybe that is all I need?

There are probably more issues to consider, but I'll handle them as they show up.
