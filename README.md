![download](https://user-images.githubusercontent.com/112741203/227890324-32d392e9-9b24-4546-80a5-89fa71905ef4.jpg)



https://terryhill89.github.io/Belly-Button-Challenge/
## By Terry Goins
## Background
In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Instructions
Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

 - Use sample_values as the values for the bar chart.

 - Use otu_ids as the labels for the bar chart.

 - Use otu_labels as the hovertext for the chart.
 ![hw01](https://user-images.githubusercontent.com/112741203/226250009-e3d95c5f-547b-4a76-8e93-113b6d7660c6.jpg)
 
3. Create a bubble chart that displays each sample.

 - Use otu_ids for the x values.

 - Use sample_values for the y values.

 - Use sample_values for the marker size.

 - Use otu_ids for the marker colors.

 - Use otu_labels for the text values.
 ![bubble_chart](https://user-images.githubusercontent.com/112741203/226250148-e03b20a3-1008-4220-9849-e1588f165ff2.jpg)
 
4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.
![hw03](https://user-images.githubusercontent.com/112741203/226250253-fc6be6d5-c651-4586-ac1f-43e0dbba8950.jpg)

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:
![hw02](https://user-images.githubusercontent.com/112741203/226250448-64da7d84-b55b-4ea8-bf29-5ec524f38bba.jpg)

7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

## Advanced Challenge Assignment (Optional with no extra points earning)
The following task is advanced and therefore optional.

 - Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

 - You will need to modify the example gauge code to account for values ranging from 0 through 9.

 - Update the chart whenever a new sample is selected.
 ![gauge](https://user-images.githubusercontent.com/112741203/226250636-d368c644-015f-4cea-b90e-7e0e0994036c.jpg)

## Hints
 - Use console.log inside of your JavaScript code to see what your data looks like at each step.

 - Refer to the Plotly.js documentationLinks to an external site. when building the plots.
 
## * Helpful Links
- http://robdunnlab.com/projects/belly-button-biodiversity/
- https://plotly.com/javascript/gauge-charts/
- https://plotly.com/javascript/
- https://d3js.org/
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-custom-404-page-for-your-github-pages-site
- https://docs.spacexdata.com/#46951cda-bdf2-481b-9697-118b1cbccaba
- https://observablehq.com/@d3/galleryhttps://plotly.com/javascript/plotlyjs-function-reference/#plotlyrestyle
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness

## References
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.
 
 
 
