# Project_HDFS
##### Author: Xingjian (James) Tian
##### Date: Dec. 24, 2024
This is a project created to obtain a recommendation letter from Professor Meena Syamkumar. It is designed to demonstrate my proficiency in Python and my familiarity with the course CS544, using HDFS as an example. The main part of project (**Project_a.ipynb** & **Project_b.ipynb**) is finished on virtual macchine which is to sse google cloud e2-medium, 25GB disk, Ubuntu 22.04 LTS public image, x86/64 version. Btw, I also hope this demonstrates my ability to independently set up and configure a virtual machine environment and effectively work within it😁. Extra Practice is done on local machine since the virtual machine memory is limited. The extra questions are done on my personal computer, which is trying to show my understanding of machine learning and visualization in Python. 

## Overview 
The project first attempts to understand and analyze the data in HDFS, then simulates the scenario where a DataNode is attacked or affected by other uncontrollable factors and becomes unavailable. In the extra question part, I designed two simple questions about the same dataset, which require me to use classification model and visualization packages to solve. 

## Questions 
#### HDFS with two datanodes. 
Q1: Check how many live DataNodes are in the cluster?

Q2: What are the logical and physical sizes of the CSV files?

Q3: What is the file status for single.csv?

Q4: What is the location for the first block of single.csv?

Q5: How are the blocks of single.csv distributed across the two DataNode containers?

Q6: what are the first 10 bytes of single.csv?

Q7: How many lines of single.csv contain the string "Single Family"?

#### After killing one of the datanodes.
Q8: How many live DataNodes are in the cluster?

Q9: How are the blocks of single.csv distributed across the DataNode containers?

Q10: How many times does the text "Single Family" appear in the remaining blocks of single.csv?

#### **Extra Questions** to show my understanding of visualization and machine learning (which can be found in Extra Practice.ipynb): 
Visualization: Based on the dataset (used in HDFS), create a visualization to analyze the relationship between the applicant's income and the loan amount for approved and denied loan applications. Use a scatter plot with different colors to distinguish between approved and denied loans.

Machine Learning: Based on the dataset (used in HDFS), predict whether a loan application will be approved or denied based on the some features using a classification machine learning model.

## Data Source
Since the dataset is too large for github, so I did not include the data inside this repo. The link to download the state_CA.csv (about 361 MB) is listed below
- https://ffiec.cfpb.gov/v2/data-browser-api/view/csv?states=CA&years=2023

## Summary
At the end of this project, I would like to sincerely thank you, Professor Meena, for taking the time and effort to review my work. Completing this project during the busy end-of-semester period, just before Christmas, has been both a challenge and an opportunity to reflect on my growth. While I aimed to produce a comprehensive analysis, there are areas where I couldn’t delve as deeply as I would have liked. For instance, integrating Spark into the HDFS framework would have made the project more aligned with real-world scenarios, but unfortunately, time constraints prevented me from achieving this goal. Nevertheless, I hope this project showcases my understanding of the concepts from CS544, CS320, and CS220, as well as my ability to apply them in practice.

Looking back on my undergraduate experience, I still remember arriving at the University of Wisconsin-Madison with no background in programming, computer science, or software design. At that time, even basic coding felt overwhelming. Through determination, hands-on practice, and the thoughtful guidance of you and other professors, I have developed a strong foundation in programming and problem-solving. Today, I am confident in my ability to independently design and implement projects, even when faced with challenges or unfamiliar concepts. While this project draws inspiration from the coursework we have completed, it also reflects my progress in applying those lessons to a larger, more complex scope.

Once again, thank you for your invaluable support and mentorship throughout my undergraduate journey. Your teaching has not only provided me with essential technical skills but also inspired me to pursue a focus in Data Science and aspire to build a career centered around working with data in the future. I am deeply grateful for all that I have learned under your guidance, and I look forward to continuing to build on this foundation in the years to come.

