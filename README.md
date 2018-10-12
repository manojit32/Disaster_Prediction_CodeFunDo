# Disaster Prediction and Management - A CodeFunDo++ Challenge

As the name suggests, Natural Disasters are inevitable in our world. Thousands of poor lives are taken by Natural Disasters every year. The idea of "preventing" natural disasters is somewhat impossible to achieve. However, with advancement of technology, Prediction and Management of Natural Disasters are made possible. In our project, we will highly focus on Natural Disaster Prediction, and provide some valuable ideas and implemenations on Disaster Management as well.

## 1. Natural Disaster Prediction ::

### a) Prediction of Earthquakes in South-East Asian regions

From the previous 3 years, India and subcontinental regions like Pakistan, Afghanistan, China etc. are sufferring from frequent earthquakes. Suddenly, Earthquake Prediction became a necessity in these regions. In this model, we are taking a Dataset from [Incorporated Research Institutions for Seismology](http://ds.iris.edu/ds/), which contains 30000 earthquake instances for India and Surrounding regions from year 2015 to end of 2017. The dataset contains 
- Latitude, Longitude value
- Timestamp for the earthquake
- Region of the earthquake
- Magnitude in Richter Scale
- Depth of the epicenter

We will use these past earthquake data to predict future earthquakes in these regions. The models for this prediction will be based on **Recurrent Neural Networks**. With the help of State-of-the-art Feature Selection algortihm and Deep Neural Network, we are hoping to get a moderately high accuracy with the prediction datasets.

### b) Disaster Forecasting of the world

Planning and budgeting for disaster responses in the coming years requires some guess at numbers and types of disasters and the number of people affected by those. This model will look at Historical Disaster data from the last 35 years and estimate expectations in the coming years. The dataset is taken from **Centre for Research on Epidemiology of Disasters (CRED)**. The **EM-DAT(Emergency Events Database)** contains data on natural and technological disasters from 1900 to 2015. We will only take relevant data from 1980 to 2015. The dataset contains - 
- Year
- Country Name
- Occurrence
- Total deaths, Injured, Affected, Homeless
- Total affected
- Total damage

We will use these past historical disaster data to create a model to forecast disaster data for coming 5 years. The model we will use for forecasting **Total Damage** and **Total Affected** is a **Moving Average Model**, which will predict numbers for next 5 years. It will be very helpful for planning for disaster responses in the coming years. 
