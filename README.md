# Module 11 – UFOs sightings!
# Unit Challenge
## Overview of the analysis
Dana, our customer, has been given the opportunity to write an article on his own. She has selected to write about UFOs sightings in her hometown. She has a JS file with data describing UFO sightings from different states and cities. 

To get started, she is planning to build a website to expose the data to a wider audience. She will be using JS to develop an interactive site, showing the available data so far. The data contains some details about the sightings:
1. Date
2. City
3. State
4. Country
5. Shape
6. Duration
7. Comments

The website that will be built will allow the users to filter the data table using date, city, state, country, and/or shape. It will be also possible to combine any of these filters. 

## Results - How to perform a search?
When loading the page for the first time, the full data table will be loaded and displayed. If the user is curious enough, he/she will be able to scroll through the whole data set. Fortunately, we can also filer the data to find especific records.

**Initial page - full data table**

![Full data table - initial state](/resources/full_data_table.png)

### Performing a search using the available filters
At the left of our home page, you will be able to see a form with five fields:
1. Date - Enter the date of the sighting you want to find
2. City - Enter the City where the sighting was reported
3. State - Enter the State where the sighting was reported
4. Country - Enter the Country where the sighting was reported
5. Shape - Enter the shape of the reported UFO

**Filtering data - using the form**

![Filtered data table](/resources/filtered_data_table.png)

You can enter one or all the five fields. Please, **consider** you have to type the exact word or phrase into the field. If no exact matches are found, your query will return no results. 

To apply the filters to the data table, you can press the "Enter" key after typing into a field. An alternative method to apply the filter is to click on some other field in the form. The table will refresh itself everytime you change the filtering criteria.

### Resetting the filters - showing the whole data set

To reset the data table, you can either set to blank all fields in the form, or you can refresh the homepage to its initial stage. 

**Resetting the form**

![Empty form](/resources/form.png)

## Summary
We have maaged to create a dynamic webpage for Dana. This first version is showing the data Dana has available with a single page. We have also enabled the possibility of filtering the data according to five different criteria.

Although we are happy with the result, we know there is room for improvement. We will now review what are some of the drawbacks of this page, and our recommendations for further developments.

### Drawbacks of this webpage
1. **An exact match is needed when filtering the data**. What will happen if the user does not remember the right spelling of any particular field? There is also the possibility of having "dirty" data which will not match with the text entered by the user. Beyond allowing searching data using approximate terms, we also need to keep using our good practices of cleaning data before publishing it. 
2. **All data is loaded when opening the page for the first time**. Right now this is not a problem. Currently we only have 111 records, so the page loads fast and scrolling to the bottom of the page is no issue. Imagine if we have ten thousand records? The page loading time may not be good, and the page will be too long to scroll and explore the full list.
3. **The set of data available is fixed**. If we need to publish new records, we have to update the JS file, an upload to the server where our page will be hosted

### Recommendations for further development
To expand the utilization of our page, and make it more interesting to the audience, I can propose the following enhancements:
1. Load a small set of records in the DB (e.g. The first ten records). Then, refresh the table as the user enters filtering criteria. This will improve the loading time and make it more user friendly. 
2. We can create an "auto complete" feature for fields where the options are plante (e.g. State and City). For the fields where the options are fewer (e.g. Country), we can always create combo boxes and allow the users to select the option they want. For date, we can implement a "pick date" functionality to minimize the errors when selecting a date. 
3. We can also create "dependant" fields. For instance, if we select "USA" as Country, then we can limit our options in the "State" field to state in the USA only.

This is a very good start, but in order to build a robust we can implement a series of improvements and enhancements. Defining a roadmap and an implementation strategy for our website should be our next steps. This web page is just the start of something great.