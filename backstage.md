## Backstage

### Do not translate this page ###

This page is just a handy collection of links, for example to get to the different country sites, their github pages and their webstats.

{% for language in site.data.languages.languages %}
{% if language.url != site.url and language.published %}
* {{ language.title }} - [site]({{ language.url }}) - [GitHub]({{ language.github }}) - [stats](language.stats)
{% endif %}
{% endfor %}