# UFOs

## Overview
UFOs have been reported across the world throughout history drawing attention towards the mystery of otherworldly existence. Are we truly alone? Have we been visited by other beings? Is that bright triangular shape of light truly a weather balloon? The existence of UFOs has always drawn our interest and it is for this reason that we have decided to create an HTML page displaying UFO sightings from data we are pulling from a JavaScript file. We are creating filters within the HTML in order to search by different criteria.
## Results
After opening the HTML file, you will be directed to a page titled ‘The Truth is Out There’.  In the left-hand side of the page, you will find different input boxes that can be used to filter through the sightings. The different criteria you may search with includes Country, City, State, and Shape.  After typing in your search criteria into the input boxes just hit enter and the page will sort through the information to display all matching sightings.  
![alt text]( https://github.com/quorinne/UFOs/blob/main/static/images/htmlfilter.png?raw=true)

## Summary

While very simple to use this HTML page is not without its own drawbacks. It is terribly, horribly case sensitive. Everything and I do mean everything must be typed in lower cases. So, it would be bonita instead of Bonita for the city filter, ca instead of CA for state filter and us instead of US or USA for country filter.  The filters also are incapable of finding results with very similar search terms they must be exact. If you search 01/01/2010 instead of 1/1/2010 nothing will be shown in the search results. This also applies to typing usa or USA instead of us. 
### Searching by CA
![alt text](https://github.com/quorinne/UFOs/blob/main/static/images/failedfilter.png?raw=true)

### Searching by ca
![alt text](https://github.com/quorinne/UFOs/blob/main/static/images/successfilter.png?raw=true)

This made searching very annoying initially until I got the hang of it. If I had more time to dedicate to this project, I would like to use regular expressions to fix this issue and improve the filters. Another potential fix would be to provide all available search options from the beginning and allow visitors to select or deselect filter variables to change the displayed information. Sort of like the way Excel does it in the image provided below. 
![alt text](https://github.com/quorinne/UFOs/blob/main/static/images/excelexample.png?raw=true)
