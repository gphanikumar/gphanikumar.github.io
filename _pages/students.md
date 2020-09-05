---
permalink: "/students.html"
title: Current Students
layout: default
---
# Current students

<table>
<tr>
<th>Name</th>
<th>Program</th>
<th>Title</th>
<th>Remarks</th>
</tr>
{% assign students = site.data.stu | sort: 'prog' %}
{% for item in students %}
   <tr>
   <td>
   <a href="{{item.url}}.html">{{ item.name }}</a> {{ item.roll }} 
   </td>
   <td>
   {{ item.prog }}
   </td>
   <td>
   {{ item.title }}
   </td>
    <td>
   {{ item.remarks }}
   </td>
   </tr>
{% endfor %}

</table>


