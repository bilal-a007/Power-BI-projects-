# Electricity Disconnection Effectiveness Analysis - FY24


## Problem Statement

To analyze the effectiveness of customer disconnection activities carried out by the ground team as a means to improve the recovery ratio of overdue payments.


### Data Source & Processing 

The data for disconnection efforts was sourced from offline .csv files, extracted from company database. Power Query was used to append and clean the data. Additional tables were linked via relationships, as shown in the provided Entity Relationship Diagram (ERD).

        
## Snap of ERD:

![image](https://github.com/user-attachments/assets/85ea1422-8a67-4d69-b07a-c2ab37f51e41)

## Snap of Dashboard:
![Untitled](https://github.com/user-attachments/assets/de6ae591-5584-4b5f-96fd-b3756e21f28c)



        
# Key Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following key insights are found during analysis:

### 1. Targeting Discrepancy: 
28% of disconnection attempts were made on customers with a high recovery ratio (greater than 85%), indicating a need for further investigation into targeting strategies.

### 2. Ineffective Disconnection Duration: 
The average disconnection duration was only 2 hours, which appears to be too short to effectively prompt customer payment.

### 3 Cluster Imbalance: 
50% of the disconnection efforts were concentrated in one out of nine clusters, suggesting the need for a more balanced approach across all clusters.

### 4 End-of-Month Surge: 
Disconnection attempts showed a gradual increase towards the end of the month. A more evenly distributed schedule throughout the month would improve operational efficiency.

### 5 Nighttime Disconnections: 
A majority of disconnections were performed during the night.

### 6 Quarterly Patterns: 
The highest number of disconnections occurred in Q3 and Q4, highlighting the need to review seasonal trends and plan accordingly.



### Conclusion

The analysis reveals several areas for optimization, including improving targeting strategies, balancing efforts across clusters, and redistributing disconnection schedules throughout the month.
