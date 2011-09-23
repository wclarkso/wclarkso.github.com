---
layout: publications
title: Publications
needs_js: y
---

Publications
========
<div id="full-page">
        <div class="entry-listing">
            <ul>
                {% for p in site.categories.publications %}
                <li>
                    <div class="pub-holder">
                        <div class="pub-title">
                        
                        {{p.title}}

                        <span class="pub-links">[{% for l in p.links %}{% unless forloop.first %}, {% endunless %}<a href="{{l.url}}">{{l.title}}</a>{% endfor %}]
                        </span>                      
                        
                        </div> 
                        
                        <div class="pub-other">
                    
                            <div class="pub-authors">
                            {% for a in p.authors %}{% unless forloop.first %}, {% endunless %}{% if forloop.last and forloop.length > 1 %}and {% endif %}{% for person in site.people%}{% if person.name == a.name and person.url %}<a href="{{person.url}}">{% endif %}{% endfor %}{{a.name}}{% for person in site.people%}{% if person.name == a.name and person.url %}</a>{% endif %}{% endfor %}{% endfor %}
                            </div>
                            
                            <div class="pub-details">
                            {% for d in p.details %}
                            {{d}}<br/>
                            {% endfor %}
                            
                            </div>

                            <div class="pub-toggle-controls">
                            <a class="abstract" href="#">Abstract</a> <a class="bibtex" href="#">BibTeX</a>
                            </div>

                            
                            <div class="pub-abstract">
                            {{ p.abstract }}
                            </div>

                            <div class="pub-bibtex">
                            <pre>{{ p.bibtex }}</pre>
                            </div>
                          
                        </div>
                    
                    </div>
                

                </li>
               {% endfor %}
                
            </ul>
        </div>
</div>



