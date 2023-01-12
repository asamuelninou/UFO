# UFO Sightings
Dana’s webpage uses a dynamic table by allowing users to filter multiple criteria to provide in-depth analysis of UFO sightings. Users will be able to filter through a table by city, state, country, and shape.
## Overview of analysis
Dana's goal is to create an interactive webpage that allows readers to parse the data around UFO sightings. I built a webpage that will allow users to view the data (HTML) and a dynamic table that will present it (JavaScript).

### How to perform a search, with images
#### JavaScript
Coding in JavaScript requires proficiency with JavaScript objects. And, in JavaScript, many different things can be considered "objects." We've already encountered one! Let's look at a snippet of code from ourdata.js array.
![data js example](https://user-images.githubusercontent.com/92180070/211959293-a3a8134d-5b9e-4a86-8871-a74d98a3bdd9.png)


The array containing UFO sightings is huge. So we used a for-loop and if-statement to filter data depending on user's input. 
![Filtered Search JS](https://user-images.githubusercontent.com/92180070/211959131-5e1862d4-05b8-475c-b815-05bd69e74372.png)

#### HTML
We created Dana's HTML page by using the layout from her storyboard. We will link D3.js, app.js, and data.js to the HTML. We tried the JavaScriptcode them together by adding <script /> tags and then linking to the file's location at the bottom of the page.
![integrating script into html](https://user-images.githubusercontent.com/92180070/211959026-e130cd98-2e55-48b2-b990-f540fd99c02b.png)

### Summary
#### Success
We created a table to organize UFO data that was stored as a JavaScript array. This table has the ability to filter data based on specific criteria.
![ufo website](https://user-images.githubusercontent.com/92180070/211958986-2d8e063d-f027-4122-8f9d-cc9f97f49b03.png)

#### Drawbacks
The website could have been more interactive to give users a better experience. 

## Additional Recommendations
### Filtered Autopopulated List
It would be helpful to have a list auto-populated so users could see what options are available without having to skim through the whole table, when filtering data.
### Map of the World 
An upgrade to Dana's website would have been to create an interactive dynamic map that users could click to autopopulate data into the table.
