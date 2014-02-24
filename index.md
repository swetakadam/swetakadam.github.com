---
layout: page
title: Sweta's Blog 
tagline: Exploring stuff ...
---


I set up this blog using Jekyll  ... when my friend passed me an article of how to set up a Blog on github in less than 3 minutes.
It took me say under 10 minutes ... as I had some issues with my mac ...
After downloading xcode-command line tool .. things worked for me.
## Start Blogging !!! 
Need to add cool stuff !!!
    
## Sample Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. Need to spare some time to make it look beautiful !!!


