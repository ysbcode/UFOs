# UFOs

## Project Overview
We used JavaScript to populate an HTML table with UFO sighting data, and created filter criterias to search through the table to find rows that match user input.

## Results
We first created a HTML webpage which housed the full dataset. The page contains a header and two sections. One section houses the search criterias and the other section houses the table. In the search criteria section, the user can input their required filter criterias the table will update automatically based on that input. In order to reset the table, the user can click the "UFO Sightings" link on the top left corner of the page. A screenshot of what the webpage looks like is provided below. 

![](https://github.com/ysbcode/UFOs/blob/main/images/UFO%20Facts.PNG?raw=true)

From this image below we have 5 different filters to choose from; the date, city, state, country & shape. You can choose any of these filters enter the search bar, then the HTML page will show all of the sightings for that specific search. Multiple filters can be entered at the same time to further inspect the data in the specific search bar that is entered.

![](https://github.com/ysbcode/UFOs/blob/main/images/UFO%20Table.PNG?raw=true)

## Summary
The table is useful to filter throgh the UFO data based on the user's perference. One drawback of the table is that the data gets filtered automatically right after the user inputs the data. It would have been better if the "Filter Data" button was retained and used as the event listener. Then the data would only get filtered if the button was clicked by the user. 

We can make further improvements to the webpage by adding a "Reset Data" button. This is more intuitive than the user having to click the link on the top of the page to refersh the filters.
