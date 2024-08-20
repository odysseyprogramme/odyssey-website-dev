---
Title: Hello World!!! Website is Alive :)
date: Tuesday Aug 20, 2024
author: Odyssey
category: tech
---

After much pain, the website is finally up and running, again. This page is for whoever is going to take over the technical duties of running the website. 

Frequent files:  
[css](https://github.com/odysseyprogramme/odyssey-website-dev/blob/d2ca0267793a68e9971163c110ac1ff3eacda132/themes/bricks/static/css/lamboz.css)  
[template: base.html](https://github.com/odysseyprogramme/odyssey-website-dev/blob/bfb00a9417b4f6bcccc132b14f079c82fe910b13/themes/bricks/templates/base.html)

# odyssey-website-dev
testing the odyssey website

The idea: we write our stuff in markdown (easy), then we use Pelican to generate the html files for us (see "output").

Pelican uses themes to generate the structure of our website. To modify themes slightly, usually change the css file.

DO not edit the html output files. Each page share the same layout and everything. Edit layout in themes (which then changes all files), not each page individually!

### Workflow:
Background reading:

The markdown files are not rendering... WHY??? I checked the workflow output log: no errors, no articles rendered... GItHub invoked the command "pelican". We actually need "pelican[markdown]"!

since we're using markdown, we must use the pelican[markdown], hence we had to copy the pelican official workflow file into our directory to modify....



