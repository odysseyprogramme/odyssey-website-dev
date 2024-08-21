The website: https://odysseyprogramme.github.io/odyssey-website-dev/

After much pain, the website is finally up and running, again. This page is for whoever is going to take over the technical challenge of running the website. Please ensure good documentation, an established workflow and good reading materials on how to get started etc.

A few files that you will frequent:  
[css](https://github.com/odysseyprogramme/odysseyprogramme.github.io/blob/main/themes/bricks/static/css/lamboz.css)  
[template: base.html](https://github.com/odysseyprogramme/odysseyprogramme.github.io/blob/main/themes/bricks/templates/base.html)

Important files:  
pelicanconf.py

# odyssey-website-dev
The idea: we write our stuff in Markdown (easy), then we use Pelican to generate the html files for us. Pelican uses themes to generate the structure of our website. To modify themes slightly, usually change the css file.

**DO NOT** edit the html output files. Each page share the same layout and everything. Edit layout in themes (which then changes all files), not each page individually!

## Writing:
Create a file in "content". Copy the keywords in "format" file. Then go to Actions to run "Workflow".

How to Markdown:  
https://www.markdownguide.org/basic-syntax/

## GitHub Workflow:
Background reading to understand the workflow files:  
https://docs.getpelican.com/en/latest/tips.html  
https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/using-jobs-in-a-workflow  
https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/triggering-a-workflow  

#### Challenge 1:  
The markdown files are not rendering... WHY??? I checked the workflow output log: no errors, no articles rendered... Apparently GitHub called the command "pelican". We actually need "pelican[markdown]"!

since we're using markdown, we must use the pelican[markdown], hence we had to copy the pelican official Github Pages workflow file into our directory to modify....




___________________________________________________________________________________________

For more help, go to the [help folder](https://github.com/odysseyprogramme/odysseyprogramme.github.io/tree/main/help)


