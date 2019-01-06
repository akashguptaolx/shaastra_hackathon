# OLX AI Hackathon

## Problem Statement 

OLX is an online classifieds platform where buyers and sellers come together to trade old and new goods. When a seller lists an item to be sold on the platform, he/she writes a title and a description for the listing, lists a price, ads some images of the item. Along with this, we also have data such as the category of the item, place of posting etc. Using these attributes, OLX is challenging you to predict the demand of a listing. The demand is defined in terms of no of unique buyers the listing will get in a month of being posted. We have normalized the demand to be a continuous variable between 0 and 1. 

## Data Dictionary 

| Column | Description  |
| ------------- | ------------- |
| id | Unique identifier for listing  |
| region_id | Region identifier from which the listing was posted  |
| district_id | District identifier from which the listing was posted  |
| city_id | City identifier from which the listing was posted  |
| category_id | Item Category identifier  |
| l1 | Category Name  |
| l2 | Sub Category Name  |
| user_id | Seller identifier  |
| created_at_first | Timestamp when the listing was posted  |
| title | Title of the the listing  |
| description | description of the listing  |
| listing_num_images | Number of images uploaded for the listing  |
| listing_price | Price listed by the seller  |
| demand | target variable  |


## Evaluation Metric 

We will use RMSE (Root Mean Squared Error) to score the submissions. 
[Definition](http://statweb.stanford.edu/~susan/courses/s60/split/node60.html)

## Data 

[Data](http://www.dropbox.com/s/hib7optbsxhq2ny/data.zip?dl=1)

The zip contains 3 files : train.csv, test.csv and sample_submission.csv

You need to use train.csv to train your algorithms and submit the predictions for the ads in test.csv. 

sample_submission.csv is the submission format. 


## Submissions

- Name the solution file in the following format: (teamName)\_(ParticipantFirstName1)\_(ParticipantFirstName2)\_(ParticipantFirstName3).csv

- The submission file should have exactly 2 column headers - id,demand

- The submission file should have exactly 86401 rows (86400 samples and 1 header) 

- Refer to the sample_submission file

- You can submit as many solutions and your best submission will be considered

- Upload your solutions to : [Upload](https://driveuploader.com/upload/J8f35bo6NL/)



