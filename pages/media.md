---

title: Event Pictures
layout: event_noheader
tags: event images
permalink: /media/

---

<section class="member-list">
<div>
{% assign images = site.data.media | where: "type", "image" %}
{% for img in images %}
<a href="{{img.url}}" class="member-logo" target="_blank" style="margin:30px; max-width:250px; max-height:250px;">
<img src="{{img.turl}}" style="max-height: 250px; max-width:250px;"/>
</a>
{% endfor %}
</div>
</section>