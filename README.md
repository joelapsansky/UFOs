# UFOs
Finished app file:  
[UFOs](/static/js/app.py)        
## Overview of Project
Provide an analysis of UFO sightings by giving users the capability to filter on a sightings dataset by several different criteria:  
* Date  
* City  
* State  
* Country  
* Shape  
  
## Results
To begin, users can visit the html document in there browser.  From there, anyone can enter search criteria in the filter search area:  
![Filter Screenshot](/Resources/filter_screenshot.png "Filter Screenshot")  
The filter criteria will narrow the dataset, which is visible on the right-hand side.  For example, if I search 1/1/2010 and triangle objects, these are the results:  
![Results Screenshot](/Resources/results_screenshot.png "Results Screenshot")  
## Summary and Limitations
This is a quick and useful way to sift through UFO sightings listed in the available JSON object, but there are some limitations.  Unfortunately, this is not currently dynamic so if a new UFO sighting happens today or tomorrow, it will not appear on our page.  Secondly, it's important to note that there is no function in the app to clear filters.  Therefore, if you filter on '1/10/2010' and try to clear that filter in the input box, it will not return you to the full dataset; you will need to reload the page.  For future inmprovements, it would provide a better user-experience if we were to use a live dataset and more seamless filter capability. 