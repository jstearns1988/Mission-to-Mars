# Mission-to-Mars

## Overview
While assisting Robin with her Mars web app, she decided she would like to include all four Mars hemisphere images to add more polish. I used BeautifulSoup and Splinter to scrape full-resolution images of Mars's hemispheres and titles, stored the scraped data on a Mongo database, used a web application to display the data, and altered the design of the web app to accommodate these images.

#### The following steps were taken to complete this analysis
  - Scrape full-resolution Mars Hemisphere images and titles
  - Updated the web app with Mars Hemisphere images and titles
  - Added Bootstrap 3 components
  
## Results

### Full Resolution Mars Hemisphere Images and titles

Code was written to retrieve the full-resolution image and title for each hemisphere. The full-resolution images of the hemispheres were added to the dictionay. A list was written to contain the dictionary of the full-resolution image URL string and title for each hemisphere image.

![Hemisphere Code](https://github.com/jstearns1988/Mission-to-Mars/blob/main/Resources/Hemispheres%20Code.png?raw=true)

### Updated web app with Mars Hemisphere images and titles

I ammended the scraping.by file to contain code that retrieves the full-resolution image URL and title for each hemisphere image. The Mongo database was updated to contain the full-resolution image URL and title for each hemisphere image. The index.html file was given code that will display the full-resolution image URL and title for each hemisphere image. I wrote the code to successfully scrape the data, and the web app now contains four hemisphere images as well as latest news, a featured Mars image, mars facts, and a convenient scraping button.

![Scraping](https://github.com/jstearns1988/Mission-to-Mars/blob/main/Resources/scraping%20screenshot.png?raw=true)

![Scraping successful](https://github.com/jstearns1988/Mission-to-Mars/blob/main/Resources/scraping%20successful.png?raw=true)

### Added Bootstrap 3 components

To make the site more attractive to look at and fun to use, I applied several Bootsrap components to index.html. 

I changed the page color to orange, a color that evokes the spirit of Mars. 

![Orange](https://github.com/jstearns1988/Mission-to-Mars/blob/main/Resources/Top%20Page.png?raw=true)

I resized the hemisphere images so they fit on the page cleanly in one row. This will also be more attractive to screenshotters and help our content be shared by fellow fans of our neighbor planet. 

![Hemispheres](https://github.com/jstearns1988/Mission-to-Mars/blob/main/Resources/Hemispheres.png?raw=true)

My favorite touch was adding a hover message to the scraping button!

![Blast off](https://github.com/jstearns1988/Mission-to-Mars/blob/main/Resources/Header%20and%20button.png?raw=true)

I made this friendly to mobile users so anyone can access our content no matter what device they are using.

![Mobile](https://github.com/jstearns1988/Mission-to-Mars/blob/main/Resources/mobile%20responsive.png?raw=true)

