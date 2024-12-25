# Project_HDFS
##### Author: Xingjian (James) Tian
##### Date: Dec. 24, 2024
This is a project created to obtain a recommendation letter from Professor Meena Syamkumar. It is designed to demonstrate my proficiency in Python and my familiarity with the course CS544, using HDFS as an example. The main part of project is finished on virtual macchine (Use google cloud e2-medium, 25GB disk, Ubuntu 22.04 LTS public image, x86/64 version). Extra Practice is done on local machine since the virtual machine memory is limited. 

## Overview 
The project first attempts to understand and analyze the data in HDFS, then simulates the scenario where a DataNode is attacked or affected by other uncontrollable factors and becomes unavailable.

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

## Data Source
- https://ffiec.cfpb.gov/v2/data-browser-api/view/csv?states=CA&years=2023 
