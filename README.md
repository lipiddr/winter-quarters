# Winter Quarters Website

This repository contains the Winter Quarters Website, which was created as a Collaboration between Brigham Young University and The Winter Quarters Project, an independent research venture which has no official affiliation with Brigham Young University or The Church of Jesus Christ of Latter-day Saints. 

# Development Environment

To edit the site, we strongly recommend using BrowserSync in conjunction with a free text editor such as [Visual Studio code](https://code.visualstudio.com/).

To run the site locally with browser-sync you'll need to have [Node.JS](https://nodejs.org/en/) installed. [Click Here to download the latest version](https://nodejs.org/en/).

## Instructions in Visual Studio Code

Once you've installed NodeJS, you can use the VSCode Terminal window to server the site. Open the site's root directory in VS code, then go to "View -> Terminal" to open the command line terminal window. Enter the following commands:

`npm install -g browser-sync`

`browser-sync start --server './' --files './'`

Once browser-sync is running you can view the site locally at http://localhost:3000/. Additionally, if you save any changes to the site browser-sync will refresh your browser window to reflect the latest changes.
