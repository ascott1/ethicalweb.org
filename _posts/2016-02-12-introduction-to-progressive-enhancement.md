---
layout: post
title:  "An introduction to progressive enhancement"
date:   2016-02-12
categories: progressive-enhancement
---


Progressive enhancement is a term that often insights intense debate. For many, progressive enhancement can be summed up as “make your site work without JavaScript.” While, developing a site that works without JavaScript often does fall under the web of progressive enhancement, it can define a much more nuanced experience.

In Aaron Gustafson’s seminal A List Apart Article, [Understanding Progressive Enhancement](http://alistapart.com/article/understandingprogressiveenhancement), he describes progressive enhancement as a peanut M&M. The peanut being the core experience, which is essential to the user. The chocolate encompasses the features and design that take us beyond the naked peanut experience and add some much loved flavor. Finally, the candy shell, though not necessarily needed, provides added features, such as not melting in your hand. Oftentimes this example is translated to HTML as the peanut, CSS as the chocolate and JavaScript as the candy shell.

In today’s web application landscape it may be over simplified to consider progressive enhancement as simply “works without JavaScript.” In fact, many of the rich interactions and immersive experiences that have come to define the modern web certainly require JavaScript. For progressive enhancement to be considered an ethical issue in web development, we must tie it back to user needs. Progressive enhancement is about defining what a user *needs* and ensuring that it is always delivered to them, in a way that will work regardless of network conditions, device, or browser.

I prefer [Jeremy Keith’s take](https://youtu.be/-yIbKaA3wCo) that progressive enhancement is a “process” rather than a specific technique or set of technologies. By Keith’s definition this process looks like:

1. Identify the core functionality
2. Make that functionality available using the simplest technology
3. Enhance!

As a developer it is our job to determine the “core functionality” of our application and what is an enhancement. This allows us to develop a baseline to build from, yet the baseline for any given project may be different.

In his 2012 article, [Stumbling on the Escalator](https://www.christianheilmann.com/2012/02/16/stumbling-on-the-escalator/), Christian Heilmann appropriated a Mitch Helberg comedy bit about escalators for progressive enhancement:

> An escalator can never break – it can only become stairs. You would never see an “Escalator Temporarily Out Of Order” sign, just “Escalator Temporarily Stairs. Sorry for the convenience. We apologize for the fact that you can still get up there.”

As a person who has spent a lot of time in the Washington DC metro system, I can really appreciate this analogy. Thankfully, when an escalator is out I am not trapped underground, but instead can huff up the now stairs to the street.

Oftentimes, when beginning a project, I am presented with a set of business requirements or a beautiful design. From these, it can be easy to see the end goal, but skip the baseline experience. If, in the case of the escalator, my requirement was to “build a transportation system that will allow Metro riders to travel from the terminal to the street,” my initial reaction may be to create an elevator. You can imagine how this might become problematic.

Developing web apps works in much the same way. If we only consider the end goal, we run the risk of leaving our users stranded. By focusing on and providing a solid baseline for our users, we set ourselves up for success in many other aspects of ethical web development, such as accessibility and performance.
