---
permalink: "/nptel.html"
title: Online Videos and Courses
layout: default
---
# Online Videos and Courses

## System Commands

As part of [Online BSc in Programming and Data Science](https://onlinedegree.iitm.ac.in/) on [System Commands](https://onlinedegree.iitm.ac.in/course_pages/BSCSE2001.html), the youtube links for videos are linked here:

<table>
<tr>
<th>#</th>
<th>Title</th>
<th>URL</th>
<th>Duration (mm.ss)</th>
</tr>
{% assign videos = site.data.bscvideos %}
{% assign n = 0 %}
{% for item in videos %}
{% assign n=n|plus:1 %}
   <tr>
   <td>
   {{ n }}
   </td>
   <td>
   {{ item.title }}
   </td>
   <td>
   <a href="https://www.youtube.com/watch?v={{ item.url }}">{{ item.url }}</a>  
   </td>
   <td>
   {{ item.duration }}
   </td>
   </tr>
{% endfor %}

</table>


## Transport Phenomena in Materials 

As part of [NPTEL MOOC](https://onlinecourses.nptel.ac.in/) on [Transport Phenomena in Materials](https://onlinecourses.nptel.ac.in/noc18\_me09/), the youtube links for videos are linked here:

<table>
<tr>
<th>#</th>
<th>Title</th>
<th>URL</th>
<th>Duration (mm.ss)</th>
</tr>
{% assign videos = site.data.tpvideos | sort:"seq" %}
{% assign n = 0 %}
{% for item in videos %}
{% assign n=n|plus:1 %}
   <tr>
   <td>
   {{ n }}
   </td>
   <td>
   {{ item.title }}
   </td>
   <td>
   <a href="https://www.youtube.com/watch?v={{ item.url }}">{{ item.url }}</a>  
   </td>
   <td>
   {{ item.duration }}
   </td>
   </tr>
{% endfor %}

</table>


## Introduction to Research

As part of [NPTEL MOOC](https://onlinecourses.nptel.ac.in)  on [Introduction to Research](https://onlinecourses.nptel.ac.in/noc16\_ge01), the youtube links for videos on group discussion and the module on literature survey are here:

<table>
<tr>
<th>#</th>
<th>Title</th>
<th>URL</th>
<th>Duration (mm.ss)</th>
</tr>
{% assign videos = site.data.resvideos | sort:"seq" %}
{% assign n = 0 %}
{% for item in videos %}
{% assign n=n|plus:1 %}
   <tr>
   <td>
   {{ n }}
   </td>
   <td>
   {{ item.title }}
   </td>
   <td>
   <a href="https://www.youtube.com/watch?v={{ item.url }}">{{ item.url }}</a>  
   </td>
   <td>
   {{ item.duration }}
   </td>
   </tr>
{% endfor %}

</table>

## Teaching Learning Centre

Here are few videos I prepared for various activities under our [TLC](https://tlc.iitm.ac.in/).

<table>
<tr>
<th>#</th>
<th>Title</th>
<th>URL</th>
<th>Duration (mm.ss)</th>
</tr>
{% assign videos = site.data.tlcvideos | sort:"seq" %}
{% assign n = 0 %}
{% for item in videos %}
{% assign n=n|plus:1 %}
   <tr>
   <td>
   {{ n }}
   </td>
   <td>
   {{ item.title }}
   </td>
   <td>
   <a href="https://www.youtube.com/watch?v={{ item.url }}">{{ item.url }}</a>  
   </td>
   <td>
   {{ item.duration }}
   </td>
   </tr>
{% endfor %}

</table>




## Analysis and Modeling of Welding 

As part of [NPTEL MOOC](https://onlinecourses.nptel.ac.in)  on [Analysis and Modeling of Welding](https://onlinecourses.nptel.ac.in/noc16\_mm02)  the youtube links for videos are here:

<table>
<tr>
<th>#</th>
<th>Title</th>
<th>URL</th>
<th>Duration (mm.ss)</th>
</tr>
{% assign videos = site.data.amwvideos | sort:"seq" %}
{% assign n = 0 %}
{% for item in videos %}
{% assign n=n|plus:1 %}
   <tr>
   <td>
   {{ n }}
   </td>
   <td>
   {{ item.title }}
   </td>
   <td>
   <a href="https://www.youtube.com/watch?v={{ item.url }}">{{ item.url }}</a>  
   </td>
   <td>
   {{ item.duration }}
   </td>
   </tr>
{% endfor %}

</table>


Watch this space for updates.
