# D3-Challenge-Data-Journalism

![Image](https://github.com/cecileung1208/D3-Challenge-Data-Journalism/blob/main/Images/newspaper.jpg)

## Background

Welcome to the newsroom! I have just accepted a data visualization position for a major metro paper. My taks is to  with analyze the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand your findings.

The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on me to sniff out the first story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included with the assignment is based on 2014 ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/). The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."


### Scatterplot - Poverty vs Health Care


Created a scatter plot between two of the data variables of `Healthcare vs. Poverty`.

The scatter plot represents each state with circle elements. the code is in the [app.js](https://github.com/cecileung1208/D3-Challenge-Data-Journalism/blob/main/D3_data_journalism/app.js) extracted from the [data.csv](https://github.com/cecileung1208/D3-Challenge-Data-Journalism/tree/main/D3_data_journalism/assets/data) by using the `d3.csv` function. The scatter plot appear as per the below image with the followig requirements:

* Include state abbreviations in the circles.

* Create and situate your axes and labels to the left and bottom of the chart.

* Note: You'll need to use `python -m http.server` to run the visualization. This will host the page at `localhost:8000` in your web browser.

* Files and details are in the [D3 data journalism folder](https://github.com/cecileung1208/D3-Challenge-Data-Journalism/tree/main/D3_data_journalism)

![Images](https://github.com/cecileung1208/D3-Challenge-Data-Journalism/blob/main/Images/scatter.jpg)
- - -

### Bonus: Impress the Boss (Optional Assignment)

Why make a static graphic when D3 lets you interact with your data?

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

You're going to include more demographics and more risk factors. Place additional labels in your scatter plot and give them click events so that your users can decide which data to display. Animate the transitions for your circles' locations as well as the range of your axes. Do this for two risk factors for each axis. Or, for an extreme challenge, create three for each axis.

* Hint: Try binding all of the CSV data to your circles. This will let you easily determine their x or y values when you click the labels.

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected. Use the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—we've already included this plugin in your assignment directory.

![8-tooltip](Images/8-tooltip.gif)

* Check out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how you should implement tooltips with d3-tip.

- - -

### Assessment

Your final product will be assessed on the following metrics:

* Creation of a **new** repository on GitHub called `D3-Challenge` (note the kebab-case). Do not add to an already existing repo.

* Completion of all steps in the core assignment

* Coherency of scatter plot (labels, ticks)

* Visual attraction

* Professionalism

* Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

**Good luck!**

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
