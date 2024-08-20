The website: https://odysseyprogramme.github.io/odyssey-website-dev/

# odyssey-website-dev
testing the odyssey website

The idea: we write our stuff in markdown (easy), then we use Pelican to generate the html files for us (see "output").

Pelican uses themes to generate the structure of our website. To modify themes slightly, usually change the css file.

DO not edit the html output files. Each page share the same layout and everything. Edit layout in themes (which then changes all files), not each page individually!

### Workflow:
Background reading:

The markdown files are not rendering... WHY??? I checked the workflow output log: no errors, no articles rendered... GItHub invoked the command "pelican". We actually need "pelican[markdown]"!

since we're using markdown, we must use the pelican[markdown], hence we had to copy the pelican official workflow file into our directory to modify....


