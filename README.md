# A-B-Testing-Result-Analysis---New-product-release

A/B testing is the process of comparing 2 versions of the same asset, and evaluating the difference in performance. It is used everywhere from thumbnails in Netflix, to new product releases on Amazon, to display of search results on Google. But once the results are obtained it becomes equally important to understand if the difference in results are statistically significant or was it a random occurences that took place because of particular samples being selected by chance. In this project we will compare 3 such promotions carried across different of varying sizes across locations and understand if 1 promotional campaign is better than the other, and help the firm decide on a marketing strategy for it's newly released product.<br><br>

<b>The project is divided in 2 main parts -</b><br>
1. Data Ingestion, Exploratory Data Analysis & Data Visualization
2. Implementing statistical tests to evaluate the merit of promotional campaigns against each other
<br><br>

<b>Data Ingestion, Exploratory Data Analysis & Data Visualization -</b><br>
The data was ingested using an xlsx file.<br>
Based on initial exploration we collect the following information -<br>
a. The promotions were run across 137 distinct locations<br>
b. These campaigns were run across both old and new stores<br>
c. The largest sales recorded was due to Promotional campaign 3, followed by promotional campaign 1, followed by promotional campaign 2.<br>
d. All 3 market sizes namely - large, medium and small participated in these campaigns<br>
e. Predominantly medium market sizes were used to run all the 3 campaigns<br>
f. Also there seems to be a preference for newer store as compared to older stores<br>

Also based on the exporatory analysis and data visualizations performed above we can sucessfully conclude that the campaigns were run across markets of similar attributes, which is a pre-requisite of AB Testing.<br><br>

<b>Implementing statistical tests to evaluate the merit of promotional campaigns against each other</b><br>
We start by computing the averages for individual promotional campaigns. Based on the initial glance, on an average promotional campaign 1 is performing better than the rest. But this could really be due to the randomness of the sample. To ensure this isn't the case we go on to perform statistical tests to verify if our results are statistically significant. The statistical test of our choice is 2 sample t-test.<br>
We start by comparing promotional campaign 1 and 2. Based on the results of the 1st t-test we derived that campaign 1 was statistically significantly performing better as compared to campaign 2 at 95% confidence level. Now that we know campaign is better than campaign 2, we move on to compare campaign 1 and 3. Based on the second t-test we could not find conclusive evidence. To further analyze which campaign is better we would need to perform additional experimentation and would require additonal data. Summing up everything we can say that campaign 1 and campaign 3 outperform campaign 2, but we do not have a clear winner between campaign 1 and campaign 3. 

