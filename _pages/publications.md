---
layout: publications
title: ""
permalink: /publications/
author_profile: true
---

### Submitted manuscripts (under review)
<ul class="preprint_list">
{% assign number_printed = 0 %}
{% for publi in site.data.publication_list %}
{% if publi.type == "preprint" %}

<li ><p>
<b>{{ publi.title }}</b> ({{ publi.year }})
<br>{{ publi.authors }}<br>
<a href="javascript:toggleBibtex('{{ publi.label }}')" style="color:rgb(199, 21, 133,0.75);">[BibTeX]</a>
<a href="{{ publi.link_pre.url }}" target="_blank" style="color:rgb(199, 21, 133,0.75);">[Preprint]</a> 
</p>
<div id="bib_{{ publi.label }}" class="bibtex noshow">
<pre>
{{ publi.bibtex }}
</pre>
</div>
</li>

{% endif %}
{% endfor %}

</ul>

### Publications in peer-reviewed journals and book chapters
<!-- Generated from JabRef by PubList by Truong Nghiem at 11:44 on 2015.09.10. -->
<ul class="biblist">

{% assign number_printed = 0 %}
{% for publi in site.data.publication_list %}
{% if publi.type == "journal" %}

<li ><p>
<b>{{ publi.title }}</b> ({{ publi.year }}) <br>{{ publi.authors }}<br> <i>{{ publi.link_main.display }}</i>
<br> 
<a href="{{ publi.link_main.url }}" target="_blank" style="color:rgb(199, 21, 133,0.75);">[Link]</a>
<a href="javascript:toggleBibtex('{{ publi.label }}')" style="color:rgb(199, 21, 133,0.75);">[BibTeX]</a>
<a href="{{ publi.link_pre.url }}" target="_blank" style="color:rgb(199, 21, 133,0.75);">[Preprint]</a> 
</p>
<div id="bib_{{ publi.label }}" class="bibtex noshow">
<pre>
{{ publi.bibtex }}
</pre>
</div>
</li>

{% endif %}
{% endfor %}

</ul>

### Publications in peer-reviewed conference proceedings
<ul class="biblist">

{% assign number_printed = 0 %}
{% for publi in site.data.publication_list %}
{% if publi.type == "inproceeding" %}

<li ><p>
<b>{{ publi.title }}</b> ({{ publi.year }})
<br>{{ publi.authors }}<br>
<i>{{ publi.link_main.display }}</i>
<br> 
<a href="{{ publi.link_main.url }}" target="_blank" style="color:rgb(199, 21, 133,0.75);">[Link]</a>
<a href="javascript:toggleBibtex('{{ publi.label }}')" style="color:rgb(199, 21, 133,0.75);">[BibTeX]</a>
<a href="{{ publi.link_pre.url }}" target="_blank" style="color:rgb(199, 21, 133,0.75);">[Preprint]</a> 
</p>
<div id="bib_{{ publi.label }}" class="bibtex noshow">
<pre>
{{ publi.bibtex }}
</pre>
</div>
</li>

{% endif %}
{% endfor %}

</ul>

### Thesis
* [Multilevel minimization in trust-region framework - Algorithmic and software developments., style="color:rgb(199, 21, 133,0.75);"](https://doc.rero.ch/record/330121/files/2020INFO021.pdf)<br> _PhD thesis_, Università della Svizzera italiana, **2020**
