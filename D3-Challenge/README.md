# D3 Homework - Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

Welcome to the newsroom! In this project I am pretending that I've just accepted a data visualization position for a major metro paper. I am tasked with analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand my findings.

The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on me to sniff out the first story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included with the challenge is based on 2014 ACS 1-year estimates: [https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml), but I am free to investigate a different data set. The current data set incldes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."


### Core Assignment: D3 Dabbler (Required Assignment)

![4-scatter](Images/4-scatter.jpg)

I need to create a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age`.

Using the D3 techniques I learned in class, I created a scatter plot that represents each state with circle elements. I coded this graphic in the `app.js` file of my homework directory—made sure to pull in the data from `data.csv` by using the `d3.csv` function. My scatter plot should ultimately appear like the image at the top of this section.

* Included state abbreviations in the circles.

* Created and situate your axes and labels to the left and bottom of the chart.

* Note: I needed to use `python -m http.server` to run the visualization. This hosted the page at `localhost:8000` in my web browser.

- - -

### My Bonus Challange: To Impress the Boss (This Secssion was Optional)

Why make a static graphic when D3 lets me interact with my data?

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

I included more demographics and more risk factors. Placed additional labels in my scatter plot and give them click events so that my users can decide which data to display. Animated the transitions for my circles' locations as well as the range of my axes. Did this for two risk factors for each axis. I also had the option for an extreme challenge, and to create three for each axis.

* Hint: Tried binding all of the CSV data to my circles. This let you easily determine their x or y values when I click the labels.

#### 2. Incorporated d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. I Entered tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Added tooltips to my circles and displayed each tooltip with the data that the user has selected. Used the `d3-tip.js` plugin developed by [Justin Palmer](https://github.com/Caged)—

![8-tooltip](Images/8-tooltip.gif)

* Check out [David Gotz's example](https://bl.ocks.org/davegotz/bd54b56723c154d25eedde6504d30ad7) to see how you should implement tooltips with d3-tip.

- - -

### Assessment
Final product was assessed on the following metrics:

* Creation of a **new** repository on GitHub called `D3-Challenge` (note the kebab-case). Do not add to an already existing repo.

* Completion of all steps in the core assignment

* Coherency of scatter plot (labels, ticks)

* Visual attraction

* Professionalism


### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
