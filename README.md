# Yelp Data Analysis: Trends, Insights, and Predictions

This project leverages the extensive Yelp dataset—which includes over 6 million reviews across more than 150,000 businesses—to extract valuable insights from both text reviews and numerical business metrics. By utilizing Apache Spark for data processing and applying machine learning techniques, the analysis uncovers trends in consumer behavior, business performance, and market dynamics.

---

## Problem Definition
The project aims to:
- **Analyze Text & Numerical Data:** Examine user reviews alongside key business metrics to understand correlations between consumer sentiment and business performance.
- **Leverage Spark for Efficiency:** Use Spark to manage, clean, and process the large dataset, enabling effective exploratory data analysis (EDA) and preliminary machine learning.
- **Extract Actionable Insights:** Reveal trends in customer engagement, regional variations, and competitive market dynamics that can inform marketing strategies and operational improvements.

---

## Data Source & Description
The dataset is obtained from the official Yelp website and comprises five tables:
- **business.json:** Contains business details such as address, categories, star ratings, review counts, and more.
- **review.json:** Holds user reviews including text, ratings, and associated metadata.
- **user.json:** Provides user-specific information like average star ratings, compliment counts, review history, and join date.
- **tips.json:** Consists of brief tips provided by users regarding various businesses.
- **checkin.json:** Records check-in data with timestamps of customer visits.

The entire dataset totals approximately 10GB, offering a rich basis for analyzing consumer trends and business performance.

---

## Introduction & Motivation
Driven by a desire to deeply understand consumer preferences and the operational efficiency of businesses, this project:
- **Uncovers Consumer Trends:** Identifies patterns in review sentiment, compliment counts, and overall customer engagement.
- **Informs Business Strategy:** Helps businesses tailor their services and marketing efforts based on insights derived from regional and category-specific trends.
- **Embraces Predictive Analytics:** Incorporates preliminary machine learning models to predict market trends, enabling businesses to proactively adapt in competitive environments.

---

## Executive Summary
- **Data Handling & Processing:**  
  Apache Spark is employed to efficiently manage and process the large dataset, ensuring robust data cleaning and exploratory analysis.
  
- **Key Insights:**
  - **Regional Engagement:**  
    States such as Pennsylvania and Florida exhibit significant user engagement, with over a million reviews each, indicating high customer participation.
  - **City-Level Excellence:**  
    Complementary review counts highlight that cities like Philadelphia and New Orleans offer exceptional dining experiences.
  - **Market Competitiveness:**  
    Businesses in competitive markets tend to achieve higher customer satisfaction and better ratings.
  - **Temporal Trends:**  
    Review activity peaked in 2019 and declined during the pandemic years (2020-2021), reflecting the impact of COVID-19.
  - **Category-Specific Variations:**  
    While the restaurant sector dominates in terms of review volume, niche categories (e.g., Mohels, Patent Law) stand out with the highest ratings.
  - **Business Presence:**  
    Major chains such as CVS Pharmacy and Walgreens are noted for their extensive market coverage.

---

## Challenges
- **Data Limitations:**  
  The anonymized and subsetted nature of the dataset leads to an underrepresentation of some prominent chains (e.g., McDonald’s), impacting the analysis of market distribution.
- **Computational Constraints:**  
  Memory-intensive tasks, such as running Word2Vec for cluster analysis, necessitated data sampling, which may limit the full efficacy of the approach.
- **Methodological Hurdles:**  
  Techniques like PCA for dimensionality reduction might result in significant information loss. Alternative methods like TSNE could be more effective but are not readily available in PySpark.

---

## Conclusion
The analysis reveals robust engagement within the Yelp ecosystem, particularly in regions like Pennsylvania and Florida. Strong consumer participation, highlighted by high review and compliment counts, underscores the importance of customer satisfaction in driving business success. Additionally, the findings emphasize that competitive markets and effective categorization of business services can lead to improved customer experiences. These insights provide a valuable foundation for business owners aiming to refine their strategies and enhance overall market performance.

---

## References
- **Dataset Source:** Official Yelp dataset (link provided within project documentation)
- **Tools & Techniques:** Apache Spark, Word2Vec, and various machine learning methods
- **Additional Notes:** ChatGPT was used to refine the language and ensure clarity in the project narrative

---

## Collaborators
- Dylan Kakkanad
- Jonathan Blanco
- Neeharika Kamireddy
- Yahui Wen
