---
layout: page
title: Ciaron Linstead
tagline: a blog
---
{% include JB/setup %}

{% for post in site.posts %}
## <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> 
<span>{{ post.date | date_to_string }}</span>
<p>{{ post.content }}</p>
{% endfor %}

### To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


