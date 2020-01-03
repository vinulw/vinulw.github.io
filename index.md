Check out some of the stuff that I have been writing about:

{% for post in site.posts %}
  <h2 class='post'><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <span> {{ post.date  | date: '%d %B %Y' }} </span>
{% endfor %}

If you want to find out more about me check out my [about me](about) page.
