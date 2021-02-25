# UFOs
Finished app file:  
[UFOs](/static/js/app.js)        
## Overview of Project
Provide ability to analyze UFO sightings data by giving users the capability to filter sightings data by various criteria:  
* Date  
* City  
* State   
* Country  
* Shape  
  
## Results
To begin, users can visit the html document in their browser.  From there, anyone can enter search criteria in the filter search area:  
![Filter Screenshot](/Resources/filter_screenshot.png "Filter Screenshot")  
The filter criteria will narrow the dataset, which is visible on the right-hand side.  For example, if someone searches "1/1/2010" and "triangle" objects, these are the results:  
![Results Screenshot](/Resources/results_screenshot.png "Results Screenshot")  
## Summary and Limitations
This is a quick and useful way to sift through UFO sightings listed in the available JSON object, but there are some limitations.  Unfortunately, the dataset is not currently dynamic so if a new UFO sighting happens today or tomorrow, it will not appear on our page.  Secondly, it's important to note that there is no function in the app to clear filters.  Therefore, if you filter on "1/10/2010" and try to clear that filter in the input box by erasing it and hitting enter on your keyboard, it will not return you to the full dataset; you will need to reload the page.  For future improvements, it would provide a better user-experience if we were to use a live dataset and more seamless filter capability.
