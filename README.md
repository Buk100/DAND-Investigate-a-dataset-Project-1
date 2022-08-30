# Medical Appointments Exploration
## By Ibukun Irinyenikan

## Dataset
The data consist of over 100,000 records collected from the  
medical appointments records of patients in Brazil. The dataset file is in csv format and 
it is included with the files of this project. 

The dataset was cleaned from both quality and tidyness issues.
Quality issues such as wrong records of patient's age and tidyness issue such as 
missing column of  waiting time were fixed. The data cleaning process are documented in the notebook accompanying this project files in details.

## Summary of Findings

- In the exploration, I found that there is no strong relationship between the age of 
  patients that showed up and those that didn't show up for their appointments. 

- Similarly, patients show up rate does not have a strong correlation with both genders.
  Generally speaking, One gender didn't tend to show up more than the others. 

- However, I found a strong correlation between patients access to medical aids and their show up rate. 
  Patients who do not enjoy free medical aid tend to show up more for their appointment than patients 
  who have access to free medical aid. 

- I also found a strong association between the ailments suffered by patients and their show up rate. 
  The patients suffering from one ailments or the other such as hypertensive, handicapped and diabetic patients 
  showed up more for their appointments more than patients who are not suffering from the ailment.  
  However, an exception are patients who are addicted to alcohol. Patients addicted to alcohol tend not
 to show up than those who are not addicted to alcohol.

- Lastly, I explored how patients suffering from a certain ailments showed up for their appointment, 
  considering whether they received a reminder or not. Generally speaking, I found that reminder increased 
  the rate at which patients showed up for their appointments by 2% rate on average. 
  Not a big significant impact though.





## Key Insights for Presentation

- The female gender showed up 71.6% on average while the male showed up 71.3% on average.
  Patients with no access to medical aid showed up 7% more than patients who have access to free medical aid.

- Patients suffering from diabetes showed up for their appointments 4 percent more than patients who are not diabetic. Similarly,           handicapped patients also showed up for their appointments 3% more than patients who are not handicapped.

- hypertension patients tend to show up than any other patients in the dataset.They showed up for their appointment at 76.53% rate while    alcoholic patients tend to show up the least for their appointments. They showed up at only 66% rate.

-  I also found that sending reminder to patients was able to increase their chances of showing up by two percent. An exception, however are the patients who are handicapped and patients addicted to alcohol where reminder didn't increase their show up rate.

- Lastly, I found out that patients who didn't show up for their appointments waited two days longer than patients that showed up for their appointment. 

## Limitation

- I must mention that even though I found that some patients tend to show up for their appointments when they received a reminder, There  might be other factors that made them show up which I didn't consider in my analysis. Similarly, I could not absolutely conclude that patients showed up or didn't show up because of one ailments or the other.

- I must also mention that I didn't consider patients who had more than one ailment. I didn't analyse all of the variables in the dataset with one another, hence I cannot be absolute in my judgement. It may require some advanced data analytic processes such as inferential statistics or machine learning to come out with absolute judgement.
