---
layout: page
title: What is trueColor3D ?
tagline: Bringing stereo3D to mobile users
---
{% include JB/setup %}
   
## Intro video
### This interview was made at the Campus Party 2012 in Berlin

<iframe src="http://player.vimeo.com/video/49552278" width="500" height="281" frameborder="0" webkitAllowFullScreen="true" mozallowfullscreen="true" allowFullScreen="true">
</iframe> <p/>

<br/>

<a href="http://vimeo.com/49552278">trueColor3D - Interview mit Thomas Kumlehn</a> from 
<a href="http://vimeo.com/alxhrt">Alex Hartmann</a> on 
<a href="http://vimeo.com">Vimeo</a>.
   
## Recent posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


