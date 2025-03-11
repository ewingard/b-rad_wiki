---
layout: default
title: E-Prime Tutorials
long_title: Tutorials on how to use E-Prime
has_children: true
has_toc: true
nav_order: 1
---
# E-Prime Links
The pages in this section describe how to use E-Prime with resources and tutorials.

<h3><a href="/e-prime"><span style="color: black;">E-Prime Tutorial</span></a></h3>
{%- assign children_list = site.pages | where: "parent", page.title -%}
{% include toc_nav_recursive.html nav=children_list %}

<!-- ### Quick Start
[Getting Started with NetStation](/e-prime/02_quick-start/index.md)

### Troubleshooting Common Errors
[Troubleshooting Netstation Errors](/e-prime/01_troubleshooting/index.md)

### Using E-Prime to create Experimental Task Paradigms
[NetStation Task Setup](/e-prime/03_task-setup/index.md)
[Tutorials on E-Prime's Scripting Language, E-Basic](/e-prime/04_e-basic/index.md)
[Data Backup after Task Completion](/e-prime/05_data-export/index.md) -->