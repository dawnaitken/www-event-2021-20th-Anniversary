---

title: Supporters
layout: event_noheader-2.0
permalink: /supporters/

---

{% for supporter in site.data.supporters %}
<div style="float:left;margin-right:24px;"><a href="{{supporter.url}}"><img src="{{supporter.logo}}"/></a></div>
{% endfor %}

<div style="height:250px"></div>