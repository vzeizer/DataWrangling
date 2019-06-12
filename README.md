# Project Data Wrangling of Udacity's Nanodegree Data Science Foundations II




## Project Instructions (according to Udacity)


### Introduction

Real world data are rarely clean
Gather data from a series of sources in a variety of formats, evaluate its quality and tidyness and, then, clean them.
This is called **Data Wrangling**.

You will document your efforts of wrangling in your Jupyter notebook, and show them by means of analyses and visualizations using Pyhton and/or SQL.

The dataset you will do wrangling (and analyze and visualize) is the data of the tweets of the user of Twitter @dog_rates, also known as WeRateDogs.
We RateDogs is a Twitter's account that classifies the dogs of people with a commentary with good humour about the dogs.
It was initiated in 2015 by the universitary student Matt Nelson and it was covered in the international midia. 
On October 2017 it had over 3.7 million followers.
These classifications have always a denominator out of 10.
But the numerators?
Almost always greater than 10. 11/10, 12/10, 13/10, etc.
Why? Because "they are good dogs, Brent."

WeRateDogs gave unique access to Udacity to its tweets data in this project.
This data contains basic data of the tweets for all its over 5000 tweets as they were in 1st August 2017.

### What to install?

The following packages (i.e., libraries) are necessary to finish this project:

-> pandas
-> numpy
-> requests
-> tweepy
-> json


### Gathering data for this project


Collect each of the three chunks of data according to the Jupyter Notebook entitled wrangle_act.ipynb.

The file WeRateDogs.
This file is given to you, then imagine it in your hands.
Download this file manually by clicking in the following link: twitter_archive_enhanced.csv

The predictions of images in tweets, i.e., which dog race or inanimated object is present in each tweet. 
This file image_predictions.tsv is hosted in Udacity and must be downloaded programmatically by using the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

The count of retweets and favorites (like) in each tweet, at least, and any additional data that you find interesting.
Take a look at the Twitter API (using the tweets ID in the file of the Twitter of WeRateDogs) for the complete dataset of each tweet using the library Tweepy from Python and store these data in a file named tweet_json.txt, where the stored JSON data of each tweet should be in its own line.
Then, read this .txt line by line in a Pandas DataFrame with (at least) tweet's ID, retweets count and favorites count.
**Obs.: do not include your Twitter API keys and access tokens when submitting your project.**


### Evaluating the data for this project

After collecting each chunk of data, evaluate them visually and by means of programming to find quality and tidyness issues.
Detect and document at least eight (8) quality problems and two (2) tidyness issues in your Jupyter notebook.
To meet the specifications, the problems that satisfy the motivation of the project must be evaluated.

### Cleaning data for this project

Clean each of the problems you documented when evaluating.
The result must be a master Pandas dataframe (or dataframes, when appropriated) of high quality and tidyness.
Again, the problems that satisfy the motivation of the project must be clean.

### Storing, analyzing and visualizing data for this project

Store the cleaned dataframe(s) in a csv file, with the main file entitled twitter_archive_master.csv
If more than one exist, name them properly.
Besides, you can store the cleaned data in a SQLite database (that should also be sent, in case you choose it)

Analyze and visualize your wrangled data in your Jupyter Notebook.
At least three (3) insights and one (1) visualization should be included.


### Reports for this project

Create a report of 300-600 words called wrangle_report.pdf that briefly describes your wrangling efforts.
It must be an internal document.

Create a written report with over 250 words, called act_report.pdf, that conveys the insights and show the visualization(s) produced by your wrangled data.
It must be an external document.


## Content of the files: 

1. act_report.pdf: the report of the findings;
2. image-predictions.tsv: file
3. tweet_son.txt: json generated
4. twitter-archive-enhanced.csv: file
5. twitter_archive_master1.csv: first master dataframe of the analysis
6. twitter_archive_master2.csv: second master dataframe of the analysis
7. wrangle_act.ipynb: jupyter notebook containing the analysis
8. wrangle_act_organized.pdf: the pdf of the jupyter notebook
9. wrangle_report.pdf: report of the wrangling procedure




## MIT License

Copyright (c) 2019 Vagner Zeizer C. Paes

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.




