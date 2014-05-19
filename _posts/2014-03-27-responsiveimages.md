---
layout: post
title: ...on "Responsive Images"
description: "Responsive Images (in 10 minutes)"
category: presentations
tags: [images, presentations]
image:
  feature: responsive-web-design.jpg
#  credit: Michael Rose
#  creditlink: http://mademistakes.com
comments: true
#  share: true
---
## Introduction

What's the correct approach to the responsive images conundrum? Is it the fabled `<picture>` element? What about `srcset`? How about just doing it with Javascript, or does the solution lie somewhere else entirely?

In this presentation we looked at all of these, their limitations and their strengths, and examined which of these can actually be used _today._

<div class="fluidMedia">
    <iframe src="https://docs.google.com/presentation/d/1cktnpwyXfKdPyYuvcG0LhyjqOiBl4JbCkjGlMBbonNg/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

## Summary

- Javascript-based solutions give us the best cross-browser support.
- SVG and the 'Clown Car' technique gives us the most complete feature set for todays' browsers, but it's difficult to generate and manage those files.
- Srcset is available in the latest version of Chrome, Safari and Firefox, but it doesn't cover all of the possible 'responsive image' definitions.
- The Picture element is touted as the future, but the spec is not settled and no browsers implement it yet.

All of these techniques have their benefits, and there's decent polyfill libraries available for them, so a lot of the choices come down to evaluating the manageability of the solution and the importance of the element.