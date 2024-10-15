# Data Visualization of Global Climatic and Energy Trends

# Overview
  Our group wanted to look into the topic of climate trends around the world based on regions. We wanted to see how the rise in temperature over several years affected different parts of the world and how many of these countries are using sustainable energy and if that is making a difference.

Here are the datasets we used for the base of our data exploration:
https://www.kaggle.com/datasets/jawadawan/global-warming-trends-1961-2022 
This dataset looks at annual surface temperatures for over 100 countries spanning from 1961-2022. 
https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy
This dataset looks at sustainable energy factors across over 100 countries from 2000 to 2020. 

We wanted to answer three main questions with our visualizations:
1. What amount of CO2 emissions did each country produce over 25 years? [GeoJSON Map]
2. What percentage of each country’s current energy production is sustainable? [Bar Chart]
3. How did the temperature averages for each country change over 25 years? [Scatter plot]

# How to Interact with the Project
  This project contains a main HTML page (link here). You can interact with this page in two different ways: scrolling down the page to view each visualization and interacting with them individually on the main page or clicking the individual hyperlinks on the main HTML page (this will open a separate HTML page for each visualization that can be interacted with).

# Breakdown of our Visualizations
Emissions Cloropleth Map
(insert information about how to interact and what you see here)
Sustainable Energy Bar Charts
(insert information about how to interact and what you see here)
Annual Surface Temperature Scatter Plots
(insert information about how to interact and what you see here)

# Ethical Considerations
  Data accuracy and representation are essential when using public datasets and transforming the data within them. We looked at the sources for each of our Kaggle datasets and noted that the global warming trends dataset did not list an exact source, it references reputable climate monitoring agencies and research institutions. We acknowledge that this does not suffice as a sufficient source for the data and can have implications on the accuracy of what is depicted in the project. On the other hand, our second source for global data on sustainable energy contains reference to the data being sources from the World Bank and International Energy Agency. The main source of the data in this kaggle set is from this website
https://ourworldindata.org/sdgs/affordable-clean-energy. It is important to note that there were a numerable amount of empty cells across the first and second dataset, both of which were filled with 0's as a representation of no data present, in our clean data CSV files. 

  We also want to note the ethical use of our visualizations in this project. We tried to avoid misleading visualizations by distorting the scale of the data. Our bar charts have consistent axis scales and our map uses the same color scheme. We want to note that there are inherit baises in the data since different regions are going to have different socio-economic and geographical factors that affect their renewable energy sources and use. This will also have an impact on temperature changes over time. 

# References for the data sources
  The following Kaggle datasets were used as the base of our data exploration for this project.   
https://www.kaggle.com/datasets/jawadawan/global-warming-trends-1961-2022 
This dataset looks at annual surface temperatures for over 100 countries spanning from 1961-2022. 
https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy
This dataset looks at sustainable energy factors across over 100 countries from 2000 to 2020. 

# References for code sources
The basis for the Emissions Cloropleth Map code was built using the code found in this notebook (https://www.kaggle.com/code/anshtanwar/starter-notebook-global-sustainable-energy). The code was modified based on our clean CSV data. The seaborn library that was used was also based on the same notebook that utilizes Seaborn to create different visualizations. Here is an image of the seaborn visualization that was used in the notebook: 
![image](https://github.com/user-attachments/assets/4bd43d60-18d1-4960-bfd6-7c67fb91170e)

We utilized https://seaborn.pydata.org/index.html as a resource to see what different kinds of visualizations could be created with the Seaborn library in Python. Ultimately, Xpert Learning Assistant and ChatGPT were used to fully curate the Seaborn visualization (for error troubleshooting and additional suggestions on cleaning up the visual). 

We also want to note that it was AI that suggested we use the write.HTML function in python to create our base HTML pages for our visualizations. This additional tool was useful in saving time. Although the base HTML pages were created using a python library, Andrew created our main HTML page that integrated the three visual HTML pages. The following resources were used to assist him in that process: https://stackoverflow.com/questions/12032664/load-a-html-page-within-another-html-page (Loading HTML pages within HTML), https://www.w3schools.com/html/html_iframe.asp (iframe tutorial). 

# Contributors to the Project
This project would not have been made possible without the following individuals: Andrew Pohle, Lauren Graves, Jessica Maranto, and Caitlin McMahill. A huge thank you to the collaborative efforts of this individuals and to the resources used to provide the foundation for this project.



  




