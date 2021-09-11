# UFOs

## Overview of Project
In celebration of World UFO Day, the purpose of this timely analysis is to provide those who are curious about the sightings of UFOs with a resource of information that will hopefully raise awareness of UFOs and to combat the naysayers. This information is provided in the form of a dynamic webpage formatted and complete with a filtered search feature.

## Results
After applying and expanding on some previous exposure to HTML and CSS styling, as well as, Bootsrap, this project required a bit of JavaScript
research and learning. With JavaScript added to the arsenal of tools, the end result is Dynamic Website with the following features:

Navigation Bar 
- "UFO Sightings"
    - when clicked, it clears the filters and refreshes the page (or...takes the user back to the home page)

Jumbotron Header
- "The Truth is Out There"
    - in large display with an image of space as its background

Header/Subheader and Paragraph
- "UFO Sightings: Fact or Fancy? Ufologists Weigh In"
- Paragraph gives some back as to why this data is being presented

Table
- Includes 7 different columns of information on sightings in the month of January 2010 as reported by witnesses
    - Date
    - City
    - State
    - Country
    - Shape (visual shape of the UFO)
    - Duration (length of time the sighting lasted)
        - the data in this column is not uniformly formatted 
            (would have required REGEX and time was limited)
    - Comments (description of the sighting)
        - the data in this column is not uniformly formatted
            (these are the witnesses own statements)

Filter Search Form (NOT CASE SENSITIVE)
- Allows the user to filter search by:
    - Date (M/*D/YYYY format)
    - City
    - State
    - Country (2-character abbreviation format)
    - Shape

There are two ways to clear the form:
    - 1. Delete all the input in the search fields, or
    - 2. Click the "UFO Sightings" navigation bar link at the top left corner of the page.

## Summary
As mentioned above, due to the amount of time it would have taken to become familiar with the appropriate REGEX syntax, the data in the "Duration" and "Comments" columns are not uniformly formatted or grammatically correct(which may or may not add to its genuine appeal). The time was, however, invested into changing the data to "uppercase" from "lowercase." Also, for ease of filtering and to ensure the accurate data was returned, the time was taken to add in some JavaScript code which renders the input fields as "case insensitive."

Given the appropriate amount of time, this webpage could benefit from further development at least two ways: 
- By adding a calculated field of total sightings once the filtered search was done would be a convenience for the user.
- Having a larger dataset to present and filter from would also prove more convincing to skeptics.