---
layout: post
title:  "Comparison and analysis of Hybrid Distribution Transformer configurations"
date:   2024-12-17 00:00:00 +0100
categories: jekyll update
tags: Projects Available
student:
grade:
semester:
---

<div style="text-align: justify;">
Hybrid Distribution Transformers (HDTs) combine a conventional distribution with a power electronics converter. Typically, a series-connected power converter is to control the output voltage of the HDT on the low-voltage side, providing a regulated supply voltage to the consumers. On the other hand, the current-controlled power converter is used to regulate the DC-Link of the HDT and to improve the power quality on the medium-voltage side.
</div>

<div style="text-align: center; margin-top: 10px; margin-bottom: 10px;">
    <img src="{{site.baseurl | prepend: site.url}}/Files/Images/Concept_HDT.png" width="500">
</div>

<div style="text-align: justify;">
There are many HDT configurations in the literature, differing on how the power converter is connected to the grid, the winding configuration of the distribution transformer, and the location of the power converters. Some HDT configurations are presented in the following table.
</div>

<div style="text-align: center; margin-top: 10px; margin-bottom: 10px;">
    <img src="{{site.baseurl | prepend: site.url}}/Files/Images/Configs_Main.png" width="700">
</div>

<h2>General tasks</h2>
<div style="text-align: justify;">
<ul>
<li>Generate simulation models with basic control algorithm for selected HDT configurations.</li>
<li>Comparison and analysis of the selected HDT configurations, considering parameters such as operating current and voltages of the power converter, circulating currents, and control capabilities.</li>
</ul>
</div>

Please, contact me at <a href= "mailto: {{ site.email }}">{{ site.email }}</a>.

