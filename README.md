# User Engagement Drives Restaurant Success

## About Yelp

**Yelp** is a web and mobile platform that functions as a crowd-sourced local business review site. Users can submit reviews, photos, and tips about businesses, while also browsing information and ratings left by others.

## Agenda

- Problem Statement
- Research Objectives
- Hypotheses
- Data Overview
- Analysis and Findings
- Recommendations

## Problem Statement

In a competitive market like the restaurant industry, understanding the factors that influence business success is crucial for stakeholders. Utilizing the Yelp dataset, this project investigates the relationship between user engagement (reviews, tips, and check-ins) and business success metrics (review count, ratings) for restaurants.

## Research Objectives

- **Quantify Correlation:**  
  Analyze the correlation between user engagement (reviews, tips, check-ins) and review count/average star rating.
- **Explore Time Trends:**  
  Examine temporal patterns in user engagement.
- **Compare Engagement:**  
  Identify differences between high-rated and low-rated businesses.
- **Geographic Variation:**  
  Assess how restaurant success metrics vary across states and cities.
- **Sentiment Analysis:**  
  Explore correlations between review sentiment (useful, funny, cool) and success metrics.
- **Elite User Impact:**  
  Compare engagement of elite users with non-elite users.

## Hypotheses

1. Higher user engagement is positively correlated across reviews, tips, and check-ins.
2. High-rated restaurants show greater engagement.
3. Restaurant success varies by location.
4. User engagement is consistent or increasing over time for successful businesses.
5. Higher engagement generally corresponds to higher ratings.
6. Reviews deemed useful, funny, or cool are indicators of greater business success.
7. Elite users contribute disproportionately to engagement metrics.
8. Busiest hours for engagement are in the evening/night.

## Data Overview

- User Engagement: Reviews, Tips, Check-ins
- Business Metrics: Review Count, Ratings
- Sentiment: Useful, Funny, Cool Votes
- User Type: Elite vs. Non-Elite
- Temporal and Geographic Data

## Analysis & Findings

<p align="center">
  <img src="https://github.com/user-attachments/assets/0bdf5024-ffbf-46be-9d25-8276eae83dba" alt="image" width="306" height="281" />
</p>

- Table showing distribution of business success metrics (review count and average rating)
- Out of 150k businesses, 35k are restaurant businesses and are open.

<p align="center">
  <img src="https://github.com/user-attachments/assets/1bb418e6-e022-497a-b2e5-eef7be3619bd" alt="image" width="842" height="359" />
</p>

- Higher ratings do not guarantee a higher review count, or vice versa.
- Ratings or review counts do not solely determine the success of Restaurants.
- Review count reflects user engagement but not necessarily overall customer satisfaction or business performance.

### Do restaurants with higher engagement tend to have higher ratings?

<p align="center">
  <img src="https://github.com/user-attachments/assets/86feec8d-f8f8-4ba7-b864-0a2123fe2a00" alt="image" width="883" height="310" />
</p>

- Data shows a general increase in average review, check-in, and tip counts as ratings improve from 1 to 4 stars.
- Restaurants rated 4 stars exhibit the highest engagement and shows a downward trend for rating above 4.
- The drop in engagement at 5.0 stars might suggest either a saturation point where fewer customers feel compelled to add their reviews, or a selectivity where only a small, satisfied audience frequents these establishments.

### Is there a correlation between the number of reviews, tips, and check-ins for a business?

<p align="center">
  <img src="https://github.com/user-attachments/assets/667fad63-c3df-4aff-8923-8eb8fc7ae3ef" alt="image" width="612" height="481" />
</p>

- These correlations suggest that user engagement across different platforms (reviews, tips, and check-ins) is interlinked; higher activity in one area tends to be associated with higher activity in others.
- Businesses should focus on strategies that boost all types of user engagement, as increases in one type of engagement are likely to drive increases in others, enhancing overall visibility and interaction with customers.

### Is there a difference in the user engagement between high-rated and low-rated businesses?

