# Analysis of Creating a UFO Sightings Finder Webpage

# Analysis Overview

Using VS Code, three separate files were created to: 
#### 1 create the layout of the webpage (html.index); 
#### 2 create the code to populate the webage as well as filter the data (app.js); and 
#### 3 format the webpage (style.css)

DevTools in Chrome was used to test and debug the code.  The data used to populate the webpage was provided in a .js format.  


# Purpose 
The purpose of creating the webpage was to make UFO sighting information readily available.  Due to the volume of information, viewing the data was overwhelming to the user.  To reduce observation strain, searchable fields were added to the webpage.  Users can search sightings, by any combination, of: date; city, state, country and shape of UFO.  The searchable aspect lends viewing flexibility to the webpage. 

## Results
Please see images below to view the final webpage.  The first image is the upper half of the webpage.  

![](static/images/UFO1.png)

To view the data, user can scroll down the page to see all the sightings.  If user wants to view specific records, they can enter one or more criteria(s) in the input boxes.  The image below displays the five(5) input boxes user can select to filter their view.  The input boxes have sample data showing that indicate how each entry should be typed.  Date is in "M/D/YYYY" format; city is entered in lower case; state is a 2-letter abbreviation in lower case; country is a 2-letter abreviation in lower case; and shape is entered in lower case.  Once the criteria is entered, user can either press enter or the tab key.

![](static/images/UFO2.png)


# Summary:
Webpage contains a lot of info which can be overwhelming.  The searchable filters allows user to view small chunks of the data.

The summary addresses one drawback of this webpage (2 pt)
data in the table is all lower case and if user entered upper case, filter would fail.

The summary addresses two additional recommendations for further development (4 pt)
convert all entries to lower case to reduce errors

add search feature to comment field.
