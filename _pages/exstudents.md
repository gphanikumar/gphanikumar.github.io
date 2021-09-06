---
permalink: "/exstudents.html"
title: Ex-students
layout: default
---
# Ex-students

Here is the list of students who have worked with me in the past.

## Ph.D.

<table>
<tr>
<th>Name</th>
<th>Year</th>
<th>Title</th>
<th>Remarks</th>
</tr>
{% assign students = site.data.phd | sort: 'year' %}
{% for item in students %}
   <tr>
   <td>
   <a href="{{item.url}}.html">{{ item.name }}</a> {{ item.roll }}
   </td>
   <td>
   {{ item.year }}
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

## MS + Ph.D.

<table>
<tr>
<th>Name</th>
<th>Year</th>
<th>Title</th>
<th>Remarks</th>
</tr>
{% assign students = site.data.msphd | sort: 'year' %}
{% for item in students %}
   <tr>
   <td>
   <a href="{{item.url}}.html">{{ item.name }}</a> {{ item.roll }}
   </td>
   <td>
   {{ item.year }}
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

## M.S. (by Research)

<table>
<tr>
<th>Name</th>
<th>Year</th>
<th>Title</th>
<th>Remarks</th>
</tr>
{% for item in site.data.ms %}
   <tr>
   <td>
   <a href="{{item.url}}.html">{{ item.name }}</a> {{ item.roll }}
   </td>
   <td>
   {{ item.year }}
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


## M.Tech

<table>
<tr>
<th>Name</th>
<th>Year</th>
<th>Title</th>
<th>Remarks</th>
</tr>
{% assign students = site.data.mtech | sort: 'year' %}
{% for item in students %}
   <tr>
   <td>
   <a href="{{item.url}}.html">{{ item.name }}</a> {{ item.roll }}
   </td>
   <td>
   {{ item.year }}
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

## Dual Degree (B.Tech + M.Tech)

<table>
<tr>
<th>Name</th>
<th>Year</th>
<th>Title</th>
<th>Remarks</th>
</tr>
{% assign students = site.data.dd | sort: 'year' %}
{% for item in students %}
   <tr>
   <td>
   <a href="{{item.url}}.html">{{ item.name }}</a> {{ item.roll }}
   </td>
   <td>
   {{ item.year }}
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

## Inter-disciplinary Dual Degree (B.Tech + M.Tech)

<table>
<tr>
<th>Name</th>
<th>Program</th>
<th>Year</th>
<th>Title</th>
<th>Remarks</th>
</tr>
{% assign students = site.data.iddd | sort: 'year' %}
{% for item in students %}
   <tr>
   <td>
   <a href="{{item.url}}.html">{{ item.name }}</a> {{ item.roll }}
   </td>
   <td>
   {{ item.prog }}
   </td>
   <td>
   {{ item.year }}
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


## B.Tech

<table>
<tr>
<th>Name</th>
<th>Year</th>
<th>Title</th>
<th>Remarks</th>
</tr>
{% assign students = site.data.btech | sort: 'year' %}
{% for item in students %}
   <tr>
   <td>
   <a href="{{item.url}}.html">{{ item.name }}</a> {{ item.roll }}
   </td>
   <td>
   {{ item.year }}
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


## Project Staff
  * Gerald Tennyson (August-2006 to July-2007), ISRO Project on setting up of national electromagnetic levitation facility 
  * Arun Kumar (July-2007 to July-2008), ISRO Project on setting up of national electromagnetic levitation facility
  * M. Manivannan (Jan-2008 to Aug-2009), ISRO project on setting up national electromagnetic levitation and GM Project on Solidification of Al alloys
  * N.R. Ravi (Jan-2008 to Jan-2010), GM Project on solidification of Al-based eutectic alloys
  * Kamatchi Priya
  * Allan Roy
  * A.R.G. Sreekar

