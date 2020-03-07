# Welcome to the Colorado Bear Hunting Draw Analysis 

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## The Goal of this presentation: 
1. Provide a better understanding of how many people are submitting applications each year
2. Attempt to identify how many points it takes to be successful in a given unit 
3. Identify how many bear hunting tags are typically avaiable after the draw each year

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## The target audience: 
1. Colorado Department of Wildlife (CDOW)
2. Hunters interested in pursuing bear in Colorado (Residents/Non Residents)

### This data provides the Colorado Department of Wildlife:
- Introduction to where most bear hunters desire to hunt
- An idea of where bear management focus needs to be
- Which units might need some assistance to attract more bear hunters 
&nbsp;

### The analysis also provide hunters: 
- Where to spend there points (RES/NR)
- How many points they need for a unit they desire (RES/NR)
- Which units to not spend their points 

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## The data
All data used in this project is publically available: 
1. Colorado Department of Wildlife website
2. Huntscore.com (Assist with analysis)
&nbsp;

![Data_Image](https://user-images.githubusercontent.com/35975720/75626938-00c85e80-5b89-11ea-9595-77c4d9102d62.PNG)

&nbsp;
&nbsp;
&nbsp;
&nbsp;


## Top 10 units with the most left over license
<iframe width="1200" height="500" frameborder="0" scrolling="no" seamless="seamless" src="//plot.ly/~alee0187/9.embed"></iframe>
&nbsp;

1. Unit BE041O1R 
   - Overall most left over tags 
   - No left over tags in 2012
&nbsp;

2. Unit BE035O1R
   - Second highest unit with left over tags
   - No left overs tags in 2014
   &nbsp;

3. Unit BE004O1R
   - Most consistent from 2012 - 2019 (only unit with left overs every year)

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## The most popular units
<iframe width="1200" height="500" frameborder="0" scrolling="no" seamless="seamless" src="//plot.ly/~alee0187/17.embed"></iframe>
&nbsp;

### Criteria: 
The units were selected based on how many applications were submitted for a specific unit. 

1. Total of 7 units that had high applicants since 2015
   - BE061O1R
   - BE041O1R
   - BE075O1R
   - BE012O1R
   - BE004O1R
   - BEE71O1R
   - BE062O1R

2. Unit BE061O1R consistently remained popular
   - Hunt Score 82/100 (What makes this unit popular)
      - 76% of the unit is public land 
      - Scored 72 for opportunity
      - Scored 100 for trophy potential
      

3. Everyone drawing for BE004O1R should be selected
   - Hunt Score 93/100 (What makes this unit popular)
      - 63% of the unit is public
      - Easy access
      - Opportunity - 100

4. Four units with high applicants for a single year 
   - Hard to draw
   - Minimal public access

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## Wasted preference points
<iframe width="1200" height="500" frameborder="0" scrolling="no" seamless="seamless" seamless="seamless" src="//plot.ly/~alee0187/11.embed"></iframe>

### These units had left over tags, but hunters used points during the draw (lets hope its an error)
1. One point equals one year
2. Highest points wasted : 
   - 17 points 2018
   - 16 points 2018, 2019
   - 15 points 2017, 2016, 2015

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## 2019 Preference Points table 

<iframe width="1200" height="500" frameborder="0" scrolling="no" seamless="seamless" src="//plot.ly/~alee0187/15.embed"></iframe>

1. Identify how many points it took to be successful in a given unit

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## Machine Learning Tests

### Heat map of dataset

![heatmap_before](https://user-images.githubusercontent.com/35975720/76047630-8305a980-5f20-11ea-8e03-723e03519450.PNG)

![heatmap_after](https://user-images.githubusercontent.com/35975720/76047636-87ca5d80-5f20-11ea-90bb-550fbadd4042.PNG)

1. Filled in necessary numbers (NaN to 0 as appropriate)
2. Removed data between 2012 - 2014 (Data provided was different compared to 2015-2019)

### Two machine learning algorthims were used for this dataset. 

1. Test one: Logistic Regression
   - 52% accuracy

2. Test two: K-Nearest Neighbors (KNN)
   - 47% accuracy
   
- Neither algorithm provided the accuracy desired
   - Restructure dataset?
   - Different algorithm?
- 2020 Bear draw slighly changed 
- 2020 data is not provided to test the algorithm (variables) 
   - If accuracy was achieved, average of the past 2 years would be used as variables

&nbsp;
&nbsp;
&nbsp;
&nbsp;

## Things to update
1. Restructure data for Machine Learning algorithms?
2. Create a database (SQL) to store data as it grows with other species
3. Coordinate with CDOW - possible access to data not in a PDF format


&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;

[comment]: <> You can use the [editor on GitHub](https://github.com/d-lee25/bear_analysis.github.io/edit/master/index.md) to maintain [comment]: <> and preview the content for your website in Markdown files.

[comment]: <> Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your [comment]: <> site, from the content in your Markdown files.




