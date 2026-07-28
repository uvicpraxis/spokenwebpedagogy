---
layout: home
---
Welcome to SpokenWeb Pedagogy, a [collection](collection.html) of materials for learning and teaching literary sound studies. 

The SSHRC-funded [SpokenWeb](https://spokenweb.ca/) partnership aims to develop coordinated and collaborative approaches to literary historical study, digital development, and critical and pedagogical engagement with diverse collections of literary sound recordings from across Canada and beyond.

## About 

All files in the collection were converted into [Markdown](https://daringfireball.net/projects/markdown/) using the [SWTools](https://github.com/callumyci/SWTools) script. 

[Documentation](https://github.com/callumyci/SWTools/blob/main/README.md) for the SWTools script describes how it automatically converts pedagogical materials (such as course outlines, lesson plans, and workshop instructions written in a word processor) into Markdown using [Pandoc](https://pandoc.org/). 

The script also generates associated [YAML](https://yaml.org/) metadata files from a metadata spreadsheet (XLSX). YAML for each file includes metadata for the title, layout, filename, permalink, document type, discipline, affiliated project URL, and author's name(s), institution(s), and email address(es). 

The collection is designed to be published to a [Jekyll](https://github.com/jekyll)-based web instance. It uses the [Minima](https://github.com/jekyll/minima) theme. 

Project developer: Callum Carroll-Ireton (UVic)    
Project editor: Jentery Sayers (UVic)    
Project communications: Joel Wheeler (UVic)  
Project host and maintenance: Praxis Studio (UVic)   
SpokenWeb director and PI: Jason Camlot (Concordia)   

## Roadmap (as of 28 July 2026) 

* Copy-edit the collection (~ 16 October 2026). 
* Circulate the collection for public use (~ 16 October 2026).

Note: this project is no longer in active development, and we are no longer accepting contributions. Thank you for understanding. 

<footer class="site-footer h-card">
  <data class="u-url" href="{{ "/" | relative_url }}"></data>

  <div class="wrapper">

    <h2 class="footer-heading">{{ site.title | escape }}</h2>

    <div class="footer-col-wrapper">
      <div class="footer-col footer-col-1">
        <ul class="contact-list">
          <li class="p-name">
            <p>a <a href="https://spokenweb.ca/">SpokenWeb</a> project</p>
            <!--
            {%- if site.author -%}
              {{ site.author | escape }}
            {%- else -%}
              {{ site.title | escape }}
            {%- endif -%}
            </li>
            {%- if site.email -%}
            <li><a class="u-email" href="mailto:{{ site.email }}">{{ site.email }}</a></li>
            {%- endif -%} -->
        </ul>
      </div>

      <div class="footer-col footer-col-2">
        {%- include social.html -%}
      </div>

      <div class="footer-col footer-col-3">
        <p>project status: proof of concept<br>
        last updated: 28 July 2026</p>
        <!--p>{{- site.description | escape -}}</p-->
      </div>
    </div>

  </div>

</footer>
