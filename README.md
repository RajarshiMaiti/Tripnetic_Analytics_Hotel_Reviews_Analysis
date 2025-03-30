Sentimental-Analysis-with-NLP

Table of Contents:

1. Introduction

2. Data

3. Understanding the variables

4. Data Cleaning and Preprocessing

5. Identify potential personally identifiable information (PII)

6. Perform Bag of Words, TF-IDF, and Word Embeddings

7. Use a Confusion Matrix to Evaluate Model Performance

8. Choose the best Model

9. Most influential dimensions in the decision-making of the model

10. Exploratory Data Analysis (EDA)

11. Hyperparameter Tuning with Word Embeddings

12. Conclusions

1. Introduction

A data analysis subsidiary specializing in data analytics is currently addressing a critical challenge within a conglomerate that operates diverse platforms such as websites, mobile applications, and portals for reservations and customer feedback. The challenge at hand involves a significant decline in room sales.

To tackle this issue analytically, the data analytics team has been assigned the task of constructing an ETL (Extract, Transform, Load) pipeline. This process involves extracting data from various sources and transforming it into a format suitable for machine learning analysis.

This analytical approach aims to enhance the effectiveness of customer feedback analysis, allowing for the identification of patterns, trends, and sentiments potentially linked to the decrease in sales. The primary objective is to utilize this data to comprehend the underlying causes of the problem and, ultimately, develop evidence-based solutions to reverse the negative sales trend.

2. Data

The dataset contains two columns:

Review: Textual data of customer reviews. This column has 20,491 unique entries, which suggests that each row contains a unique review text.
Rating: Numerical ratings associated with the reviews. The ratings range from 1 to 5.
