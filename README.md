# Data analysis : what qualities make a good cup of coffee? 
<img src="https://s1.qwant.com/thumbr/0x0/b/f/da8d590028a6c3e739e9ec4f5981793621f359d435ee8d3ace9775d2dd1389/cec1033bff7927e2ce0955659af65dda_M.jpg?u=https%3A%2F%2Fwww.businessincameroon.com%2Fmedia%2Fk2%2Fitems%2Fcache%2Fcec1033bff7927e2ce0955659af65dda_M.jpg&q=0&b=1&p=0&a=0" width="3000" height="400">

The aim of this project is to determine what qualities make a good cup of coffee. The analysis is based on data extracted from the Coffee Quality Institute (CQI), an independent entity that supports producers by providing education that gives them options to improve the quality of their coffee. 

## Background Information

Since 1996, ***Coffee Quality Institute (CQI)*** has worked to improve the quality of coffee and the lives of people who produce it. Quality is one of the most important variables that influence a coffee’s value. However, many producers do not have access to the tools and support they need to understand the quality of their coffee, improve that quality, access markets that reward that quality, ultimately enabling them to make more informed business choices.

The database used for the analysis was created by ***scrapping the website of the CQI in January 2018*** and contains a reference for each sample sent for grading and analysis from its foundation. This means that ***each line of the database represents one sample sent by a coffee producer at a given time.*** 

## Data limits
First of all, our analysis is limited to the given dataset and background informations

Our analysis raises some limits:
- Unbalanced representativity in samples given we have more arabica and less robusta (two main types of coffee beans)
- Difficulty in understanding the meaning of some column names (specific to coffee)
- Website suggests minimum grading needs to be 80 to be certified, however analyst suggests there are countries with a mean below the target
- Our analysis can be biased since the grade will depend on individual perception and taste of each expert regarding each coffee sample.

## Dataset used

- Dataset downloaded from Kaggle about coffee quality (https://www.kaggle.com/volpatto/coffee-quality-database-from-cqi)
- Data gathered from the Coffee Quality Institute (CQI) in January 2018
- 3 csv files
- Initially 44 columns, 1339 rows


#### Inside the dataset

- Quality measures such as Flavor, Aroma, Body
- Bean metadata such as processing method, species
- Farm metadata such as country of origin and farm name

- One row = one 2kg sample of green coffee
- One column = one categorical or numeric value
- Interest in mainly quality measures: flavor , aroma, sweetness, body, acicity
- Interesdt also in metadata such as country of origin, harvest year and processing method

## Codebook

A codebook has been created in order to understand some labels of the dataset.

<img width="530" alt="codebook" src="https://user-images.githubusercontent.com/82478538/148704941-e18b0664-6235-4ffa-ad62-e6e5f8d921a0.png">


## Tableau (public)

https://public.tableau.com/views/Coffequality/Harvestyear?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link

## Going further

Merging with other datasets, our analysis could answer other relevant questions:
- Why are less bags sent for analysis year after year?
- Why are sweetness and uniformity (quality measures) not considered as relevant variables for the total cup points?
- Why is 2016 the best year of harvest ? What happened during the other years ? 

### In a larger way...

In order to get a sample graded the coffee producer needs to make a payment to the CQI. 
One of the main questions that arise from this practice is to wonder what are the benefits for a coffee producer to be graded. Is the farmer seeking a quality seal? Or does the farmer maybe need to reach a minimum grading to be eligible to be considered for export? These considerations make us believe that the analysis results need to be considered wisely.


## Trello dashboard

https://trello.com/b/QmLn78vn/coffee-quality-data-analysis


