# American Forests Technical Exercise, by Ally Detre
American Forests Technical Exercise. November, 2025.

### Task Details:
Using Python, create a dataset that combines information from Census tracts, NLCD land cover 2021, and NCES Public & Private Schools. Data are provided.

Create a data table output that summarizes all Census tracts for that state with the following descriptive statistics reported on by tract. I have chosen Pennsylvania as my state.

* Total population
* User choice: Estimate total population of 5-9 year olds
* User choice: Estimate total housing units
* Percent forest cover
* A measure of the number of public vs. private schools
* Total schools per capita
* Trees per capita - assume a tree is 600sq-ft

### Output:

* CSV file with full PA results
* CSV file with PA summary statistics


## Project Contents
* 'Technical_Ex_AmericanForests.ipynb' : Jupyter Notebook with full workflow/steps
* 'environment.yml' : Conda-generated environment file with required packages/dependencies
* 'README.md' : You are here!
* 'Process_Documentation.docx' : Document containing a brief description of my process
* 'Technical_Exercise_Instructions' : Instructions for this project/exercise
* 'InterviewDatasets' : Folder containing census, landcover, and school datasets necessary to run this code
* 'Final Output' : Folder containing 2 final csv outputs, along with a dictionary
  * 'PA_Results.csv' : Full results dataframe
  * 'PA_Summary_Stats.csv' : Summary statistics dataframe for the state of Pennsylvania
  * 'PA_Results_Column_Dictionary.csv' : Dictionary file to describe data/columns in PA_Results.csv
* 'Checks' : Folder containing 3 checkpoint csv exports, along with a dictionary -- primarily for QA/QC along the way
  * 'pa_census_school_results.csv' : Checkpoint csv save after PA census data and school-related results
  * 'pa_forested_stats.csv' : Checkpoint csv save after PA forest analyses
  * 'pa_full_results.csv' : Checkpoint csv save after all analyses, contains all columns (whereas PA_Results.csv contains only the required descriptive statistics)
  * 'PA_Full_Results_Column_Dictionary.csv' : Dictionary file to describe data/columns in pa_full_results.csv


## Setup Instructions

### 1. Install Conda (if not already installed)
Download Anaconda from [here](https://www.anaconda.com/download)

### 2. Create Environment
Use Anaconda Prompt (Terminal on a Mac) to create the proper environment for this project by running:
````bash
conda env create -f environment.yml
````

### 3. Activate Environment
Using the Anaconda Prompt (Terminal on a Mac), activate the environment:
````bash
conda activate americanforests
````

### 4. Launch Jupyter Notebook
Again, in the Anaconda Prompt (or Terminal) run:
````bash
jupyter notebook
````

### 5. Open Technical_Ex_AmericanForests.ipynb and Run Cells!

