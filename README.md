# UFOs

JavaScript, HTML, CSS, Bootstrap

Background

We needed a webpage and dynamic table that are working as intended, but DANA aims to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

Overview of Project

We need to build a dynamic webpage that displays UFOs sightings information for upcoming annual gathering of UFO enthusiasts in McMinnville, Oregon.
![UFO Sightings](https://user-images.githubusercontent.com/91812090/153767505-c87e9108-cde3-42de-a615-3f35738623c8.png)


Purpose

The purpose of this project is to display data by adding filters to the table which let users to refine their search on more than one level.

Requirements

The webpage contains the following:

Interactive filters for searching criteria on date, city, country, and shape.
Brief article and its summary.
An attention-grabbing header with a refresh page link.
Visually appealing design of overall presentation of the data.

Background

For this project we are using JavaScript as the primary coding language. JavaScript (JS) is a scripting language, primarily used on the Web. It is used to enhance HTML pages and is commonly found embedded in HTML code. JavaScript is an interpreted language. Thus, it doesn't need to be compiled. JavaScript renders web pages in an interactive and dynamic fashion.

Resources

Data Source: JavaScript list data.js
HTML to build the webpage index.html.
CSS and Bootstrap to build and style the page style.css
Software: VS Code and Chrome Developer Tools.
Chrome Developer Tools to test the code.
Languages: JavaScript, HTML, CSS and Bootstrap 3
The table is built by inserting JavaScript into HTML page. app.js.
HTML to build the webpage index.html.
CSS and Bootstrap to build and style the page style.css
Dependencies: D3(Data Driven Document)- We can Build a real-world, custom, interactive and beautiful data visualization from scratch using D3.

Results

The raw data from JavaScript array is going displayed in a dynamic table where end-users can filter the data on multiple criteria such as date, city, state, country and shape of UFOs sightings. Here we filter input box, suggesting end-user that, how search criteria should be entered with using text value in it. For example, date should be entered in format as in 1/10/2010 – with forward slashes and without extra 0 before day and month. City, state, and country should be entered in lower case.

![FilterSearch_Criteria](https://user-images.githubusercontent.com/91812090/153768250-d4945fb0-6f93-4631-a769-590fc9cc9397.png)


Dynamic multi-filter.

When user types of criteria in multi-filter and then press enter then table displays only rows that matches the user input. From the picture below we can see only data that has been filtered based on the user input – that is -- State: ca, Shape: triangle and Date: 1/1/2010.
![FilteredTable](https://user-images.githubusercontent.com/91812090/153768244-a50918b8-a40e-4e23-a578-eba0c44a8c14.png)


 

New table, displays only the results that matches the user’s input.

To resetting the filter, there are two options. User can either clear input manually by deleting input cell by cell or click the refresh link UFO Sightings that can be found at the top left corner of the page. After the filter is cleared, the user can use filter again.



Reset filters and refresh page with UFO_sightings at the top left corner of the webpage.

Summary

This webpage does give a great overview of UFO sightings in the US, but it does have a few shortcomings.

Instead of "UFO Sightings" reset link, we can add some functions which will reset page automatically. Also provide some "BOTTOM" and "TOP" functions to scroll page up and down to make it user friendly.

It does not have the functionality to add "live" data.

The data that is a part of the data file will stay the same unless and until someone change it.

Recommendations for further analysis

Input data.

By Adding a code that will convert all letters to lower case from user input. For example, no matter which format user used to type “CA” or “Ca” instead of “ca”, the code will still be able to process and find the results.
Also we can add some functinality that will change the user input to exact keys which will match the data. For example, if user type "st.louis" then it will automatically changed it to St.Louis or "mo" to "MO".
Adding drop down-menu from the filter.

In addition, to improve upon the user experience we suggest make the filter functionality be changed to drop down menus that populate with the options to limit the data displayed on the dashboard. This would help it be more intuitive and would not require users to be already familiar with the data.


