# K-means for Evolving Datastream

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)

## Authors
- Aniket Sethi - 190001003
- Yash Suvarna - 190001068
- Garvit Galgat - 190001016
## Introduction
The analysis of streaming data has gained significant importance in recent years, posing unique challenges for clustering techniques due to the dynamic and evolving nature of data streams. Our project focuses on addressing the challenges posed by evolving data streams through the development of a K-means algorithm specifically tailored for handling concept drift in streaming data.

## Objective
Our main objective is to create an efficient K-means algorithm capable of clustering evolving data streams while adapting to changes in the data distribution.

## Features
- Evolving Data Handling: Our algorithm is designed to handle evolving data streams where data points arrive sequentially and the underlying distribution may change over time.

- Adaptive Clustering: The algorithm adapts to changes in the data distribution by incorporating a restart mechanism whenever a concept drift is detected, ensuring accurate clustering over time.

- Approximation Technique: We employ an approximation approach using a surrogate error function that captures the relevant information for clustering quality without explicit concept drift detection.
