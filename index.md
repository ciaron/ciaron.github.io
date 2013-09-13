---
layout: page
title: All blog posts
tagline: 
---
{% include JB/setup %}

{% for post in site.posts %}
## <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
#### <span>{{ post.date | date_to_string }}</span>


{{ post.content }}
***
{% endfor %}


