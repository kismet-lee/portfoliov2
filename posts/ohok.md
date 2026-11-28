---
layout: layouts/post.njk
title: Ohhh, okay
description: Some solutions!
date: 2026-11-29
featuredImage: /assets/web-image.webp
tags: "posts"
---

So I realized that after deleting and regenerating my _site folder to see if something was wrong with my code (my posts weren't showing up how they should, updated posts not showing) I needed to fix the permalinks on my homepage and base.njk for the blog landing page. There was not a file in my _site folder called blog.html which is why after regenerating the _site folder, my blog page stopped working. I could only access it through the blog/index.html folder. So I updated the links to /blog/ in my navigation bars.

Okay great, I got my blog page back. Now, I needed to learn how to do the pagination stuff. Here are some key points. I had includes and set on my blog page and one was overwriting the other which mean it wasn't rendering the blog posts properly for pagination. I had to remove the set and the blogs began populating. I can use them together, but not in this instance.

Consider the permalink and what you need to add to future blogs you make. You also need to add the permalink logic and html to the page you're putting the blogs on.

If I make a post.md without frontmatter information, it'll generate a blank post that only has time and date stuff. This is why a post showed up without a title on my page. I fixed it!