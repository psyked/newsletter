---
layout: page
title: Responsive Images (in 10 minutes)
description: Responsive Images (in 10 minutes)
category: presentations
tags: [images, presentations]
image:
  feature: responsive-web-design.jpg
---
## Introduction

What's the correct approach to the responsive images conundrum? Is it the fabled `<picture>` element? What about `srcset`? How about just doing it with Javascript, or does the solution lie somewhere else entirely?

In this presentation we looked at all of these, their limitations and their strengths, and examined which of these can actually be used _today._

<div class="fluidMedia">
    <iframe src="https://docs.google.com/presentation/d/1cktnpwyXfKdPyYuvcG0LhyjqOiBl4JbCkjGlMBbonNg/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

## Summary

- Javascript-based solutions give us the best cross-browser support.
- SVG and the 'Clown Car' technique gives us the most complete feature set for todays' browsers, works in [practically all browsers](http://caniuse.com/#feat=css-mediaqueries,svg), but it's difficult to generate and manage those files.
- **srcset** is available in the [latest version of Chrome](http://caniuse.com/srcset), but it doesn't cover all of the possible 'responsive image' definitions.
- The **Picture** element is touted as the future, but the spec is not settled and no browsers implement it yet.

All of these techniques have their benefits, and there's decent polyfill libraries available for them, so a lot of the choices come down to evaluating the manageability of the solution and the importance of the element.

## Further Reading

- [Responsive Images Community Group](http://responsiveimages.org/)
- [Which responsive images solution should you use?](http://css-tricks.com/which-responsive-images-solution-should-you-use/)
- [A Q&A on the Picture Element](http://alistapart.com/blog/post/picture-element-qa)
- [HTML5 adaptive images: end of round one](http://html5doctor.com/html5-adaptive-images-end-of-round-one/)
- [Srcset and sizes](http://ericportis.com/posts/2014/srcset-sizes/)
