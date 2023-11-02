---

title: Sponsors & Exhibitors
layout: event_noheader
permalink: /sponsors/

---

# {{ page.title }}
We would like to recognize our sponsors and exhibitors: 
{% if site.data.sponsors.size > 0 %}
{% assign diamond_plus = site.data.sponsors | where: "type", "Diamond Plus" | sort: "name" %}
{% assign diamonds = site.data.sponsors | where: "type", "Diamond" | sort: "name" %}
{% assign golds = site.data.sponsors | where: "type", "Gold" | sort: "name" %}
{% assign silvers = site.data.sponsors | where: "type", "Silver" | sort: "name" %}
{% assign lunch = site.data.sponsors | where: "type", "Lunch Sponsor" | sort: "name" %}
{% assign coffee = site.data.sponsors | where: "type", "Coffee Break Sponsor" | sort: "name" %}
{% assign network = site.data.sponsors | where: "type", "Networking Reception Sponsor" | sort: "name" %}
{% assign keynote = site.data.sponsors | where: "type", "Keynote Sponsor" | sort: "name" %}
{% assign lanyard = site.data.sponsors | where: "type", "Lanyard Sponsor" | sort: "name" %}
{% assign hotel = site.data.sponsors | where: "type", "Hotel Key Cards Sponsor" | sort: "name" %}
{% assign event = site.data.sponsors | where: "type", "Event Supporter" | sort: "name" %}

<section class='member'>
<div class='member-wrapper'>
<section class='member-list'>
<h3>Diamond Plus Exhibitors</h3>
<div class='event_member_div'>
{% for sponsor in diamond_plus %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Diamond Exhibitors</h3>
<div class='event_member_div'>
{% for sponsor in diamonds %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Gold Exhibitors</h3>
<div class='event_member_div'>
{% for sponsor in golds %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Silver Exhibitors</h3>
<div class='event_member_div'>
{% for sponsor in silvers %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Lunch Sponsors</h3>
<div class='event_member_div'>
{% for sponsor in lunch %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Coffee Break Sponsors</h3>
<div class='event_member_div'>
{% for sponsor in coffee %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Networking Reception Sponsors</h3>
<div class='event_member_div'>
{% for sponsor in network %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Keynote Sponsors</h3>
<div class='event_member_div'>
{% for sponsor in keynote %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Lanyard Sponsors</h3>
<div class='event_member_div'>
{% for sponsor in lanyard %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Hotel Key Cards Sponsors</h3>
<div class='event_member_div'>
{% for sponsor in hotel %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Event Supporters</h3>
<div class='event_member_div'>
{% for sponsor in event %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
</section>
</div>
</section>
<br><br>
<p>
<hr>
{% endif %}
