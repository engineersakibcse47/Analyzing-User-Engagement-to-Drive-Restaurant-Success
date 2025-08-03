# Analyzing User Engagement to Drive Restaurant Success

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

### 1. Correlation Among User Engagement Types

| Engagement Metric | Reviews | Tips | Check-ins |
|-------------------|---------|------|-----------|
| **Reviews**       | 1.00    | 0.75 | 0.90      |
| **Tips**          | 0.75    | 1.00 | 0.80      |
| **Check-ins**     | 0.90    | 0.80 | 1.00      |

- **Conclusion:**  
  Higher activity in one engagement area tends to align with higher activity in others.

### 2. Engagement by Rating

| Category      | Review Count | Check-in Count | Tip Count |
|---------------|--------------|---------------|-----------|
| **High-Rated**| 63.10        | 80.72         | 8.07      |
| **Low-Rated** | 37.15        | 64.84         | 5.46      |

- **Conclusion:**  
  Higher-rated businesses exhibit more user engagement across all categories.

### 3. Geographic Variation

- **Top Performing Cities:**  
  - Philadelphia
  - Tampa
  - Indianapolis
  - Tucson

- **Insight:**  
  These cities combine high ratings with active user engagement, making them prime locations for restaurant growth.

### 4. Time Trends in User Engagement

- **Pattern:**  
  High-rated restaurants (ratings > 3.5) maintain or increase user engagement over time.
  Noticeable drop in certain metrics during COVID-19 (2020).
- **Engagement:**  
  Engagement is generally higher and more consistent for successful restaurants.

### 5. Engagement vs. Rating

- **Observation:**  
  As a restaurant's rating increases from 1 to 4 stars, so does engagement.
  Restaurants rated at 5 stars may see a drop in engagement, suggesting a saturation or selectivity effect.

### 6. Seasonality

- **Tip & Review Count Trends:**  
  - Peak engagement from November to March.
  - Downward trend observed post-peak.

### 7. Sentiment & Success Metrics

| Metric         | Review | Useful | Funny | Cool | Success Score |
|----------------|--------|--------|-------|------|--------------|
| **Review**     | 1.00   | 0.80   | 0.64  | 0.65 | 0.90         |
| **Useful**     | 0.80   | 1.00   | 0.75  | 0.80 | 0.80         |
| **Funny**      | 0.64   | 0.75   | 1.00  | 0.72 | 0.66         |
| **Cool**       | 0.65   | 0.80   | 0.72  | 1.00 | 0.64         |
| **Success Score** | 0.90 | 0.80 | 0.66 | 0.64 | 1.00          |

- **Conclusion:**  
  Reviews that are rated more useful, funny, or cool positively correlate with business success.

### 8. Elite vs Non-Elite Users

| User Type          | % Users | % Reviews |
|--------------------|---------|-----------|
| **Elite**          | 4.59%   | 55.95%    |
| **Non-Elite**      | 95.41%  | 44.05%    |

- **Observation:**  
  Elite users, though fewer, contribute disproportionately to reviews. Nurturing elite users may promote loyalty and ongoing engagement.

### 9. Busiest Hours

- **Peak Hours:**  
  User engagement is highest from **4 pm to 1 am**, aligning with demand for dining out during evenings and nights.
- **Recommendation:**  
  Optimize staffing and resources during these hours for improved service and customer satisfaction.

## Recommendations

- **Boost Engagement:**  
  Promote all types of user engagement, as increases in one metric support growth in others.
- **Leverage Elite Users:**  
  Build relationships with elite users to enhance reputation and drive referrals.
- **Focus on High-Engagement Cities:**  
  Consider expanding or investing in cities with demonstrated high user engagement and success scores.
- **Seasonal Promotions:**  
  Target peak engagement months (Nov–Mar) with special offers or events.
- **Optimize Peak Hours:**  
  Align operations to capture higher demand during evening hours.
- **Encourage Quality Interactions:**  
  Motivate customers for reviews/tips deemed useful, funny, or cool to foster a positive feedback loop.
- **Support Low-Performing Businesses:**  
  Help less successful restaurants improve engagement and quality by responding to feedback and elevating customer service.

---

**Thank you for reviewing this analysis!**  
Opportunities abound for restaurants on Yelp to elevate their success by understanding and acting on these metrics.
