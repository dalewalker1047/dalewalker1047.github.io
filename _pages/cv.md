---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Engineering, Virginia Tech 2025 (Expected)
* M.S. Virginia Tech, 2027 (Expected)

Work experience
======
* Undergraduate Researcher, System Software Research Group (September 2022, February 2024) 
  * Furthered an existing papers completeness using reverse engineering tool Ghidra, java scripts, and Pcode
  * Learned and applied rewrite based executable semantic framework K 
  * Learned Haskell for verification work on Ebpf instructions 
  * Quickly learned many new languages and skills to complete various tasks
    
Skills
======
* C++
* C
* Python
* SystemVerilog
  * Verilog
* Operating Systems
  * Windows
  * Linux
  * Windows Subsystem for Linux 

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
