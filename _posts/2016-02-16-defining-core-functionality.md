---
layout: post
title:  Defining Core Functionality
date:   2016-02-16
categories: progressive-enhancement
---

If progressive enhancement is the process of defining a core functionality and building up from there, how do we define that initial baseline? The goal is to consider the bare minimum that a user requires to use our application. Once we have defined this, we can layer on additional style and functionality. For some applications this may be a completely JavaScript free version of the experience, while for others it may be a less fully featured version, and still others it may be providing some server rendered content on the initial page load only.

The key is to think of progressive enhancement not as a binary option, but instead as a range, determining what is the best decision for users. In this way, progressive enhancement is a gradient rather than an either/or option. Our responsibility is to decide where on this gradient our particular application falls.

![gradient image representing progressive enhancement](/img/progressive-enhancement-gradient.png)

I’d encourage you to take a few minutes and consider what the core functionality might look like for a few different types of websites and applications. Identify the primary goal of the site and determine the minimum amount of technology needed to implement it. To take it a step further, write some markup or pseudo code explaining how you might implement those baseline and features.

- News website
- Social network (write text posts and read the feed of friends)
- Image sharing website
- Web chat application
- Video chat application

When working on your own applications, try to perform the same exercise First, determine the core functionality for your users and build the application from there. This programatic approach also pairs well with the [Agile](http://www.agilemanifesto.org/) approach to software development, where the goal is to deliver working software at the end of each development sprint. If we first deliver a core experience, we can iteratively build upon that experience while continuing to deliver value.
