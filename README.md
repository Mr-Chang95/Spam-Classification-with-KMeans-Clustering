# Spam Message Classification Project with KMeans Clustering

## Introduction

In today's digitally connected world, the influx of messages and emails has given rise to the persistent issue of spam. These unwanted and potentially harmful messages not only disrupt productivity but also pose security risks. To combat this challenge, we embarked on a comprehensive Data Science research project aimed at constructing an intelligent spam classification system. Our mission was to leverage advanced algorithms and machine learning techniques to distinguish between legitimate messages and spam, ultimately providing users with a secure communication experience.

## Objective and Scope

Our project's scope encompassed developing a highly accurate and adaptive predictive model for spam message detection. Leveraging Gaussian Naive Bayes (GNB) and clustering techniques, we approached this multifaceted problem. We collected and meticulously preprocessed diverse message data, employed feature engineering, and selected models capable of adapting to the evolving landscape of digital communication.

## Data Source

Our dataset comprised three folders of non-spam messages and two folders of spam messages, meticulously curated for analysis. We loaded this data into a Pandas DataFrame for further examination.

## Modeling

### Transforming Explanatory Data (Messages)

We employed the TF-IDF vectorization technique to convert textual messages into a numerical format comprehensible to machine learning algorithms. To address varying feature scales, we incorporated the StandardScaler() function into our preprocessing pipeline, ensuring standardized feature values.

### Gaussian Naïve Bayes

We utilized TF-IDF vectors and normalized them with StandardScalar as features for the Gaussian Naive Bayes model, automating spam detection while achieving high classification accuracy.

## Clustering (KMeans)


## Conclusion

Our research project demonstrates the power of machine learning and clustering in addressing the spam problem. We achieved high accuracy in distinguishing spam from legitimate messages, contributing to a more secure digital communication environment.
