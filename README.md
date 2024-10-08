[The website](https://odysseyprogramme.github.io/index.html)

[A video introduction to using this GitHub repo to post stuff](https://youtu.be/Kdr73zzNnVU)

The website is finally up and running, again. Yay! This page is for any NTU student who[ is interested in contributing to the website. Please ensure good documentation, an established workflow and good reading materials on how to get started etc.

A few files that you will frequent:  
[change_log](https://github.com/odysseyprogramme/odysseyprogramme.github.io/blob/main/help/change_log.md)  
[css](https://github.com/odysseyprogramme/odysseyprogramme.github.io/blob/main/themes/bricks/static/css/lamboz.css)  
[template: base.html](https://github.com/odysseyprogramme/odysseyprogramme.github.io/blob/main/themes/bricks/templates/base.html)

Important files:  
pelicanconf.py

# odyssey-website-dev
The idea: we write our stuff in Markdown (easy), then we use Pelican to generate the html files for us. Pelican uses themes to generate the structure of our website. To modify themes slightly, usually change the css file.

**DO NOT** edit the html output files. Each page share the same layout and everything. Edit layout in themes (which then changes all files), not each page individually!

## Writing:
Create a file in folder <content>. Copy the keywords in <format> file. Then go to Actions to run "Workflow".

How to Markdown:  
https://www.markdownguide.org/basic-syntax/

Reducing picture file size (reduced quality though...)  
Windows: open image file using native image software (Photos) >> three-dot menu >> resize image

## GitHub Workflow:
Background reading to understand the workflow files:  
https://docs.getpelican.com/en/latest/tips.html  
https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/using-jobs-in-a-workflow  
https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/triggering-a-workflow  

___________________________________________________________________________________________

For more help, go to the [help folder](https://github.com/odysseyprogramme/odysseyprogramme.github.io/tree/main/help)


