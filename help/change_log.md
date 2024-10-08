## Background
Webpage design
Go to template>>index.html, seach "logo" to get the bearded guy.  
The people behind the logo are from "lego_background". Used in /theme/css/lamboz.css

Try offline in your computer  
The images won't come up. You must change file path  
https://www.w3schools.com/html/html_filepaths.asp

a href for local file: relative path (try playing with the thing that imports the css file; if you lose css effects, good. What's the right file path?) https://stackoverflow.com/questions/12021781/the-right-way-of-setting-a-href-when-its-a-local-file

css file: the lego image path has to be changed. use this dot notation.  
https://stackoverflow.com/questions/20047364/how-to-give-the-background-image-path-in-css

## Changes made

#### created Github Workflow
The markdown files are not rendering... WHY??? I checked the workflow output log: no errors, no articles rendered... Apparently GitHub called the command "pelican". We actually need "pelican[markdown]"!

since we're using markdown, we must use the pelican[markdown], hence we had to copy the pelican official Github Pages workflow file into our directory to modify....

#### changing position of odyssey logo to not block any heads
Using a container  
https://stackoverflow.com/questions/5507415/positioning-a-banner-in-css

Positioning a container  
https://stackoverflow.com/questions/14402038/how-to-position-a-container-in-the-middle-of-the-screen

#### grey link is too hard to read
Changing the link colour    
https://www.w3schools.com/css/css_link.asp

#### making CSS file more readable
writing comments  
https://www.w3schools.com/css/css_comments.asp


#### some of our social links are dead: changing them
pelicanconf.py>>LINKS

24/8  
#### added template file in contents
#### discovered how adding images work (and the many ways to fail)
https://github.com/odysseyprogramme/odysseyprogramme.github.io/blob/main/content/template.md


#### here is a way to disable markdown for a small part of the page
https://stackoverflow.com/questions/701042/disable-markdown-for-a-block
