

# Project Summary

## Repository Navigation

<UL>
<LI> This is the README.md file. Inside are the steps I took to complete the project and links to different sources.
<LI>data is a folder containing the data from KING COUNTY I used to complete this project as well as column names to the data.
<LI>student.ipynb is the notebook that has the steps I described in this README.md in play by play.
<LI>CONTRIBUTING.md contains messages about contributing to Learn.co.
<LI>halfway-there.gif is a gif expressing the progress this project implies.
<LI>king_county_stat_sheet.pdf is a pdf I included that encompasses the data I used to better undestand KING COUNTY.
<LI>LICENSE.md is a little document that tells how flatiron school owns this content.
<LI> presentation.pdf is a pdf of the slide presentation.
<UL/>
    
## Data Science Steps
    
### Business Declaration
The first thing I did was identify the stakeholders of the project, whom I would present my findings to. Then I described the
real world problem I was looking to address. In this case it was learning which aspects of the home can be renovated for 
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
from my data except price, my target variable. The first model was a baseline model and roughly estmated the prediction target. I made tweaks afterwards in a step by step process that came to present a model that held up to linearity and with only 
features found to be statistically significant.

### Interpretation
I had modeled my data with room left for interpretation. I scoured the summary and concluded that the number of bathrooms the homeowner has was a noteworthy feature since it was an aspect the homeowner had control over. Likewise with square
footage, since I saw it was very influential and another possible change a homeowner could make. I found how much both of 
those features affect the price on average.

### Business Implications
I concluded in the same fashion that I started, business. I recommended how I would use the findings for recommendations
to customers using a free tool that would estimate home values. I felt that way the stakeholder had a concrete way to
leverage the knowledge gained in this project.


## Presentation and Sources

Presentation: https://docs.google.com/presentation/d/17Zwdaytolsq9H5br2-hWuQXTR6gq422plD69R3fnvEw/edit?usp=shari
    
<DL>Sources:
<DT>KING COUNTY statistics: 
<DD>https://kingcounty.gov/depts/executive/performance-strategy-budget/regional-planning/Demographics.aspx
<DT>Coding Inquiries: 
<DD>https://stackoverflow.com/
<DT>Census 2020: 
<DD>https://www.census.gov/programs-surveys/decennial-census/decade/2020/2020-census-main.html
<DT>Checking Linearity:
<DD>https://github.com/learn-co-curriculum/dsc-modeling-your-data
<DL/>
    
## Blog post:https://medium.com/@greennicholas62/exploratory-data-analysis-and-descriptive-statistics-a613fe050bc9

## Interpretation

My model concluded that the number of bathrooms in the home and the square footage were the key determinents of house price.

I found that for bathrooms, every increase in the Z-score of the number of bathrooms produced about a 5.5 percent 
of new home value on average.

Square footage was very influential. I found that for increase in Z-score of a house's square footage, the house's value 
would increase by 15 percent on average.





