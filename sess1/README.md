Online Session 1 - Coding Exercise
From the readings of this lesson, there are complementary codes given in github, please only submit the two that are given below. Make sure you focus on the portion of the code for text pre-processing and data exploration; especially on topics such as exploring the data (including imbalanced classes), cleaning the text via simple regular expressions and advanced NLP, and exploring data properties, summaries, frequencies, visualizations, and complexities. It is alright if you do not understand all the steps in the machine learning life cycle right now, we will go over them in detail the up-coming weeks in this course. You will get practical hands-on experience by writing your own code.

After completing the programming code components, think about which methodologies you would employ in your project and how you would use them.

(The following links will open in new window)

Modern Text Mining with Python, Part 1 of 5: Introduction, cleaning and linguistics. datanizing GmbH March 24 [7 minutes]

Modern Text Mining with Python, Part 2 of 5: Data Exploration with Pandas. datanizing GmbH March 24 [11 minutes]

Some Tips and Hints: 
1. Some of the simple skills you will learn will be how to execute jupyter notebooks and install different libraries and modules. If you are using MAC and have have Anaconda, a better way to install packages is to do it from the Anaconda environments UI. The order of installing packages is important so that they may not override other packages. You may have developed a checklist to try to get the code to begin working again. Next, please use virtual environments for each individual code exercise to organize the Python packages and their versions. You may look for tutorials online.

2. Another challenge you will face is dataset size and computational power. The dataset is too big on your machine to iterate over all the rows. You may reduce the dataset size to 50,000 rows by randomly selecting the dataset and balancing the classes. You may also run the code on the Google research collab environment so that you can see the results. The google environment provides an alternate environment for running commands against very large datasets. Although, this approach took a while to upload large datasets to the cloud environment. The last solution is to try GPU and parallel processing.

3. For "Multi-Class Text Classification with Scikit-Learn. Susan Li Feb 19, 2018 · 11 min read:-" The data file from :- https://catalog.data.gov/dataset/consumer-complaint-database is very big.

Int64Index: 463991 entries, 3 to 1437711

It takes a lot of time to compute. In order to decrease the processing time, change the starting lines to:-

```python
import pandas as pd
df = pd.read_csv('Consumer_Complaints.csv')
df = df[:50000]
df.head() 
```

Will change the data to :-

Int64Index: 15799 entries, 3 to 49999