<p align="center">
  <img src="https://github.com/user-attachments/assets/8f0712fd-cf34-4786-80ee-ec6593f7485c" alt="image" width="666" height="204" />
</p>

- Data indicates a clear correlation between higher ratings and increased user engagement across reviews, tips, and check-ins.
- This pattern underscores the importance of maintaining high service and quality standards, as these appear to drive more reviews, check-ins, and tips, which are critical metrics of customer engagement and satisfaction.

### How do the success metrics of restaurants vary across different states and cities?

<p align="center">
  <img src="https://github.com/user-attachments/assets/a1d999ef-4b5c-40a5-a2b5-80913414074f" alt="image" width="770" height="476" />
</p>

- Philadelphia emerges as the top city with the highest success score, indicating a combination of high ratings and active user engagement.
- Following Philadelphia, Tampa, Indianapolis, and Tucson rank among the top cities with significant success scores, suggesting thriving restaurant scenes in these areas.

### Are there any patterns in user engagement over time for successful businesses compared to less successful ones?

<p align="center">
  <img src="https://github.com/user-attachments/assets/a66b6d64-9b67-4f5b-99b2-4d28bfa88edc" alt="image" width="892" height="475" />
</p>

- Successful businesses, particularly those with higher ratings (above 3.5), exhibit consistent and possibly increasing user engagement over time.
- High-rated restaurants maintain a steady or growing level of user engagement over time, reflecting ongoing customer interest and satisfaction.

## Trend and Seasonality Analysis

<p align="center">
  <img src="https://github.com/user-attachments/assets/f7a9451c-5bf4-4401-8d1a-78c2c9e8bafc" alt="image" width="1400" height="596" />
</p>

### How does the sentiment of reviews and tips (useful, funny, cool) correlate with the success metrics of restaurants?

<p align="center">
  <img src="https://github.com/user-attachments/assets/212f3c1f-db58-4989-b17e-7333606cdc15" alt="image" width="677" height="567" />
</p>

- “useful", "funny", and "cool" are attributes associated with user reviews. They represent the feedback provided by users about the usefulness, humor, or coolness of a particular review.
- Higher counts of useful, funny, and cool reviews suggest greater user engagement and satisfaction, which are key factors contributing to a restaurant's success.

### Is there any difference in engagement of elite users and non-elite users?

<p align="center">
  <img src="https://github.com/user-attachments/assets/f909202c-69c5-4818-806a-da30e8d21646" alt="image" width="792" height="334" />
</p>

- Elite users are individuals who have been recognized and awarded the "Elite" status by Yelp for their active and high-quality contributions.
- Elite users, despite being significantly fewer in number, contribute a substantial proportion of the total review count compared to non-elite users.
- Establishing a positive relationship with elite users can lead to repeat visits and loyalty, as they are more likely to continue supporting businesses they have had good experiences with.

### Busiest Hours

<p align="center">
  <img src="https://github.com/user-attachments/assets/b28b83c5-faa0-4b39-8d01-0c23682d1cfe" alt="image" width="816" height="488" />
</p>

- The busiest hours for restaurants, based on user engagement, span from 4 pm to 1 am.
- Knowing the peak hours allows businesses to optimize their staffing levels and resource allocation during these times to ensure efficient operations and quality service delivery.
- The concentration of user engagement during the evening and night hours suggests a higher demand for dining out during these times, potentially driven by factors such as work schedules, social gatherings, and leisure activities.

## Recommendations

- Utilizing insights from the analysis of various metrics such as user engagement, sentiment of reviews, peak hours, and the impact of elite users, businesses can make informed decisions to drive success.
- Collaborating with elite users and leveraging their influence can amplify promotional efforts, increase brand awareness, and drive customer acquisition.
- Businesses can adjust their operating hours or introduce special promotions to capitalize on the increased demand during peak hours.
- Less successful businesses may need to focus on strategies to enhance user engagement over time, such as improving service quality and responding to customer feedback.
- Cities with high success scores present opportunities for restaurant chains to expand or invest further.

---

