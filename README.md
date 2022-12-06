# Module 22 Challenge - Big Data Homework - "Alexa, can you handle big data?"

### Level 1 - DataFrame size query answers
- part_one_aws_tools      = 1,741,100 rows
- part_one_aws_watches    =   960,872 rows

&nbsp;

### Level - 2 (watch review data only)
&emsp;

**Summary statistics for all Reviews:**

|summary|       star_rating|     helpful_votes|      total_votes|
|-------|------------------|------------------|-----------------|
|  count|            960679|            960679|           960679|
|   mean|           4.13824|           1.19591|          1.56012|
| stddev|           1.29328|            8.1602|          9.06782|
|    min|                 1|                 0|                0|
|    max|                 5|              4004|             4249|
&emsp;


**Summary statistics for vine customers:**

|summary|       star_rating|     helpful_votes|      total_votes|
|-------|------------------|------------------|-----------------|
|  count|              1747|              1747|             1747|
|   mean|            4.0343|           2.85804|          3.71207|
| stddev|           0.93669|          11.03931|         12.01083|
|    min|                 1|                 0|                0|
|    max|                 5|               349|              370|
&emsp;

**Summary statistics for not-vine customers:**

|summary|       star_rating|     helpful_votes|      total_votes|
|-------|------------------|------------------|-----------------|
|  count|            958932|            958932|           958932|
|   mean|            4.1384|           1.19288|          1.55620|
| stddev|           1.29384|           8.15376|          9.06113|
|    min|                 1|                 0|                0|
|    max|                 5|              4004|             4249|
&emsp;

**Summary 5 Star Rating Only**

|                          | paid (Members)   | un-paid    | all-in|
|--------------------------|------------------|------------|--------|
|                vote count|               605|     570,888| 571,493|
|          total vote count|             1,747|     958,932| 960,679|
|                Percentage|             34.6%|       59.5%|   59.4%|
&emsp;


### Conclusions:

In the case of reviews for watches it can be seen that paid members are not showing a bias to giving 5 star ratings.  In fact they are harsher, with only 34% of reviewers giving 5 star in comparison to 59.5% by un-paid reviews. It should also be notes that the number of vine reviewers is less than 1 % of the total reviews so it could be argued that thi sample size is too small to draw a definative conclusion. 
