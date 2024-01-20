**Project Overview**

In this project, we will develop an interactive dashboard to explore the Belly Button Biodiversity dataset. This dataset reveals fascinating insights into the microbial species found in human navels, showing that a few microbial species, or operational taxonomic units (OTUs), are prevalent in over 70% of individuals, while others are less common.

**Initial Setup**

- We will begin by creating a new repository named "belly-button-challenge". This project should be standalone and not part of any existing repository.
- We will clone this repository to our local machine.
- From the "Module 14 Challenge" zip file, we will copy the contents of the "StarterCode" folder into our local repository. This includes files such as `index.html`, `samples.json`, and the entire `static` folder.
- Note: While the `samples.json` file is included for reference, we won't need to access it locally.
- We will push these initial files to our GitHub repository and deploy the repository using GitHub Pages.

**Project Tasks**

1. We will use the D3 library to fetch data from the provided URL: `https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json`.

2. We will build a horizontal bar chart with a dropdown menu to showcase the top 10 OTUs for a selected individual. 
   - We will use `sample_values` as the data for the bar chart.
   - We will employ `otu_ids` for the chart's labels.
   - We will incorporate `otu_labels` as hovertext for the chart.

3. We will construct a bubble chart to represent each sample.
   - We will assign `otu_ids` for x-axis values.
   - We will utilize `sample_values` for y-axis values and marker sizes.
   - We will apply `otu_ids` for marker colors.
   - We will use `otu_labels` for the text values in the chart.
   - We will present demographic information for each sample.
   - We will display each key-value pair from the metadata JSON object on the webpage.

4. We will ensure that all plots are updated when a new sample is chosen.

We are free to design the dashboard layout according to our preference.

**Reference**
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.
