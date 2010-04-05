---
layout: name
title: Blog
needs_js: y
---
<div id="full-page">
        <div class="entry-listing">
             {% for p in site.categories.blog %}
             <div class="blog-title" >{{p.title}}</div><div class="blog-date">  on {{p.month}} {{p.day}}, {{p.year}}</div>
             {% if p.image_name %}
<img class="blog-image" src="/images/{{p.image_name}}"/> 
             {% endif %}
             <div class="blog-post">{{p.post}}</div><br>
             {% endfor %}
        </div>
</div>



