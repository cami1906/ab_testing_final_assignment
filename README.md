# AB Testing Final Assignment
This is a series of queries that answer the questions from the final assignment of the course 'Data Wrangling, Analysis and AB Testing with SQL', in Cousera. 
Note: If you are here to review my work from the UC Davis University course, I would like to ask you a favour: please run the queries in Mode, and you will find the answers. 
I created this report becasue I could no figure out how to let people access the link I submitted in my report.

## Project Purpose 
We are running an experiment at an item-level, which means all users who visit will see the same page, but the layout of different item pages may differ. 
  
## 1. Data Quality Check
- **Question**: Compare this table to the assignment events we captured for user_level_testing. Does this table have everything you need to compute metrics like 30-day view-binary?
- **Answer**: No, because the provided table return only whether each test has received treatment or not. It is not possible to compute the metrics we need without knowing when was the start date for each test event. To sum up, there is missing data and the data available is not properly formatted.
- **Date**: 29/03/2024

```sql
SELECT 
  * 
FROM 
  dsv1069.final_assignments_qa
```

## 2. Reformat the Data
- **Question**:
- **Answer**:

## 3. Compute Order Binary
- **Question**:
- **Answer**:

## 4. Compute View Item Metrics
- **Question**:
- **Answer**:

## 5. Compute lift and p-value
