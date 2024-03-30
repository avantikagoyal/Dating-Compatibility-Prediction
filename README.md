# Dating Compatibility Final Project

## Overview
Our project delves into the determinants of dating compatibility among individuals in their 20s during the initial stages of acquaintance. Through rigorous analysis, we observed specific attributes that significantly differ between successfully matched pairs and those that were not, suggesting certain characteristics may influence matchmaking outcomes. However, our attempts to predict matches based on these attributes proved challenging, indicating the complex nature of human compatibility.

## Team Members
Avantika Goyal \n
Akhilan Gurumoorthy \n
Derek Ma \n
Weston Yang \n
Yu Huang \n

## Research Question
We aimed to uncover the most critical factors determining compatibility between individuals in their 20s at the outset of their meeting.

## Background and Prior Work
As people enter early adulthood in their 20s, many seek out romantic relationships and hope to find a significant other to journey with them through life. In romantic relationships, compatibility is one of the most essential factors—but what determines compatibility? For two individuals in their 20s, determining compatibility is a complex challenge: factors such as age, shared interests, preference in race, humor, and ambition—to name a few, are all contributors that determine compatibility for two people in a relationship, and the overwhelming amount of factors involved is what makes determining compatibility so complex.

This research project aims to explore some of these factors in determining compatibility by looking at how well different factors predict matches in partners by using a variety of statistical and data analysis techniques on a speed dating dataset. This dataset contains data for age, race, interests, and self-ratings for two people who went on a speed date, as well as information on what both people thought of the date. The overall idea is to see whether or not certain factors about these potential pairings can correlate or predict whether the pair ended up in a match or not.

In a 2019 Pew Research Center survey of American adults, responses show that differences in religion, race, ethnicity, and income are generally not major dealbreakers in dating and relationships. In fact, 77%+ responders said they were open to dating (or have already dated) someone who differs from them on these characteristics [1]. 

In another study conducted by Columbia professors Ray Fisman and Sheena Iyengar, results indicated differences between the genders regarding what they prioritize when dating. They found that “women put greater weight on the intelligence and the race of partner, while men respond more to physical attractiveness. Moreover, men do not value women’s intelligence or ambition when it exceeds their own” [2]. This seems somewhat consistent with traditional gender stereotypes and suggests that when we carry out our project, we should segment the data by gender to achieve more meaningful results. 

[1]: Amanda Borroso. (2020, August 21). Key takeaways on Americans’ views of and experiences with dating and relationships. Pew Research Center. https://www.pewresearch.org/fact-tank/2020/08/20/key-takeaways-on-americans-views-of-and-experiences-with-dating-and-relationships/

[2]: Fisman, R., Iyengar, S. S., Kamenica, E., & Simonson, I. (2006). Gender differences in mate selection: Evidence from a speed dating experiment. The Quarterly Journal of Economics, 121(2), 673-697. https://doi.org/10.1162/qjec.2006.121.2.673

## Hypothesis
We hypothesize that 'attractiveness' and 'shared interests' are primary contributors to a match after a brief speed dating interaction, given their significance in forming first impressions.

## Data
The "Speed Dating" dataset from Kaggle, consisting of over 8,378 observations, served as our analysis foundation. It included participants' ratings across various attributes post-speed dating events, offering a rich basis for exploring compatibility determinants.

## Methodology
Our approach encompassed data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling. We focused on attributes like age distribution, gender, work fields, race, and individual characteristics (e.g., attractiveness, sincerity) to explore their impact on match outcomes. Statistical tests and machine learning models, including Logistic Regression, Decision Trees, and Random Forest, were employed to gauge the predictability of matches.

## Key Insights
Certain attributes significantly differed between matched and unmatched pairs, yet predicting matches based on these characteristics proved complex.
Gender, age preferences, race, and field of work showed varied influences on dating preferences and compatibility.
The complexity of human compatibility underscores the challenge of using isolated factors to predict matchmaking outcomes accurately.

Our most effective model was a Random Forest Classifier in which we achieved an accuracy score of 0.7668. We employed GridSearchCV to determine the optimal hyperparameters for this model.

## Technologies Used
Python for data manipulation and analysis, leveraging libraries such as Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn.
Logistic Regression, Decision Trees, and Random Forest models for predictive analysis.
Jupyter Notebook for interactive documentation of our analysis process.

## How to Use
Clone this repository for a comprehensive analysis overview.
Ensure you have the necessary Python environment and libraries installed.
Explore the Jupyter Notebook for detailed insights into our methodology and findings.

## Contributions
We welcome further exploration and contributions to refine our models or expand upon our findings. Feel free to fork this repository and submit your enhancements for review.

## Acknowledgements
We extend our gratitude to Columbia University and Kaggle contributor, Ulrik Thyge Pedersen, for collecting and providing the dataset that made this project possible. Special thanks also go to our professor and peers for their invaluable support and feedback throughout this endeavor.

