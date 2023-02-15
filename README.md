# Glassdoor-Dashboard
A dynamic power bi dashboard visualizing dataset contains job postings from Glassdoor.com.

***The project consists of a Power BI Dashboard***

**The Glassdoor Dashboard** : Glassdoor Dashboard.pbix is the Dashboard containing exploratory data analysis and contains the insights which I was able to glean from the dataset.



https://user-images.githubusercontent.com/73903183/219144403-6cb3d357-3050-4d48-85d2-de39f6d3ffda.mp4


## About Glassdoor

![glass](https://upload.wikimedia.org/wikipedia/commons/e/e1/Glassdoor_logo.svg)

Glassdoor is a website where current and former employees anonymously review companies. Glassdoor also allows users to anonymously submit and view salaries as well as search and apply for jobs on its platform.Glassdoor launched its site in 2008 , as a site that “collects company reviews and real salaries from employees of large companies and displays them anonymously for all members to see,” according to TechCrunch. The company then averaged the reported salaries, posting these averages alongside the reviews employees made of the management and culture of the companies they worked for—including some of the larger tech companies like Google and Yahoo. The site also allows the posting of office photographs and other company-relevant media.


## Dataset Description:

I have been using a web scraped Dataset, which is available at Kaggle: https://www.kaggle.com/datasets/thedevastator/jobs-dataset-from-glassdoor.

This dataset contains job postings from Glassdoor.com from 2017-2018. It includes features such as job title, salary estimate, job description, rating, company name, location, headquarters, size, founded, type of ownership, industry, sector, revenue, competitors compile a list of the most important features in this dataset. 

```
job_id: The unique identifier for the job posting (Numeric)
job_state: The state where the job is located (String)
same_state: A binary indicator of whether the job is in the same state as the person looking at the job (String)
age: The age of the person looking at the job (Numeric)
python_yn: A binary indicator of whether the person looking at the job knows Python (String)
R_yn: A binary indicator of whether the person looking at the job knows R (String)
spark: A binary indicator of whether the person looking at the job knows Spark (String)
aws: A binary indicator of whether the person looking at the job knows AWS (String)
excel: A binary indicator of whether the person looking at the job knows Excel (String)
job_simp: A simplified job title (String)
seniority: The seniority of the job (String)
desc_len: The length of the job description (Numeric)
num_comp: The number of competitors for the job (Numeric)
```

## Stage 1 : Data Transforming 
In this step I was converting, cleansing, and structuring data into a usable format that can be analyzed. You can find more details in the documentation word file.

## Stage 2 : Data Visualization  
Once I explored the data, I start thinking about the data story and immediately put it into practice by creating different charts to visualize the data and get insights.

## The challenges I went through:

Hence the data is web scraped so it is containing many non-reliable data like outliers and wild characters, moreover its poorly structured so went through a process of cleaning and transforming the data in a better way. One of main challenges where that most of the data is in a text format and I rarely  worked on such a one  so it was hard to get insights and build a story. 

