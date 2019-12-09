# Challenge 15 - Interactive Data Visualization with Plotly

## Belly Button Biodiversity

![Bacteria by filterforge.com](Images/microbes-sem.jpg)

The coolest study of biodiversity on the human body on the planet!
The belly button is one of the habitats closest to us, and yet it remains relatively unexplored. In January 2011, [The Public Science Lab](http://robdunnlab.com/) launched Belly Button Biodiversity to investigate the microbes inhabiting our navels and the factors that might influence the microscopic life calling this protected, moist patch of skin home. In addition to inspiring scientific curiosity, Belly Button Biodiversity inspired conversations about the beneficial roles microbes play in our daily lives.

For this challenge, built an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).

Used Plotly.js to build interactive charts for your dashboard.

* Created a PIE chart that uses data from top 10 samples to display  microbe and percentage of each microbe found in the sample set.

  * Use `sample_values` as the values for the PIE chart.

  * Use `otu_ids` as the labels for the pie chart.

  * Use `otu_labels` as the hovertext for the chart.

  ![PIE Chart](Images/pie_chart.png)

* Created a Bubble Chart that uses data from samples to provide a detailed visulization of color coded microbes present in each sample and its concentration in each sample.

  * Use `otu_ids` for the x values.

  * Use `sample_values` for the y values.

  * Use `sample_values` for the marker size.

  * Use `otu_ids` for the marker colors.

  * Use `otu_labels` for the text values.

  ![Bubble Chart](Images/bubble_chart.png)

* Display the sample metadata 

  * Display each key/value pair from the metadata JSON object.

  ![Sample Select](Images/SampleSelect.png)

* All the plots are updated any time that a new sample is selected.

## Advanced Challenge 

* Adapt the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the Weekly Washing Frequency of bellybutton which depends upon the the microbes and its percentage present in a given sample.


![Weekly Washing Frequency Gauge](Images/gauge_chart.png)

## Deployment: This was deployed on Amazon Web service.

- - -





### Copyright

Indira V. Poovambur © 2019. 
