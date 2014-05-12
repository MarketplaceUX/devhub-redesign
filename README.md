# Firefox Marketplace Developers Site Redesign 

## Description
These are the files that make up the current design document for the Firefox Marketplace Developer pages redesign project. This document is currently a "living document" and all the concepts, features, stories, designs, etc are currently subject to change and open to feedback and contribution. If you see something you'd like to discuss, please file an Issue against it to start the conversation with the team.   

To view the document visit http://tsmuse.github.io/FirefoxMarketplaceDevPagesDesign/ All the supporting files used to create the content for this document are available in the master branch of this project. 

## How to Contribute
If you'd like to actively participate in the design process, please document your work in the site hosted here. Making a fork of this repo and then submitting pull requests is the best way to get new pages added. 

### Making New Pages
This site is using Jekyll to ease the burden of updating shared components (like the top navigation area). Because of this you need to know where to edit specific parts of pages. 

* The header for the page, top nav, footer and any other reusable items all live in _includes folder. If you need to make changes to them, you have to edit the files in that folder and the changes will replicate across the site. Keep in mind the code in these files just gets pasted (essentially) into any page it’s included in, so you don’t have to navigate out of the _includes folders in any links to other files.
* All the images for the site are in the img folder, commingled together. This mostly because it was simplier at the start of the project, if you need to make sub-folders in this folder feel free.
* Research findings should live in the research folder (if they’re not a link to another website.) 
* All the actual pages for the site live in the main directory. I did this to avoid any potentially weird linking with relative paths. Because they all live in the same folder I’ve tried to start a naming contention for the files to make them a little easier to find. Here it is:
  * User stories addressed pages: userstoriesStoryThemeName.html (e.g. userstoriesManageVersions.html)
  * Design stories: designstoriesStoryName.html (e.g. designstoriesSimplifyPaymentOptions.html)
  * User flows: userflowTaskName.html (e.g. userflowSubmissionFlow.html)
  * everything else: named for the page title (e.g. designPrinciples.html)

This is all still a work in progress so if you find a bug in it or come up with a better way to do any of this just let us all know and we can evolve the process. The goal of this hosting method is to allow the team to focus on creating content instead of presentation pages. 
