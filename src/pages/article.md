---
layout: blog.njk
title: Articles
date: 2017-01-01
pagination:
  data: collections.post
  size: 6
  reverse: true
permalink: "article{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html"
metaDescription: A sample Blog page listing various posts.
subtitle: A collection of technical blog posts and random thoughts
eleventyNavigation:
  key: Article
  order: 2
---
Browse articles by [National Association for Science Writers (NASW)]({{ '/tags/nasw' | url }}), [TheSTEMTimes]({{ '/tags/thestemtimes' | url }}), [SciRio]({{ '/tags/scirio' | url }})