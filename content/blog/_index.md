---
title: A Blog That Works
description: "This is a fully featured blog that supports categories, \ntags, series, and pagination.\n"
author: Alonso Otiniano @branext
show_post_thumbnail: true
thumbnail_left: true # for list-sidebar only (true show not in list-sidebar)
show_author_byline: true
show_post_date: true
show_button_links: true

layout: list-sidebar # list, list-sidebar, list-grid

sidebar:
  title: Your Thoughts Become Reality
  author: Alonso Otiniano Zavala @Branext
  description: "On this page you are going to read and interact with awesome developments in geology related to environmental geoscience, hydrogeology, geological hazards and geochemical engineering."
  text_link_label: Subscribe via RSS
  text_link_url: /index.xml
  show_sidebar_adunit: true # show ad container

cascade:
  author: Alonso Otiniano @branext
  show_author_byline: true
  show_comments: true  # see site config to choose Disqus or Utterances
  show_post_date: true
  # for single-sidebar layout
  sidebar:
    show_sidebar_adunit: false
    text_link_label: View recent posts
    text_link_url: /blog/
---

** No content below YAML for the blog _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside blog/. You may still override any of these by changing them in a page's front matter.**
