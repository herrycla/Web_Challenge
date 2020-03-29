# latitude_page
Quick webpage with latitude and weather correlations

https://blueskiesatx.github.io/latitude_page/index.html

## Web Visualization Dashboard (Latitude)
## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.

![Images/landingResize.png](Images/landingResize.png)

## Latitude - Latitude Analysis Dashboard with Attitude
Tghis is a created visualization dashboard website using visualizations plotting weather data.

In building this dashboard, I created individual pages for each plot and a means to navigate between them. These pages contain the visualizations and their corresponding explanations. There is a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data comes from exporting the `.csv` file as HTML, or converting it to HTML. 
    
    Alternatively, we can use a csv-to-html table conversion tool, e.g. [ConvertCSV](http://www.convertcsv.com/csv-to-html.htm).

## Features

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.


## To do:
Make responsive (using media queries) such as a background color change.

### Tools

bootstrap theme to customize, navbar, visualization navigation, publicly accessible URL

### Screenshots

This section contains screenshots of each page built, at varying screen widths. 

#### Navigation menu





