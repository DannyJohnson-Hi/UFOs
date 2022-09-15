# UFOs Sightings - a Javascript Assignment

Utilizing `Javascript` to build and create dynamic webpages.

## Project Overview

The purpose of this project was to learn how to extract data, that is stored as a `JavaScript` array or list, and to build a table to organize the data that visually adjusts as "events" change. We use `Javascript` functions to loop through the data to build the table and create a customized dashboard, in order to react when an element has changed. The customizations have filters w/ event listeners that will record the information when an element has changed and to develop an interactive webpage. Filters can be applied in different ways. For this exercise, we reviewed how to reflect default data in the table, listen for a button input to trigger the table to update based on the user's input with a select criteria. Finally, we use `HTML`, `Bootstrap` and `CSS` to read the `Javascript` code and create a webpage that is easy to view, includes filters, images, and a summary of the topic.

## Topic

We have been tasked to help **Dana** with building a webpage, in which others can access information of reported UFO sightings and review the data themselves. This webpage will include:

* A description/summary of the topic 
* A table to display all of the information from the data source
* Search filters that will allow for visitors to update the table based on the search criteria they enter.    

![UFO](

## Results

The webpage **[UFO Sightings - The Truth is Out There] has been created. Upon entering, visitors embarking on their "first encounter" will see:

![webpage](https://github.com/DannyJohnson-Hi/UFOs/blob/main/static/images/UFO.png)

- You will notice that a **"Filter Search"** section has been added. 

![FilterSearch](https://github.com/DannyJohnson-Hi/UFOs/blob/main/static/images/FIlterSearch.png)


- You can filter by one or all of the search criteria shown. For example, if you search by **"City"**, you will see that the table updated to show the reported sightings that was recorded for that specific city.


![CitySearch](https://github.com/DannyJohnson-Hi/UFOs/blob/main/static/images/citysearch.png)

- If you add a shape, the table will update filtering further to only display the information containing that shape.

![ShapeSearch](https://github.com/DannyJohnson-Hi/UFOs/blob/main/static/images/deletesearch.png)


- Or if you delete your previous entries and enter **"State"** and **"Shape"**, the table will update using your new criteria.

![DeleteSearch](https://github.com/DannyJohnson-Hi/UFOs/blob/main/static/images/deleteSearch1.png)

## Summary

**Drawbacks:**

Unfortunately, this page has several drawbacks. They include the following:

* The search field is "case-sensitive". The table will not update if you do not enter exactly how the data is stored. It also does not allow for partial entries. 
  - This is an issue because it does not instruct the user on how to input this information. 

* There is no button to interact with or some sort of action that tells the user that the table will update after you hit "enter".

* The data provided is limited and outdated, since it's not linked to a "live" source.

**Recommendations for further development:**

With the following enhancements, this webpage will be significantly enhanced for a better user experience:

* Add additional customizations, such as interactive buttons, dropdown lists, and/or auto-fill that can help "instruct" the user and make the page more interactive.

* Add functionality to pull the data from a live source that includes current and archived data not limited to only the United States, but globally.

* Add a "Latest News" section that will highlight an article showing the most recent or famous reported sightings.
