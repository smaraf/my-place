---
layout: post
title: "Setting up a Simple Site with Jekyll"
---

I'm impressed with how easy it was to set up this site. The documentation says "Get up and running in seconds" but that's not always the case. This time it was. I simply followed the [Quickstart](https://jekyllrb.com/docs/) article, and I was up and running in no time. I love that some things just came out of the box:

### Clean Theme

The default [Minima](https://github.com/jekyll/minima) theme is just what I wanted. A simple layout that allows me to set up some pages and easily create blog posts.

### Google Analytics

Setting up your google analytics account is as easy as adding ```google_analytics: UA-XXXXXXX-Y``` to the ```_config.yml``` file.

### Automagic deployment

I did not want to bother with hosting this. [GitHub Pages](https://pages.github.com/) has a magic integration with Jekyll sites. Magic as in _it works_ as soon you set the Source branch on your repo's Settings page. No deployment or configuration needed. If you're looking to set up a [user page](https://help.github.com/articles/user-organization-and-project-pages/#user-and-organization-pages-sites), you'll need to remember that the name of the repository needs to follow the ```<username>.github.io``` naming convention. In my case, this was ```smaraf.github.io```. It took a few minutes for the site to be up and running at https://smaraf.github.io/.


