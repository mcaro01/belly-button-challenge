# belly-button-challenge
![image](https://github.com/mcaro01/belly-button-challenge/assets/125619215/2db40b4e-261f-416d-a8c6-643d458df8f8)





## Background

In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.


## Website  Link
["http://127.0.0.1:5500/Starter_Code/StarterCode/index.html"]


## Implementation of Success

Use the D3 library to read in samples.json from the URL 
    
    https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

## Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Use sample_values as the values for the bar chart.

Use otu_ids as the labels for the bar chart.

Use otu_labels as the hovertext for the chart.

![image](https://github.com/mcaro01/belly-button-challenge/assets/125619215/155c95a8-757f-4d6a-9ca5-aab51be39bfc)



## Create a bubble chart that displays each sample.

Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.


![image](https://github.com/mcaro01/belly-button-challenge/assets/125619215/afd1f32a-74c8-4f4c-8c1c-3d4786d811ec)


## Display the sample metadata, i.e., an individual's demographic information.

![image](https://github.com/mcaro01/belly-button-challenge/assets/125619215/3761e57e-f72c-45ec-8560-bd635713a5a0)


##  Advanced Challenge Assignment (Optional with no extra points earning)

The following task is advanced and therefore optional.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

![image](https://github.com/mcaro01/belly-button-challenge/assets/125619215/9362b931-8ee1-4aa7-95f0-9ddf22b3c99a)



























## File Organization and Structure


Located in the parent directory are three folders and the index.html file.
The Resources folder contains the ["samples.json'] file as a reference.
The assets folder contains a css folder which houses the styles.css file used for customization of the dashboard.
The static folder contains the two javascript files ["app.js"] and ["bonus.js'} that were used to build the dashboard.
