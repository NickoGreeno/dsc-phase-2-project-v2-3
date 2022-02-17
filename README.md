

# Project Summary

## Repository Navigation

*This is the README.md file. Inside are the steps I took to complete the project and links to different sources.
*data is a folder containing the data from KING COUNTY I used to complete this project as well as column names to the data.
*student.ipynb is the notebook that has the steps I described in this README.md in play by play.
*CONTRIBUTING.md contains messages about contributing to Learn.co.
*halfway-there.gif is a gif expressing the progress this project implies.
*king_county_stat_sheet.pdf is a pdf I included that encompasses the data I used to better undestand KING COUNTY.
*LICENSE.md is a little document that tells how flatiron school owns this content.

## Data Science Steps

### Business Declaration
The first thing I did was identify the stakeholders of the project, whom I would present my findings to. Then I described the
real world problem I was looking to address. In this case it was learning which aspects of the home can be renovatto d for 
maximum value and to understand the metric to that value.

### Data Understanding
After understanding my target, I wanted to understand where my data came from. I identified how it summarized the population 
I hoped to make inferences about. I also made sure to identify any data limitations or matters that my data would have trouble
dealing with.

### Data Cleaning
After I gave my data the greenlight and understood what each part represented, I filled any missing values the data had. This
is important since missing values would cause snags in the modeling process. 

### Exploratory Data Analysis
Having cleaned my data, I analyzed trends in the data that could generate questions. One question I asked was what made 
renovated houses so much more expensive than unrenovated houses. I made sure to model that data to visualize the questions
I was asking.

### Modeling
I started this portion by dummying categorical variables for regression purposes. After that, I made a model using all the features
from my data except price which was my my target variable. The first model was a baseline model and was a little messy. I made 
small tweaks afterwards in a step by step process that came to present a model that held up to linearity and with only 
features found to be statistically significant.

### Interpretation
I had modeled my data with room left for interpretation. I scoured the summary and concluded that the categorical variable
condition was a noteworthy feature since it was an aspect of the house the homeowner had control over. Likewise with square
footage since I saw it was very influential and another possible change a homeowner could make. I found how much both of 
those features affect the price on average.

### Business Implications
I concluded in the same fashion that I started, business. I recommended how I would use the findings for recommendations
to customers using a free tool that would estimate home values. I felt that way the stakeholder had a concrete way to
leverage the knowledge gained in this project.


## Presentation and Sources

*Presentation: 
*Sources:
    *KING COUNTY statistics: https://kingcounty.gov/depts/executive/performance-strategy-budget/regional-planning/Demographics.aspx
    
*Blog post:https://medium.com/@greennicholas62/exploratory-data-analysis-and-descriptive-statistics-a613fe050bc9

## Interpretation

My model conluded that condition of the home and the square footage were the main determinents of house price.

I found that for conditions were like brackets. All houses were either graded poor, fair, average, good, or in very good
condition. if a house went from one bracket to another than it was automatically a certain percentage more valuable 
relative to the average house.

Square footage was very influential. I found that for every percentile increase in a houses square footage compared to 
other houses, the house's value would increase by 15 percent. Therefore if a house were went from 50th percentile to
the 52nd, the house would increase its value by 30 percent on average.





