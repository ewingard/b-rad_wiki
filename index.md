---
#file front matter
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: B-RAD Lab Wiki
layout: home
nav_exclude: true
has_toc: true
---

# Welcome to the B-RAD Lab Wiki!
This website is still a WIP but will be used as a demo to show how B-RAD Lab's wiki page could work and help with future training and continuity efforts for staff/interns!

<h3><a href="/what-is-eeg"><span style="color: black;">What is EEG?</span></a></h3>
{%- assign children_list = site.pages | where: "parent", page.title -%}
{% include toc_nav_recursive.html nav=children_list %}

<h3><a href="/redcap"><span style="color: black;">REDCap Tutorial</span></a></h3>
{%- assign children_list = site.pages | where: "parent", page.title -%}
{% include toc_nav_recursive.html nav=children_list %}

<h3><a href="/e-prime"><span style="color: black;">E-Prime Tutorial</span></a></h3>
{%- assign children_list = site.pages | where: "parent", page.title -%}
{% include toc_nav_recursive.html nav=children_list %}

<h3><a href="/netstation"><span style="color: black;">NetStation Tutorial</span></a></h3>
{%- assign children_list = site.pages | where: "parent", page.title -%}
{% include toc_nav_recursive.html nav=children_list %}