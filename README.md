Download Link: https://assignmentchef.com/product/solved-mie1624-assignment1-eda-and-hypothesis-testing
<br>
For this assignment, you are responsible for answering the below questions based on the dataset provided. You will then need to submit a 2-page report in which you present the results of your analysis. In your report, you should use visual forms to present your results. How you decide to present your results (i.e. with tables/plots/etc.) is up to you but your choice should make the results of your analysis clear and obvious. In your report, you will need to explain what you have used to arrive at the answer to the research question and why it was appropriate for the data/question. You must interpret your final results in the context of the dataset for your problem.

<strong><u>Dataset:</u></strong>

Kaggle has hosted an open data scientist competition in 2020 titled “<strong>Kaggle ML &amp; DS Survey Challenge.</strong>” The purpose of this challenge was to “<em>tell a data story about a subset of the data science community represented in this survey, through a combination of both narrative text and data exploration.</em>” More information on the competition, data, and prizes can be found on: <a href="https://www.kaggle.com/c/kaggle-survey-2019/data">https://www.kaggle.com/c/kaggle-survey-2020/data</a>

The dataset provided (<strong>kaggle_survey_2020_responses.csv</strong>) contains the survey results provided by Kaggle<em>. </em>The survey results from 20036 participants are shown in 355 columns, representing survey questions. Not all questions are answered by each participant, and responses contain various data types.

In the dataset for Assignment 1, column Q24 “<em>What is your current yearly compensation (approximate $USD)?” </em>contains a numerical target variable. Rows with null salaries have been dropped. (Please refer to clean_kaggle_data.csv). <strong>You should work with the clean dataset for this assignment.</strong>

<strong><u>Questions:</u></strong>

The objectives of this Assignment is to explore the survey data to understand <strong>(1) </strong>the nature of women’s representation in Data Science and Machine Learning and <strong>(2) </strong>the effects of education on income level. The following tasks should be completed:

<ol>

 <li><strong> </strong>Perform exploratory data analysis to analyze the survey dataset and to summarize its main characteristics. Present 3 graphical figures that represent different trends in the data. For your explanatory data analysis, you can consider Country, Age, Education, Professional Experience, and Salary.</li>

 <li><strong> </strong>Estimating the difference between average salary (Q24) of men vs. women (Q2).

  <ol>

   <li><strong> </strong>Compute and report descriptive statistics for each group (remove missing data, if necessary).</li>

   <li><strong> </strong>If suitable, perform a two-sample t-test with a 0.05 threshold. Explain your rationale.</li>

   <li><strong> </strong>Bootstrap your data for comparing the mean of salary (Q24) for the two groups. Note that the number of instances you sample from each group should be relative to its size. Use 1000 replications. Plot two bootstrapped distributions (for men and women) and the distribution of the difference in means.</li>

   <li>If suitable, perform a two-sample t-test with a 0.05 threshold on the bootstrapped data. Explain your rationale.</li>

   <li>Comment on your findings.</li>

  </ol></li>

 <li>Select “highest level of formal education” (Q4) from the dataset and repeat steps <strong>a </strong>to <strong>e</strong>, this time use analysis of variance (ANOVA) instead of t-test for hypothesis testing to compare the means of salary for three groups (Bachelor’s degree, Doctoral degree, and Master’s degree) [<strong>75pts </strong>for <strong>a; 0.5 pts </strong>for <strong>b; 2pts </strong>for <strong>c; 0.75 pts </strong>for <strong>d; 1pt </strong>for <strong>e</strong>].</li>

</ol>