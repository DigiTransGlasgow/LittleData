
<div id="index-page">

<h2>Projects from the AHRC Digital Transformations Theme</h2>

{% for item in site.contributions %}
<a class="titles" href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>
{% endfor %}

</div>
