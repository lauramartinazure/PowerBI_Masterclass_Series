# PowerBI_Masterclass_Series
This is a repository containing datasets, PowerBI templates, and finished reports for a three-session PowerBI Masterclass Series

## BEFORE EACH SESSION INSTRUCTIONS  
Whether you're joining me for one, two, or all three sessions, in any combination, you;ll need to complete the following steps:

### If you're familiar with (or want to explore) GIT:
* Download and install GIT
* Get this repository's URL from the green button on the repository page.
* In your ommand line, navigate to the directory where you want the folder containing all the files to be by typing `cd <path to your directory location>`
* In your command line, type `git clone <repository URL>`. This will copy the latest version of all the files in this repository. Be aware that there are some big files in here!

### If you're not familiar with GIT:
* Simply download the contents of this repository as a zip file, then unzip its contents.

### Download and Install Microsoft PowerBI
* Link: https://www.microsoft.com/en-us/download/details.aspx?id=58494 
* Please note that this requires a Windows computer; unfortunately, PowerBI is not yet supported on Mac.
* If you need IT/a system admin to do this step, please ensure it is done well ahead of time.

### SESSION 1 JOINERS: Open a BLANK new PowerBI report. Other reports are 'waypoints' on our journey that will allow you to jump in.
### SESSION 2 AND/OR 3 JOINERS: Open the report indicated by your instructor.

## Series Contents:

### Session 1: Loading and Preparing Data

#### Dataset information

* Datasets are from Gapminder and the Google Covid19 Datasets.
* Gapminder: https://www.gapminder.org/data/ 
* Child mortality 0-5
* Crude birth rate per 1000 population
* Crude death rate per 1000 population
* Health expenditure per capita, $
* Health expenditure as % GDP
* Life expectancy - female
* Life expectancy - male
* Google: https://health.google.com/covid-19/open-data/raw-data 
* Geography Data
  * Note: We’ve organized the geographical hierarchy as follows:
  * 0: Country
  * 1: Province, state, or local equivalent
  * 2: Municipality, county, or local equivalent
  * 3: Locality that may not conform with an established hierarchical category. For example, "city" might span multiple municipalities.
  * The location key is determined by its level: So, country-level data for the United States would use the location key US; state-level data for California, US_CA; and Santa Clara County data, with an FIPS code of 06085, would use US_CA_06085.
  * Level 3 data may be nested within levels 0 or 1. The city of San Francisco’s location key is US_CA_SFO.
* Health Data
* Vaccinations Data (from URL and demo of Azure Cloud Blob Storage)
* Metadata 

### Session Content:

* Loading Data 
  * Loading single CSV file
  * Loading multiple files from folder (if they contain the same structure)
  * Loading data from URL
  * Loading data from cloud storage (Azure Cloud Blob Storage)
  * Loading Data from API - REST countries, specific URL (no key) “https://restcountries.com/v3.1/all?fields=name,capital,currencies”

* Inspecting Data
  * Column Statistics
  * Data Types

* Cleaning Data
  * Down-selecting columns
  * Changing data types
  * Merging datasets
  * Appending datasets
  * Advanced data cleaning

### Session 2: Modelling Data and Basic Visualisations

### Session Content:

* Principles of data modelling
  * `1:1` relationships
  * `1: *` and `* : 1`
  * `* : *` and why to avoid
* Central date/location tables for cross filtration
* Creating/deleting data relationships
* Visualisations and interactivity/cross-filtering

* Creating visualisations - The basics:
  * Adding fields
  * Adding legends
  * Customising visualisations
  * Formatting size, title, changing column names
  * Choosing legend colours
  * Formatting consistently
 
* Basic DAX for Measures

### Session 3: More Advanced Visualisations and Maximising Report Impact

* Creating a Visually Impactful Report
* Colour schemes
* Formatting consistently
* Creating Interesting Visuals: Maps
* Tooltips
* More advanced Measures using DAX
* Custom Visuals and using Python in PowerBI
* Publishing to a PowerBI Workspace and managing access

