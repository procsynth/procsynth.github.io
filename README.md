<ul>
	{% for url in site.static_files %}
	<li><a href="{{ site.baseurl | escape }}{{ url.path | escape }}">{{ url.path | escape }}</a> </li>
	{% endfor %}
</ul>