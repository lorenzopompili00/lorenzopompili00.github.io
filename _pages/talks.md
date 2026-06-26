---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

Selected talks, seminars, and panels in reverse chronological order.

<div class="talks-timeline">
{% assign last_year = "" %}
{% for t in site.data.talks %}{% if t.year != last_year %}<div class="talks-year">{{ t.year }}</div>{% assign last_year = t.year %}{% endif %}{% include talk-item.html t=t %}{% endfor %}
</div>
