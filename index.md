{% raw %}
{% for category in site.notes.docs | group_by:"category" %}
  <a href="/notes/{{ category.name }}" class="tag">{{ category.name }}</a>
{% endfor %}
{% endraw %}
