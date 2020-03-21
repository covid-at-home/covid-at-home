## Backstage

### Do not translate this page ###

This page is just a handy collection of links, for example to get to the different country sites, their github pages and their webstats.

### Language sites

Language | English |  |  |  
--- | --- | --- | --- | --- | ---
{% for language in site.data.languages.languages %}{{ language.title }} | {{ language.english }} | [site]({{ language.url }}) | [GitHub]({{ language.github }}) | [stats]({{ language.stats }}){% endfor %}