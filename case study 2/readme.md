# Welcome to the Data Analysis Process - Case Study 2

In this second case study, you'll be analyzing fuel economy data provided by the EPA, or Environmental Protection Agency.
https://www.epa.gov/compliance-and-fuel-economy-data/data-cars-used-testing-fuel-economy

# Data Overview

We'll learn more about these features as we go. Right now, we have a good idea of what data we're working with, so let's answer some questions. You'll see quick descriptions of each feature again in the next section to help you.
Data Source

Below are the web pages from this video. Note that the datasets we'll be working with are slightly simpler than those found here.

*    EPA Fuel Economy Testing https://www.epa.gov/compliance-and-fuel-economy-data/data-cars-used-testing-fuel-economy
*    DOE Fuel Economy Data https://www.fueleconomy.gov/feg/download.shtml/


# 1. Asking Questions
# Fuel Economy Data

This information is provided by the U.S. Environmental Protection Agency, Office of Mobile Sources, National Vehicle and Fuel Emissions Laboratory.

|Attribute|Description| |-| |Model|Vehicle make and model| |Displ|Engine displacement - the size of an engine in liters| |Cyl|The number of cylinders in a particular engine| |Trans|Transmission Type and Number of Gears| |Drive|Drive axle type (2WD = 2-wheel drive, 4WD = 4-wheel/all-wheel drive)| |Fuel|Fuel Type| |Cert Region*|Certification Region Code| |Sales Area**|Certification Region Code| |Stnd|Vehicle emissions standard code| |Stnd Description*|Vehicle emissions standard description| |Underhood ID |This is a 12-digit ID number that can be found on the underhood emission label of every vehicle. It's required by the EPA to designate its "test group" or "engine family." This is explained more here| |Veh Class|EPA Vehicle Class| |Air Pollution Score|Air pollution score (smog rating)| |City MPG|Estimated city mpg (miles/gallon)| |Hwy MPG|Estimated highway mpg (miles/gallon)| |Cmb MPG|Estimated combined mpg (miles/gallon)| |Greenhouse Gas Score|Greenhouse gas rating| |SmartWay|Yes, No, or Elite| |Comb CO2*|Combined city/highway CO2 tailpipe emissions in grams per mile|
  
  

# 2. Assessing Data

The files all_alpha_08.csv and all_alpha_18.csv discussed in the previous pages have been provided in the workspace for you here to access. Use pandas to explore these datasets in the Jupyter Notebook below to answer the quiz questions below the notebook about these characteristics of the data:

*    number of samples in each dataset
*   number of columns in each dataset
*  duplicate rows in each dataset
* datatypes of columns
*    features with missing values
*    number of non-null unique values for features in each dataset
*    what those unique values are and counts for each