---
layout: name
title: Home

section: Home
---


<table border='0'>
<tr>
	<td>
		<img src="http://www.cs.princeton.edu/~wclarkso/images/mona_30s.png" height='150'>

		<img src="http://www.cs.princeton.edu/~wclarkso/images/ets-077-004-top_6_4.jpg" height='150'>
				<img src="http://www.cs.princeton.edu/~wclarkso/images/sum.png" height='150'>

	</td>
</tr>
</table>

+-- {.section}
Obligatory Bio
=======
I'm William (Will) Clarkson, a 5th year Ph.D. Candidate in <a href="http://www.cs.princeton.edu">Computer Science</a> at Princeton University. I'm a member of the [Security Group](http://security.cs.princeton.edu) and the [Center for Information Technology Policy](http://citp.princeton.edu). My advisor is [Ed Felten](http://cs.princeton.edu/~felten/) is currently on leave as the <a href="http://www.ftc.gov/opa/2010/11/cted.shtm">Chief Technologist</a> for the FTC. I graduated in 2003 from <a href="http://www.tulane.edu">Tulane University</a> with a degree in Computer Engineering. I spent a summer working at Diebold Inc. in their security group, and a few summers at Google working on various projects.

In my free time I attend as many blues concerts as time allows, and I enjoy finding less well known artists. 
=--

+-- {.section}
Research
=======
My research interests focus on re-evaluating  assumptions about the indistinguishability of seemingly identical or anonymous items. In each of the items I've studied, they each have distinguishing physical features, often inherent to the item, that allow them to be identified by measuring that feature with a cheap sensor -- e.g. desktop scanner. At the completion of my Ph.D. I will be joining Google.
=--

+-- {.section}
Publications
========
<ul>
 	{% for p in site.categories.publications %}
    
    {{p.year}} {{p.title}} <br>

	{% endfor %}
</ul>
For abstracts, PDF and BibTex, see my <a href="http://www.cs.princeton.edu/~wclarkso/publications/index.html">Publications</a>.
=--
