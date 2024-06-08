1. SpaceX Falcon 9 first stage Landing Prediction
In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; 
other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, 
we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

2. Web scraping Falcon 9 and Falcon Heavy Launches Records from Wikipedia
We will be performing web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled List of Falcon 9 and Falcon Heavy launches
https://en.wikipedia.org/wiki/List_of_Falcon\_9\_and_Falcon_Heavy_launches
Objectives
Web scrap Falcon 9 launch records with BeautifulSoup:
•	Extract a Falcon 9 launch records HTML table from Wikipedia
•	Parse the table and convert it into a Pandas data frame

3. Data wrangling
We will perform some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.we will mainly convert 
landing outcomes into Training Labels with 1 means the booster successfully landed 0 means it was unsuccessful.
Objectives
Perform exploratory Data Analysis and determine Training Labels
•	Exploratory Data Analysis
•	Determine Training Labels

4. Overview of the DataSet
Using this Python notebook you will:
•	Understand the SpacexDataSet
•	Load the dataset into the corresponding table in a Db2 database
•	Execute SQL queries to answer assignment questions

5. Exploring and Preparing Data
Objectives
Perform exploratory Data Analysis and Feature Engineering using Pandas and Matplotlib
•	Exploratory Data Analysis
•	Preparing Data Feature Engineering


6. Launch Sites Locations Analysis with Folium
The launch success rate may depend on many factors such as payload mass, and orbit type.  It may also depend on the location and proximities of a launch site and the initial position 
of rocket trajectories. Finding an optimal location for building a launch site certainly involves many factors that could be discovered some of them by analyzing the existing launch 
site locations.
Objectives
•	Mark all launch sites on a map
•	Mark the success/failed launches for each site on the map
•	Calculate the distances between a launch site to its proximities
After completed the above tasks, we should be able to find some geographical patterns about launch sites.

7. Building a Dashboard
To build a dashboard is necessary to analyze launch records.An interactive dashboard contains pie charts and scatter plots to analyze data with the Plotly Dash Python library.

8. Machine Learning Prediction
Objectives
Perform exploratory Data Analysis and determine Training Labels
•	create a column for the class
•	Standardize the data
•	Split into training data and test data
•	Find best Hyperparameter for SVM, Classification Trees and Logistic Regression
•	Find the method performs best using test data

