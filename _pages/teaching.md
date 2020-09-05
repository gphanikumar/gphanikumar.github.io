---
permalink: "teaching.html"
title: Teaching
layout: default
---
# Courses

Lecture schedule and course information are now hosted in the [Moodle](https://courses.iitm.ac.in/) site.

<table>
<tr>
<th>Period</th>
<th>Course</th>
<th>Students</th>
<th>Remarks</th>
</tr>
{% for item in site.data.courses %}
   <tr>
   <td>
   {{ item.year }} {{ item.sem }} 
   </td>
   <td>
   {{ item.num }}:{{ item.name }} 
   </td>
   <td>
   {{ item.students }}
   </td>
    <td>
   {{ item.remarks }}
   </td>
   </tr>
{% endfor %}

</table>
