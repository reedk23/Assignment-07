## Assignment-07

This is our seventh assignment for BIOL390 in the summer of 2020. The purpose of this project is to give you some more practice manipulating and graphing COVID-19 data to make choropleth maps. Like before, you should fork my repo and clone it to your local machine. Follow the instructions to complete the assignment while committing periodically and pushing up to your GitHub remote. When you are done, do a final knit and submit the HTML file to complete this assignment. Then file a pull request so that I can admire your work on GitHub. This assignment requires the dplyr and stringr skills that you should have been picking up by now from working in DataCamp. 

## Data URL
You will be using COVID-19 data from the CDC for this project. You can access it from here: [https://www.cdc.gov/covid-data-tracker/#cases](https://www.cdc.gov/covid-data-tracker/#cases).

## Instructions
* Create folders for raw_data and output. Put the CDC dataset into raw_data (I haven't found a link to the dataset yet - you may need to do this manually).

* Write a chunk that loads the needed tidyverse libraries but does not show up in any way in the final HTML document.

* Write a chunk that creates a tidy dataset called output/deaths_by_state.csv. This file should have variables named State, and Total_Deaths. The dataset should only contain information for the 50 US States and the District of Columbia; ditch the rest. This chunk should not display anything in the final HTML document.

* Write another chunk that creates a tidy dataset called output/normalized_deaths_by_state.csv. This file should have variables named State, and Deaths_per_100000. ould only contain information for the 50 US States and the District of Columbia; ditch the rest. Once again, this should not show up in the final HTML.

* Write a chunk that uses choroplethr to create a map of the US showing total COVID deaths. Add an informative title. What is your interpretation of this plot?

* Write a chunk that uses choroplethr to create a map of the US showing total COVID deaths. Add an informative title. What is your interpretation of this plot?
