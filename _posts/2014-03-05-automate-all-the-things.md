---
layout: page
title: Automation For The Win
description: Automation For The Win
category: tools
tags: [automation, grunt, tools]
# thumbnail: automate-all-the-things.jpg
# image:
#  feature: responsive-web-design.jpg
#  credit: Michael Rose
#  creditlink: http://mademistakes.com
comments: true
#  share: true
--- 
## Introduction
**Great Developers** are often also **Lazy Developers**. It's not a criticism, it's a good thing. As the saying goes:

> Lazy programmers hate doing grunt work, and will, whenever possible, find ways to automate or scriptify the work, 
instead of doing it by hand.

If you're going to have to repeat the same tasks all the time, you might as well automate them and start finding better 
uses for all of that free time you'll be having in the near future.

Automation itself is not a new concept, but it's relatively recently - with the rise of tools like 
[Grunt](http://gruntjs.com/) - that it's crossed the threshold of being accessible to, and designed for those that work 
in the realm of the "Front End".  One of the key benefits of Grunt is that it's a tool that's extensible and built in a
language which we're all familiar with - *JavaScript*.

## Summary

### What can we automate?

Often the most common elements that we need to automate are:

- **JavaScript minification**, combining lots of separate javascript files into one single, optimised file.
- **CSS minification**, and more importantly, using preprocessors such as SASS to generate our output CSS files.
- **Spritesheet generation**, because that's an absolute nightmare to create and maintain by human hands. 
- **Optimisation**, **generation** or **processing** of **images**.

There's much more besides - such as uploading or downloading files, compressing archives, checking code quality or 
executing command-line actions - and all of which can easily be boring, repetitive, complex and error prone all at the 
same time.

### An introduction to Grunt

[Grunt](http://gruntjs.com/)  is our current weapon of choice for automating our repetitive local workflow tasks. In 
December 2013 we had a "Brown Bag Session" introducing Grunt, and since then we've had some initiatives such as 
*Automate ALL THE THINGS* as a knowledge sharing exercise and to push Grunt's adoption across a range of internal 
projects.

- - -

**Introducing Grunt** - a JavaScript-syntax tool for automating your build processes. Better than batch files, better 
than rakefiles, better than ANT or anything else out there. I'm going to show you some magic, and then show you how to 
make that magic happen yourself, and then your existing processes will look bleak, dull and boring in comparison.

<script async class="speakerdeck-embed" data-id="d71b909045610131812366ab85d4b2f5" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>

*(Naturally a presentation like this loses a bit of its 'wow' factor when it's not actually being presented, so feel 
free to talk to a Training Champion, James F or another member of the Front End Team for a personal recap.)*

- - -

The benefits of having these monotonous tasks scripted should be as obvious as using source control. And just like source 
control, once you're on the bandwagon you'll wonder why you ever tried to live without it.

## Further Reading
- [Grunt for People Who Think Things Like Grunt are Weird and Hard](http://24ways.org/2013/grunt-is-not-weird-and-hard/)
- [An Introduction To Grunt](http://code.tutsplus.com/articles/an-introduction-to-grunt--wp-34728)
- [Grunt and Gulp Tasks for Performance Optimization](http://yeoman.io/blog/performance-optimization.html)
- [Presentation: Automating Front-end Workflow](https://speakerdeck.com/addyosmani/automating-front-end-workflow)

And finally, go build something awesome:

![Automation is great, isn't it?](/images/automation-awesome.gif)
