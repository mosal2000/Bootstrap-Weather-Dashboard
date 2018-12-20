# Web Visualization Dashboard (Latitude)

## Background

The purpose of this project is to create a visualization dashboard website presenting graphs and data that were previously created using Jupyter Notebook.

This page is published in the following page:
https://mosal2000.github.io/Bootstrap

![Images/landingResize.png](Images/landingResize.png)

## Latitude - Latitude Analysis Dashboard with Attitude

The data to be represent is the [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

For reference, see the ["Screenshots" section](#screenshots) below.

The website must consist of 7 pages total, including:

- A [landing page](#landing-page) containing:
  - An explanation of the project.
  - Links to each visualizations page.
- Four [visualization pages](#visualization-pages), each with:
  - A descriptive title and heading tag.
  - The plot/visualization itself for the selected comparison.
  - A paragraph describing the plot and its significance.
- A ["Comparisons" page](#comparisons-page) that:
  - Contains all of the visualizations on the same page so we can easily visually compare them.
  - Uses a bootstrap grid for the visualizations.
    - The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
- A ["Data" page](#data-page) that:
  - Displays a responsive table containing the data used in the visualizations.
    - The table must be a bootstrap table component.
    - The data must come from exporting the `.csv` file as HTML, or converting it to HTML. You may use a csv-to-html table conversion tool, e.g. [ConvertCSV](http://www.convertcsv.com/csv-to-html.htm).

The website must, at the top of every page, have a navigation menu that:

- Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
- Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
- Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
- Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

### Screenshots

#### Landing page

Large screen:
![Landing page large screen](Images/landing-lg.png)

Small screen:
![Landing page small screen](Images/landing-sm.png)
￼

#### Comparisons page

Large screen:
![comparison page large screen](Images/comparison-lg.png)

Small screen:
![comparison page small screen](Images/comparison-sm.png)

#### Data page

Large screen:
![data page large screen](Images/data-lg.png)

Small screen:
![data page small screen](Images/data-sm.png)

#### Visualization pages

You'll build four of these, one for each visualization. Here's an example of one:

Large screen:
![visualize page large screen](Images/visualize-lg.png)

Small screen:
![visualize page small screen](Images/visualize-sm.png)

#### Navigation menu

Large screen:
![nav menu large screen](Images/nav-lg.png)

Small screen:
![nav menu small screen](Images/nav-sm.png)
