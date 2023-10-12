---
layout: plain
title: Projects
order: 4
---

### Ongoing Research Projects

Here are the research projects we are currently working on:

<table>
<col width="200px">
<col width="600px">
<tr>
  <th>Project</th>
  <th>Description</th>
</tr>
{% for entry in site.data.projects %}
<tr>
  <td>{{ entry.title }}</td>
  <td>{{ entry.description }} </td>
</tr>
{% endfor %}
</table>
