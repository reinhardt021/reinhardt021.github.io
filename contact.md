---
layout: page
title: Contact
permalink: /contact/
---

This page should be a Contact page, 
listing things like your e-mail address, 
and any social networks on which you can be found. 
{% if site.github_username %}
  {% include icon-github.html username=site.github_username %}
{% endif %}
{% if site.twitter_username %}
  {% include icon-twitter.html username=site.twitter_username %}
{% endif %}

<!-- Consider integrating something like SimpleForm to get a contact form on the page
 - form goes here
 - add more
 -->

<!-- You can find the source code for the Jekyll new theme at:
{% include icon-github.html username="jglovier" %} /
[jekyll-new](https://github.com/jglovier/jekyll-new)
 -->