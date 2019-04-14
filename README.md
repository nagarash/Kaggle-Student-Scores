# Kaggle-Student-Scores
Understanding impact of socio-economic factors on student exam scores
## Dataset
The dataset consists of math, reading and writing scores of students along with some influencing factors such as gender, race, parents education, lunch type, and if the student took test preparation courses.

## Goals
### Inference
Identify interesting correlations within the dataset.
The lunch column is an interesting factor I didnt expect in such a dataset. I want to explore its impact on the scores?
### Prediction
Try different models in predicting scores based on the input factors.

## Key Takeaways
Whether the student gets the standard lunch or free/reduced lunch has an impact on the scores. It is evident students from lower income families on an average have 5-10 points lower scores than those who can afford standard lunches.
Test preparation provides a stastically signficant improvent in test scores. However, the difference in means are consistently higher for students with 'free/reduced' lunch type. This indicates test preparation has an outsized impact on scores for students from low income families (6 points increase for math and more than 11 points increase for writing).
Predictive models suggest the most important variables driving higher scores are
lunch = 'standard'
test preparation course = 'completed'
parental education level = 'bachelors/masters degree'
race/ethnic_group = 'E'
