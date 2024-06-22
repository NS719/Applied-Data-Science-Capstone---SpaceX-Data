# Data Science Capstone Project: SpaceX Launch Data Analysis

## Project Overview
The commercial space age is here, companies are making space travel affordable for everyone. Perhaps the most successful is SpaceX. SpaceX’s accomplishments include:
- Sending spacecraft to the International Space Station.
- Starlink, a satellite internet constellation providing satellite Internet access.
- Sending manned missions to Space.

One reason SpaceX can do this is the rocket launches are relatively inexpensive. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each. Much of the savings is because SpaceX can reuse the first stage. If it can be determined whether the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

These diagrams from Forest Katsch, a 3D artist and software engineer, will help understand the scale and components of the Falcon 9. 
![Components of the SpaceX Falcon 9 in its fairing configuration](https://zlsadesign.com/infographic/vehicle/spacex-falcon9-components-tall.jpg "Falcon 9 Components")
The payload is enclosed in the fairings. Stage two, or the second stage, helps bring the payload to orbit, but most of the work is done by the first stage. The scale of the first stage is shown here, next to a person and several other landmarks.
![SpaceX Falcon 9 Scale](https://zlsadesign.com/infographic/vehicle/spacex-falcon9-scale-tall.jpg "Falcon 9 Scale")
This stage is quite large and expensive. Unlike other rocket providers, SpaceX's Falcon 9 can recover the first stage. Sometimes the first stage does not land or may crash. Other times, Space X will sacrifice the first stage due to the mission parameters like payload, orbit, and customer.

In this capstone project, I assume the role of a Data Scientist working for a startup intending to compete with SpaceX. I have determined the price of each launch by gathering information about Space X and created dashboards. Instead of using rocket science to determine if the first stage will land successfully, I have trained a machine learning model and used public information to predict if SpaceX will reuse the first stage, thus determining the cost of a launch.
This project is a graded assignment for [Applied Data Science Capstone](https://www.coursera.org/learn/applied-data-science-capstone) by IBM, the final course in the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science).

## Objectives

### Data Collection 
Make a get request to the SpaceX API
- Request to the SpaceX API
- Clean the requested data

### Web Scraping
Web scrap Falcon 9 launch records with `BeautifulSoup`
- Extract a Falcon 9 launch records HTML table from Wikipedia
- Parse the table and convert it into a Pandas data frame

### Data Wrangling
Perform exploratory  Data Analysis and determine Training Labels 
- Exploratory Data Analysis
- Determine Training Labels

### Exploratory Data Analysis with SQL 
- Load the dataset into the corresponding table in a Db2 database
- Execute SQL queries

### Exploratory Data Analysis with Visualization 
Perform exploratory Data Analysis and Feature Engineering using `Pandas` and `Matplotlib`
- Exploratory Data Analysis
- Preparing Data  Feature Engineering

### Interactive Visual Analytics
Perform interactive visual analytics using `Folium`
- Mark all launch sites on a map
- Mark the success/failed launches for each site on the map
- Calculate the distances between a launch site to its proximities

### Interactive Dashboard
Build a `Plotly Dash` application for users to perform interactive visual analytics on SpaceX launch data in real-time.
- Add a Launch Site Drop-down Input Component
- Add a callback function to render `success-pie-chart` based on selected site dropdown
- Add a Range Slider to Select Payload
- Add a callback function to render the `success-payload-scatter-chart` scatter plot

### Predictive Analysis (Classification) using Machine Learning
Perform Exploratory Data Analysis and determine Training Labels
- Create a column for the class
- Standardize the data
- Split into training data and test data
- Find best Hyperparameter for SVM, Classification Trees and Logistic Regression
- Find the method performs best using test data

### Presentation
Create a presentation that showcases all performed analysis and conclusions
