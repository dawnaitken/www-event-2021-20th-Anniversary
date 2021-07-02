---

title: Supporters
layout: event_noheader-2.0
permalink: /supporters/

---
<section class="member-list">
{% for supporter in site.data.supporters %}
{%- if supporter.logo -%}
<div style="float:left;"><a href="{{supporter.url}}" class="supporter-logo" style="filter:none;"><img src="{{supporter.logo}}"/></a></div>
{% else %}
<div style="float:left;"><a href="{{supporter.url}}" class="supporter-logo" style="filter:none;">{{supporter.name}}</a></div>
{%- endif -%}
{% endfor %}
</section>