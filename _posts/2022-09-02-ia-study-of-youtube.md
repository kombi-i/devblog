---
layout: post
title: "IA Study of Youtube"
date: 2022-09-02 20:00:37 +0900
categories: study
---
​
## Introduction
​
---
​
In order to learn more about Information Architectures, I drew out the IA for the Youtube app.
​
It isn't a full IA, since it doesn't contain some buttons & context menus (for example the search settings), but it should give you a general idea of the basic overview of youtube.
​
![Information Architecture of Youtube](/devblog/assets/IAimg.png)
_Figure. IA of Youtube_
​
## Suggestions
​
---
​
With an app that focuses around videos, it would make sense that most of the nodes would point back to videos. In fact, the Create tab is the only one that doesn't eventually point back to a video.
​
One new addition to the app makes navigation kind of confusing. Shorts were implemented a few years ago as a way for Youtube to have short-form video content, which is extremely popular now.
​
So, they implemented a new homepage just for Shorts.
However, the search bar on the homepage also takes you to Shorts content. In addition to this, some Shorts style videos(short form, vertical video) are just uploaded as regular Youtube videos, and show up in your normal homepage feed.
​
Despite there being a deliberate segregation of content through the seperate tabs, content is mixed in the homepage search bar.