---
layout: post
title:  "Progressive Enhancement Vs. Graceful Degradation"
date:   2015-09-08 16:39:10
categories: jekyll update
---
For one of my first assignments for Code Fellows, my instructor asked me to read Chapter 1 from of Aaron Gustafson’s Adaptive Web Design and write a blog post with my thoughts on the subject. Below are some of those thoughts.

The difference between progressive enhancement and graceful degradation can be confusing. Both approaches attempt to provide good user experiences, but they’re polar opposites in how they create that user experience.

Progressive enhancement takes a proactive approach to solving potential problems by focusing on the content first and the visual presentation second. It creates a baseline user experience that works for all browsers and gradually adds more advance features to those browsers that support them. Because of this, progressive enhancement doesn’t force users to upgrade their browsers or make the assumption that they know how to do this.

Graceful degradation applies a more prescriptive approach to web development. A web developer using graceful degradation may design and code a website using latest features supported in the newest browsers and only deal with potential problems in other browsers as they occur. If a user comes across a feature that isn’t supported in their browser (such as JavaScript), they may be told to upgrade their browser or to turn on JavaScript in order to experience everything on the website.

In this context, progressive enhancement seems like the ideal approach. It takes accessibility into account and creates a great user experience for everyone from the start. It does, however, seem unrealistic to use progressive enhancement all the time.

For example, if you’re working on a website that was originally built using graceful degradation, it wouldn’t be efficient to redo the entire website to follow the principles of progressive enhancement in order to solve a problem you’re facing. Doing so would require a redesign of the code, and there often isn’t time to do that in real production environments. In these situations, it would be faster and more efficient to create exceptions on a case-by-case basis for older browsers rather than start from scratch.
