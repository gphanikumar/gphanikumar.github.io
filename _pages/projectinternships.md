---
permalink: "/projectinternships.html"
title: Project Internships
layout: default
---

# Project Internships

IIT Madras allows for summer internships for a period of 2 months with stipend to be paid from projects. For the summer 2019, following are few topics where I am able to host summer interns. Please write to me if you are interested.
  * GPU Programming: We have in-house developed codes using OpenCL for GPU programming. These are basically solvers for partial differential equations. One can take up a task to either convert some of these to work with CUDA or to extend features in OpenCL itself. Applicants need to show that they are good at programming and are either introduced to / willing to learn about GPU programming. Familiarity with Linux environment is a must.
  * Programming using OWL API: A set of tasks for web development using Java programming and OWL API are available. Applicants should know web development using Java programming. Familiarity with Linux environment is a must.
  * Programming using Python / SageMath : A set of tasks for curriculum development using Python and/or SageMath are available. Working knowledge using Jupyter notebook interface is a must. 
  * Programming in C++ on OpenFOAM platform: Development of solvers on OpenFOAM platform is of long term interest to our group. Students who have undergone a course in Heat Transfer, Fluid Mechanics / Transport Phenomena related topics can consider this. Familiarity with C++ is a must. 
  * Simulation of Additive Manufacturing / 3D Printing: Using Simufact-Additive, a set of simulations can be taken up in the topic of 3D printing. This task does not require programming experience but knowledge of Heat Transfer is a must.

# An advice

I have an advice for all the young students who write emails seeking internships. [Please read on](internships.html).

# Previous interns

Here are few interns who worked in my group in the past.


<table>
<tr>
<th>Name</th>
<th>Year</th>
<th>Program</th>
<th>Topic</th>
<th>Affiliation</th>
</tr>
{% assign students = site.data.interns | sort: 'year' %}
{% for item in students %}
   <tr>
   <td>
   {{ item.name }}
   </td>
   <td>
   {{ item.year }}
   </td>
   <td>
   {{ item.prog }}
   </td>
   <td>
   {{ item.topic }}
   </td>
    <td>
   {{ item.from }}
   </td>
   </tr>
{% endfor %}
</table>

