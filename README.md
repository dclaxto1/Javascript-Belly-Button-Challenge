# Javascript-Belly-Button-Challenge       
## Background   
In this assignment, I was tasked with building an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json), which catalogs microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
## Instructions  
Complete the following steps:
 
 1. Use the D3 library to read in `samples.json` from the URL `https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json`.

 2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
    * Use `sample_values` as the values for the bar chart.
    * Use `otu_ids` as the labels for the bar chart.
    * Use `otu_labels` as the hovertext for the chart.   
    
  ![image](https://github.com/dclaxto1/Javascript-Belly-Button-Challenge/assets/128431134/ef16cc58-3d0c-4e16-9c63-6eaf4f921a7a)  


 3. Create a bubble chart that displays each sample.
    * Use `otu_ids` for the x values.
    * Use `sample_values` for the y values.
    * Use `sample_values` for the marker size.
    * Use `otu_ids` for the marker colors.
    * Use `otu_labels` for the text values.
    
  ![image](https://github.com/dclaxto1/Javascript-Belly-Button-Challenge/assets/128431134/e1a5f9ea-df17-4949-acbf-2f67d1854596)


  4. Display the sample metadata, i.e., an individual's demographic information.

  5. Display each key-value pair from the metadata JSON object somewhere on the page.
  
   ![image](https://github.com/dclaxto1/Javascript-Belly-Button-Challenge/assets/128431134/1345c3b7-2e40-417f-954d-bf1609243b33)


  6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard.

  7. Deploy your app to a free static page hosting service, such as GitHub Pages.
  
## Advanced Challenge Assignment
 * Adapt the Gauge Chart from [https://plot.ly/javascript/gauge-charts/](https://plotly.com/javascript/gauge-charts/) to plot the weekly washing frequency of the individual.
 * You will need to modify the example gauge code to account for values ranging from 0 through 9.
 * Update the chart whenever a new sample is selected.
![image](https://github.com/dclaxto1/Javascript-Belly-Button-Challenge/assets/128431134/6e5772f9-609e-4809-a436-b669ac2a3b18)
 <br />

# View interactive page here:
https://dclaxto1.github.io/Javascript-Belly-Button-Challenge/
