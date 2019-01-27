---
layout: default
title: Service
---

<div>
<h1>Scientific Community Service</h1>
<h3>Program Committee Member</h3>
<ul>
	{% for item in site.data.program_committee_members %}
	<li class="pc-element">
	{{ item.name }}
        </li>
{% endfor %}
</ul>
<h3 id="reviewer">External Reviewer</h3>
<ul>
	{% for item in site.data.external_reviewers %}
	<li class="pc-element">
	{{ item.name }}
        </li>
{% endfor %}
</ul>
</div>