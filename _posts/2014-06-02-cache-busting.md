---
layout: page
title: Cache Busting
description: Cache Busting
category: performance
tags: [cache]
author:
  name: Adrian Lansdown
image:
  feature: cache-busting.jpg
  credit: Doug Kline
  creditlink: https://www.flickr.com/photos/popculturegeek/7019135657
---
## Introduction
Caching busting stops browsers from using a cached file when an new updated version is available.

If you are following best practices for caching your assets ([Google - Optimize Caching](https://developers.google.com/speed/docs/best-practices/caching)) you might find that browsers will used the cached version of a file even when a new updated version is available.

This issue becomes worse when proxies, load balancers and other _helpful_ machines are taken into consideration.

To get around problem you need to _cache bust_ meaning that the browser and anything in between knows to request the latest version of the file. There are a number of ways this can be done, best practice is to rename the whole file by appending a version number, date/time or hash to the end of the file name.

This process can be done a number of ways including: Build process, Grunt or Web server configuration.
 
## Summary
- Browsers, proxies and other servers can cache files even when they have changed.
- Giving a file a unique filename will help break any caching occurring on file updates.
- Renaming the file is better than adding a query string.
- Multiple ways of automating this process. Build Process, Grunt, Web Server configuration.
 
## Further Reading
- [What is a cache buster and how does it work?](http://www.adopsinsider.com/ad-ops-basics/what-is-a-cache-buster-and-how-does-it-work/) 
- [Revving Filenames: don’t use querystring](http://www.stevesouders.com/blog/2008/08/23/revving-filenames-dont-use-querystring/)
- [Google : Leverage proxy caching](https://developers.google.com/speed/docs/best-practices/caching?csw=1#LeverageProxyCaching)