---
layout: page
---



<h2><b>Biography</b></h2>

<div style="overflow: hidden;">
    <img align="left" src="{{site.baseurl | prepend: site.url}}/Files/Images/Alvaro Carreno.png"
         width="200" height="200" alt="Alvaro Carreno" 
         style="margin-right: 25px; margin-bottom: 10px;"/>
    <div style="text-align: justify;">
        <b>ALVARO CARRENO</b> received the Engineer and M.Sc. degrees in electronic engineering 
        from Universidad Tecnica Federico Santa Maria, Valparaiso, Chile, in 2015 and 2018, 
        respectively, and the dual Ph.D. degree in electrical and electronics engineering from 
        Warsaw University of Technology, Warsaw, Poland, and Universidad Tecnica Federico Santa 
        Maria, Valparaiso, Chile, in 2024.<br>
        His main research interests include hybrid distribution transformers, grid-connected 
        converters, and digital control of power converters.
    </div>
</div>


<h2><b>Contact information</b></h2>

  <div style="line-height:120%;">
    email: <a href="mailto:{{ site.email }}">{{ site.email }}</a>
    <br>
    <a href="https://orcid.org/0000-0002-9545-662X">ORCID</a>
    <br>
    <a href="https://scholar.google.com/citations?user=CxRSWH4AAAAJ&hl=en&authuser=1">Google Scholar</a>
    <br>
    <a href="https://www.researchgate.net/profile/Alvaro-Carreno">ResearchGate</a>
  </div>

<br>

<h2><b>Available Engineering and Master projects</b></h2>

<div style="text-align: justify;"> Dissertation topics for engineering and master students are available below. Please, contact me at <a href= "mailto: {{ site.email }}">{{ site.email }}</a>.
</div>

<ul>
  {% for post in site.posts %}
    {% if post.tags contains 'Projects' and post.tags contains 'Available' %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

<!--<h2><b>Students</b></h2>-->
<!---->
<!--<ul>-->
<!--  {% for post in site.posts %}-->
<!--    {% if post.tags contains 'Projects' and post.tags contains 'Taken' %}-->
<!--      <li>{{ post.student }}, {{ post.grade }}, {{ post.semester }}, <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>-->
<!--            -->
<!--    {% endif %}-->
<!--  {% endfor %}-->
<!--</ul>-->


