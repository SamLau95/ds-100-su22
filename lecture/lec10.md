---
layout: page
title: Lecture 10 – Ordinary Least Squares (Multiple Linear Regression)
nav_exclude: true
---

# Lecture 10 – Ordinary Least Squares (Multiple Linear Regression)

Presented by Anirudhan Badrinath and Dominic Liu

Content by Fernando Pérez, Alvin Wan, Suraj Rampure, Allen Shen, Joseph Gonzalez, Andrew Bray, Josh Hug, Lisa Yan, Ani Adhikari, and Sam Lau

- [slides](https://docs.google.com/presentation/d/1MVSqxY1d1y-MsDfymplNdbuNGr_ViRTj40B1-GzdK0o/edit?usp=sharing){:target="_blank"}
- no code
- [recording](https://bcourses.berkeley.edu/courses/1515881/external_tools/78985){:target="_blank"}
- supplemental recording: [OLS Properties](https://youtu.be/dhG8GiZcyUE){:target="_blank"}

<!--
A reminder – the right column of the table below contains _Quick Checks_. These are **not** required but suggested to help you check your understanding.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th></th>
<th>Video</th>
<th>Quick Check</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>10.0</strong> <br />Formal definition of visualization. The purpose of visualization in the data science lifecycle.</td>
<td><iframe width="300" height="" src="https://youtube.com/embed/loW5f8KMkpQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></td>
<td></td>
</tr>
<tr>
<td><strong>10.1</strong> <br />Formal definition of visualization. The purpose of visualization in the data science lifecycle.</td>
<td><iframe width="300" height="" src="https://youtube.com/embed/jJEEYES-Drw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></td>
<td><a href="https://forms.gle/zgF41YvrS94UcvmcA" target="\_blank">10.1</a></td>
</tr>
<tr>
<td><strong>10.2</strong> <br />Different ways we can map from data to properties of a visualization.</td>
<td><iframe width="300" height="" src="https://youtube.com/embed/6cly3iD2B64" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></td>
<td><a href="https://forms.gle/8TiGEbRWGzg2p5MW8" target="\_blank">10.2</a></td>
</tr>
<tr>
<td><strong>10.3</strong> <br />Defining distributions, and determining whether or not given visualizations contain a distribution.</td>
<td><iframe width="300" height="" src="https://youtube.com/embed/7DaEWbSdBd4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></td>
<td><a href="https://forms.gle/soh84fja1hdsJVsx8" target="\_blank">10.3</a></td>
</tr>
<tr>
<td><strong>10.4</strong> <br />Bar plots as a means of displaying the distribution of a qualitative variable, as well as for plotting a quantitative variable across several different categories.</td>
<td><iframe width="300" height="" src="https://youtube.com/embed/-uclH1gmwuE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></td>
<td><a href="https://forms.gle/Qtbi1cgp5z984FcA9" target="\_blank">10.4</a></td>
</tr>
<tr>
<td><strong>10.5</strong> <br />Rug plots. Histograms, where areas are proportions. Reviewing histogram calculations from Data 8. Density curves as smoothed versions of histograms.</td>
<td><iframe width="300" height="" src="https://youtube.com/embed/j2cGxJTXask" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></td>
<td><a href="https://forms.gle/foWbG6rtV4VR3Pck7" target="\_blank">10.5</a></td>
</tr>
<tr>
<td><strong>10.6</strong> <br />Describing distributions of quantitative variables using terms such as modes, skew, tails, and outliers.</td>
<td><iframe width="300" height="" src="https://youtube.com/embed/XyVFj_ckvFg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></td>
<td><a href="https://forms.gle/GA8gG4V6mtvt9f5r5" target="\_blank">10.6</a></td>
</tr>
<tr>
<td><strong>10.7</strong> <br />Using box plots and violin plots to visualize quantitative distributions. Using overlaid histograms and density curves, and side by side box plots and violin plots, to compare multiple quantitative distributions.</td>
<td><iframe width="300" height="" src="https://youtube.com/embed/oGHNoTcJy6M" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></td>
<td><a href="https://forms.gle/6bPAg11auz5bUWzj9" target="\_blank">10.7</a></td>
</tr>
<tr>
<td><strong>10.8</strong> <br />Using scatter plots, hex plots, and contour plots to visualize the relationship between pairs of quantitative variables. Summary of visualization thus far.</td>
<td><iframe width="300" height="" src="https://youtube.com/embed/s-dRmP_8zd0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe></td>
<td><a href="https://forms.gle/68yHpG7P8pm1wtu98" target="\_blank">10.8</a></td>
</tr>
-->
