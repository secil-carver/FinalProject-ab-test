<style = "font-family:georgia,garamond,serif;font-size:20px;font-style:italic;">
    
# Rider Demographics And Their Bike Share Patterns

## by Secil Carver
<a href="https://www.udacity.com/course/data-analyst-nanodegree--nd002">Udacity Data Analyst Nanodegree</a><br>
<em>Project 5: Data Visualization</em>
<>

## A/B Testing
<a href="https://www.udacity.com/course/data-analyst-nanodegree--nd002">Udacity - Data Analyst Nanodegree</a><br>
<em>Project 3: Practical Statistics</em>

### Table of Contents

1. [Project Overview](#overview)
2. [Project Flow](#projectflow)
3. [Requirements](#requirements)
4. [Key Files](#keyfiles)
5. [Summary of Findings](#findings)
6. [Acknowledgements](#acknowledgements)

<p style = "font-family:georgia,garamond,serif;font-size:16px;font-style:italic;">
    
### 1. Project Overview <a name="overview"></a>

For this project, I worked to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. The goal was to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.
    



### 2. Project Flow <a name="projectflow"></a>

I have organized the current notebook into the following sections:

- Introduction
- Part I - Probability
- Part II - A/B Test
- Part III - Regression
- Final Check
- Submission

### 2. Requirements <a name="requirements"></a>

This project was created using Anaconda's Jupyter Notebook using the language python. The following language and packages were used:

- python 3.7.11
- pandas 
- numpy 
- matplotlib 
- random


### 3. Key Files <a name="keyfiles"></a>

The project consist of one main file, and two datasets: 
- `Analyze_ab_test_results.ipynb`: 
    This is the file I used to gather the data, assessed and used models for analysis.
    
-- Datasets used: `ab_data.csv`, `countries.csv`

    
### 4. Summary of Findings <a name="findings"></a>
    
To find out if a new web page has better conversion than the old web page, I first looked at a Probability model.  The result did not indicate a major difference between the two groups. I proceeded to perform an AB test simulating probabilites of conversion of users that used the new webpage and the old page, then compared it to my probability model. The results did not show any significant differences between the two groups.

Finally I performed a Logistic regression model, after merging the dataframe with the countries dataframe in order to compare user conversion of each country, then user new page interaction in each country. None of the results showed significant enough relatonships to predict user conversion in a country, or user new page interaction leading to conversion in any of the countries. 
    
Over all, since most of the tests did not indicate that there was greater conversion for the new web page than the old web page, we cannot conclude that there will be any added benefit to implementing the new web page. However, the data collected was only from 23 days, and perhaps a longer running test would give a more definitive answer.
    
### 5. Acknowledgements <a name="acknowledgements"></a>
This project was completed as a requirement for Udacity's <a href="https://www.udacity.com/course/data-analyst-nanodegree--nd002">Data Analyst Nanodegree</a>. The dataset was provided by Udacity.


```python

```
