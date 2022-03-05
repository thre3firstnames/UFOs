#  Display & Search UFO Sightings with JavaScript
## Overview 
Using JavaScript functions combined with HTML & CSS, build and display a webpage that can filter UFO sighting data according to five different criteria. 
## Results 
- To search for sightings on the webpage, enter data in any input field. We will begin with the date:
![datesearch.png](static/Images/datesearch.png)
*Here, you can see the search parameters are also printed to the console.* 
- Continue to add additional filters to the data: 
![datestate.png](static/Images/datestate.png)
- Finally, to clear all filters, use the ‘UFO Sightings’ link in the navigation bar at the top of the page:

![navbar.png](static/Images/navbar.png)
## Summary
One notable drawback of this design is the case sensitivity of the search fields. For example, I can search by sightings in California by typing **ca** but not **CA**. For future iterations of this code, data cleaning on all fields would be prudent before a presentation (all fields, searchable or not, should be corrected to display proper capitalization and cleaned of stray or broken character strings). Design steps should also be taken to address the display issues faced by the filters and their results on smaller screens (neither are mobile-friendly and would benefit from HTML./CSS styling/restructuring).
