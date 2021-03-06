# Web-Design-Challenge
Create a website using HTML and CSS. The challenge was to use visualizations that we used in a previous challenge. The example use the visualizations from the API project that used weather data. However, we could use other visualizations if we wanted to and that is what I decided to do. I used my visualizaitons that I created from my group project on the U.S. National Parks. I used the portion of the group work that I did, which was the 2019 v. 2020 month-to-month comparison on visits to a U.S. National Park region. 

# Website Requirements

The website must have 7 pages total:
1. A landing page
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.

2. Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

3. A "Comparison" page that:
  * Contains all of the visualizations on the same page, so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
  * The grid must be two visualizaions across on medium and larger screens, and then 1 across on extra-small and small screens.

4. A "Data" page that:
  * Displays a responsive tabel containing the data used in the visualizations.
  * The table must be a bootstrap table component.
  * The data must come from exporting teh .csv file as HTML, or converting it to HTML (I used the df.to_html conversion in Pandas then copied the coded over in VS Code). 

The website must have a navigation menu on every page and include:
* The name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons" that links to the comparison page and "Data" that links to the data page.
* Is responsive (using media queries).

The deployed app's website (hosted on GitHub): https://gggojo.github.io/Web-Design-Challenge/index.html


