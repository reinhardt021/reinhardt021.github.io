---
layout: page
title: Contact
permalink: /contact/
---

The best places to find me are either in Vancouver / Mississauga / Waterloo.

Otherwise I am off exploring the world on another adventure.

Best way to reach me:
 - {% if site.email %} 
 {% include username=site.email %} 
 {% endif %}
 - {% if site.github_username %} 
 {% include icon-github.html username=site.github_username %} 
 {% endif %}
 - {% if site.twitter_username %} 
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