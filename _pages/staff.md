---
permalink: "/staff.html"
title: Project Staff
layout: default
---
# Project Staff

<table>
<tr>
<th>Name</th>
<th>Project</th>
<th>Remarks</th>
</tr>
{% assign staff = site.data.staff %}
{% for item in staff %}
   <tr>
   <td>
   <a href="{{item.url}}.html">{{ item.name }}</a> {{ item.id }} 
   </td>
   <td>
   {{ item.proj }}
   </td>
    <td>
   {{ item.remarks }}
   </td>
   </tr>
{% endfor %}

</table>


