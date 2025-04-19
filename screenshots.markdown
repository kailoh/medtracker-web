---
layout: page
title: App Screenshots
permalink: /screenshots/
---

### Screenshots ###

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-bottom: 30px;">
  {% for i in (1..19) %}
    <a href="{{ '/assets/screenshots/' | append: i | append: '.png' | relative_url }}" target="_blank">
      <img src="{{ '/assets/screenshots/' | append: i | append: '.png' | relative_url }}" 
           alt="Screenshot {{i}}"
           style="width: 100%; border-radius: 25px; transition: transform 0.2s; border: 2px solid black;"
           onmouseover="this.style.transform='scale(1.05)'" 
           onmouseout="this.style.transform='scale(1)'"/>
    </a>
  {% endfor %}
</div>

