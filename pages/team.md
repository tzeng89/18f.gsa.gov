---
layout: bare
permalink: /team/
title: 18F People
---
# {{ page.title }}

18F is a growing group of technologists, designers, and researchers from around the country. You can find us in Washington, San Francisco, Chicago, New York, Dayton, and a handful of other cities. Click through the learn more about the amazing staff that is reshaping government services.

<ul class="sortable">Sort by:
	<li><a href="?sort=none">name</a></li>
	<li><a href="?sort=loc">location</a></li>
	<li><a href="?sort=team">team</a></li>
</ul>

<div class="container team">{% for member in site.data.team %}
	<div class="bio"><a href="/team/{{member[0]}}/">{{ member | with_pic }}</a></div>
{% endfor %}</div>