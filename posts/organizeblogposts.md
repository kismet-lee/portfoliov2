---
layout: layouts/post.njk
title: Organize blog posts
description: This is the third blog post! How do I organize my blogs?
date: 2026-11-26
featuredImage: /assets/web-image.webp
tags: "posts"
---

Welcome to the third blog post. I've learned how to make my blog posts show up at the proper url, began styling the blog page, and will then style the blog post page. But I've run into a new curiosity. 

How do I organize my blog posts by date? It seems all of the newer ones are descending instead of ascending. I will try to use the flex-direction: column reverse first. But that's only a momentary fix. I will need to actually allow people to filter the posts properly.  (I've completed this with column reverse, FOR NOW.)

Next, I will add tags for my blog posts. I know it's a low-priority thing. So, I won't really focus on it too much for right now. I guess that's where DECAP CMS will come in. Another low priority add will be adding a share button on top of the blog posts in the list or on the actual page. This could grab the url of each post and copy it to the clip board. I know that this will require some JS. I will refer to the small project's code I'm making everyone do for the linktree project.

After that, I will be sure to add a 'back to home' button and 'back to blog' button at the bottom of each blog post. I'm wondering if it should also have other links such as previous blog and next blog. But it's a minute thing.

The logo also needs to link back to the homepage, so I will adjust the base.njk template properly. (I've completed this)

I'm having a lot of fun with 11ty actually. Eventually, I will need to adjust the SEO for each page. I'm wondering how I can do that when I've connected all of my headers through the template?

As of right now, the blog list looks great. I will need to incorporate pagination though (and figure out where that needs to appear, maybe within my postslist.njk file?) After I incorporate pagination after 5 posts and add a way to filter them, I will the edit how the post template actually looks. (I've completed this)