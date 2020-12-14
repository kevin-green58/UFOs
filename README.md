# UFOs

## Overview of Project
The purpose of this analysis is to create a web application that can be used to easily filter through supposed UFO sightings in January 2010. This was accomplished using a Javascript d3 framework. 

## Results
The webpage is fairly straight forward to navigate. Using the ` d3.selectAll("input").on("change", updateFilters);` functionality, one simply needs to type something into one of the five filters on the left side of the page. After pressing `Enter ` , the results will filter to only show results that have a match for that category. Results can be narrowed down further using multiple filters.


## Summary
One drawback of the design of this web application is that it cannot handle typos. For further development one may want to consider adding a "Did you mean.." sugestion before submtting search results. For example if someone types "cs" instead of "ca" the web app would recoginize this and sugest the latter so you wouldn't see zero results. One may also want to consider expanding the size of the data.js file, even potentially having it be able to update live. Folks interested in UFO sitings will want to read about citings beyond those that occured in January 2010.  



