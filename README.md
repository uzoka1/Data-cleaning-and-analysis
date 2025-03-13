## Mini Project: Data Cleaning and Analysis Task

### Data Cleaning and Insights Report
 This report lays out the process  used to clean up the dataset give and points out the main things i learned from the cleaned up data. The dataset had sales records for different fantasy and comic book products. 

 ### Data Sources

 Sales data: The dataset used for this analysis is "ways_to_clean_dataa. .xlsx" file, containing details of comic book sales per region

 ### Tools Used

 Excel - Data cleaning and calcuations 

 ### Data Cleaning Steps and preparation

 1. I got rid of rows with bad data
  - I took out rows that had "inf" in the Price Per Unit column, since they were bad data
  - I removed duplicate IDs to stop wrong analysis. 
 2. I worked out the total value
 - I figured out the total value for each sale by multiplying the Quantity by the Price Per Unit.

   ### Exploratory Data Analysis

- A cleaned dataset with duplicate IDs removed and infinite values handled.
- A summary table showing total quantity and total value per region.
- A short report explaining your steps and insights from the cleaned data.

  ### Data Analysis
  - I used the remove duplicate function on the dataset to remove the duplicates
  - To get rid of "inf" in the dataset, i used the find function then remove the cells higlighted
  - I used the "=PRODUCT(G2, H2)" function to  find the total value
  - To get the total quantity per region i used "=SUMIF(D:D,K9,G:G)"
  - To get the total value per region i used "=SUMIF(D1:D23,K20,I1:I22)"
    
### Results and Finds
- The South area made the most money bringing in $8,049.9.
- On average, each sale across all deals was worth about $1,199.99.

To wrap up
The data cleaned up gave me some great insights into how well different areas and products are selling. The South came out on top as the best-performing region, and with the wide variety of products being sold. These findings can help shape business choices and plans to grow in the future.



