# UFO Analysis

## Overview of Project
To allow users of the UFO Sightings website to run a more in-depth analysis of UFO sightings, the filter function on the website has been upgraded to allow users to search for UFO sightings with multiple criteria at the same time.

## Results
- The original website allowed users to search by date of sighting only.  With the updated filter function, users can now search by one or multiple criteria, including the date of sighting, city of the sighting, state of the sighting, country of the sighting, and shape of the UFO.

- Once users enter the information in the filter(s) and hit “Enter” on their keyboards, the table will update to show UFO sightings that match the criteria.  The below example demonstrates only one criterion (searching UFO sightings in Canada) is used.
    ![Country](https://github.com/SzeWingChan/UFOs/blob/main/resources/Country.png)

- Users can enter information in more than one filter, and after they hit the “Enter” key, the table will show the filtered results.  The below examples show combing two or more criteria will help refine the search results.

  Combining the "Date" and "State" filters
  ![Date_State](https://github.com/SzeWingChan/UFOs/blob/main/resources/Date_State.png)

  Combining the "Date", City and Shape filters
  ![Date_City_Shape](https://github.com/SzeWingChan/UFOs/blob/main/resources/Date_City_Shape.png)

## Summary
- One drawback of this new design is users may not know the options available in each filter.  They would fill in the information with no guarantee of successful results.  For example, users will not be able to retrieve any UFO sightings if they were to type “1 Jan 2010” in the Date filter or type “CA” instead of “ca” in the Country filter.  Users have to study the data in the original table first and learn the correct format or what data is available.

  The table will not show any results if the information is not in the correct format
  ![Summary_Date](https://github.com/SzeWingChan/UFOs/blob/main/resources/Summary_Date.png)

- Instead of allowing users to input free text in the filters, a drop-down menu could be utilized for each filter so users can filter out results by selecting the options available to them.

- A brief description of how to use the filter(s) could be added to the website to help users understand better since users may not know that multiple criteria could be used to sort UFO sightings.  
