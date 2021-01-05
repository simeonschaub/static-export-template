# Helloo!

I am Jekyll?

{{ site.static_files }}

aaaa

<ul>
    {% for page in site.static_files %}
    <li>{{ page.path }}</li>
    {% endfor %}
</ul>

bbbb


<ul>
    {% for page in site.static_files %}
    <li>{{ page.path }} name: {{ page.name }} ext: {{ page.extname }}</li>
    {% endfor %}
</ul>

ccc

site.pages
<ul>
    {% for page in site.html_files %}
    <li><a href="{{ page.path | absolute_url }}">asdf {{ page.path }} name {{ page.name }}</a></li>
    {% endfor %}
</ul>
