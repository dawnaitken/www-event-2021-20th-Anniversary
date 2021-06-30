---

title: Supporters
layout: event_noheader-2.0
permalink: /supporters/

---

{% for supporter in site.data.supporters %}
<div style="float:left;"><a href="{{supporter.url}}" class="supporter-logo"><img src="{{supporter.logo}}"/></a></div>
{% endfor %}

<div style="height:250px"></div>