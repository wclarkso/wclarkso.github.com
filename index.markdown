---
layout: name
title: Home

section: Home
---
<img class='inset right' title='Will Clarkson' height="250" src='/images/PersonalPicture.jpg'/>


I'm Will Clarkson, a Ph.D. Candidate in Computer Science at Princeton University. I'm a member of the [Security Group](http://security.cs.princeton.edu) and the [Center for Information Technology Policy](http://citp.princeton.edu). My advisor is [Ed Felten](http://cs.princeton.edu/~felten/). My (professional) interests range from applied cryptography and biometrics to privacy and information technology policy more generally. 

+--	{.section}
Interests
========
I'm a 3rd year graduate student at Princeton University [Computer Science Department](http://www.cs.princeton.edu)
=--

<br>


+-- {.section}
Recent Publications
========
 <ul>
 	{% for p in site.categories.publications %}
    
    	{{p.year}} {{p.title}} <br>

	{% endfor %}
 </ul>
=--
