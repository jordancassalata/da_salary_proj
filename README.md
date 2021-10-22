# da_salary_proj
Data analyst salary project 
# Data Analyst job comparison: Project Overview 
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Cleaned data using python pandas 
* Visualized data with matplotlib and seaborn packages 

## Code and Resources Used 
**Python Version:** 3.9  
**Packages:** pandas, numpy, matplotlib, seaborn, selenium,    
**Scraper Github:** https://github.com/arapfaik/scraping-glassdoor-selenium  
**Scraper Article:** https://towardsdatascience.com/selenium-tutorial-scraping-glassdoor-com-in-10-minutes-3d0915c6d905  

## Web Scraping
Tweaked the web scraper github repo to scrape 900 job postings from glassdoor.com. Collected the following information:
*	Job title
*	Salary Estimate
*	Job Description
*	Rating
*	Company 
*	Location
*	Company Headquarters 
*	Company Size
*	Company Founded Date
*	Type of Ownership 
*	Industry
*	Sector
*	Revenue
*	Competitors 

## Data Cleaning
After scraping the data, I needed to clean up some of the data. I made the following changes and created the following variables:

*	Parsed numeric data out of salary 
*	Made columns for employer provided salary and hourly wages 
*	Removed rows without salary 
*	Parsed rating out of company text 
*	Made a new column for company state 
*	Transformed founded date into age of company 
*	Made columns for if different skills were listed in the job description:
    * Python  
    * SQL
    * Excel  

## Data Visualization
After cleaning the data, I went ahead and started to analyze the data and make visualizatoions

![alt text](https://github.com/jordancassalata/da_salary_proj/blob/main/avg_salary_per_state.png "Average salary per state")
![alt text](https://github.com/jordancassalata/da_salary_proj/blob/main/jobs_per_state.png "How many jobs per state")
