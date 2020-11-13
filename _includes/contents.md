## Table of Contents

{% for item in site.data.contents %}
## [{{ item.chapter }}]({{ item.link }}) - {{ item.name }}
<!-- ## [{{ item.chapter }}]({{ item.link }}) -->
{% endfor %}
