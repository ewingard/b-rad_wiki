---
layout: default
title: NetStation Tutorials
long_title: Tutorials on how to use NetStation
has_children: true
has_toc: true
nav_order: 2
---
# NetStation Links
The pages in this section describe how to use NetStation with resources and tutorials.

<h3><a href="/netstation"><span style="color: black;">NetStation Tutorial</span></a></h3>
{%- assign children_list = site.pages | where: "parent", page.title -%}
{% include toc_nav_recursive.html nav=children_list %}

<!-- ### Quick Start
[Getting Started with NetStation](/netstation/02_quick-start/index.md)

### Troubleshooting Common Errors
[Troubleshooting Netstation Errors](/netstation/01_troubleshooting/index.md)

### Using NetStation for EEG Recording during Tasks
[NetStation Task Setup](/netstation/03_task-setup/index.md)
[Data Backup after EEG Recording](/netstation/04_mffs/index.md) -->
