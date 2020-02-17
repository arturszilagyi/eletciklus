{% for post in site.posts %}
# [{{ post.title }}]({{ post.url }})
*{{ post.datum }}*

{{ post.excerpt }}
{% endfor %}
