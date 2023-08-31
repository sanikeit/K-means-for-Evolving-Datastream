# K-means for Evolving Datastream

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)
Authors
Aniket Sethi - 190001003
Yash Suvarna - 190001068
Garvit Galgat - 190001016
Introduction
The analysis of streaming data has gained significant importance in recent years, posing unique challenges for clustering techniques due to the dynamic and evolving nature of data streams. Our project focuses on addressing the challenges posed by evolving data streams through the development of a K-means algorithm specifically tailored for handling concept drift in streaming data.

Objective
Our main objective is to create an efficient K-means algorithm capable of clustering evolving data streams while adapting to changes in the data distribution.

Features
Evolving Data Handling: Our algorithm is designed to handle evolving data streams where data points arrive sequentially and the underlying distribution may change over time.

Adaptive Clustering: The algorithm adapts to changes in the data distribution by incorporating a restart mechanism whenever a concept drift is detected, ensuring accurate clustering over time.

Approximation Technique: We employ an approximation approach using a surrogate error function that captures the relevant information for clustering quality without explicit concept drift detection.
This repository contains an implementation of the K-means algorithm tailored for evolving data streams. K-means is a popular clustering algorithm, but traditional implementations are not well-suited for data streams where data points arrive continuously and may change over time. This implementation adapts the K-means algorithm to handle such evolving data streams efficiently.

## Features

- **Evolving Data Handling:** The implementation is designed to handle data streams where new data points arrive over time, and the underlying clusters might change.

- **Online Clustering:** The algorithm updates the cluster centroids and assignments incrementally as new data arrives, allowing for efficient and adaptive clustering.

- **Parameter Tuning:** The code provides flexibility in tuning parameters such as the number of clusters (K) and distance metrics, enabling users to customize the clustering process based on their data.

- **Usage Examples:** We provide examples demonstrating how to use the implementation on synthetic and real-world data streams.




## Contributing

Contributions are welcome! Feel free to open a pull request if you find any issues or have improvements to suggest.

## License

This project is licensed under the [MIT License](LICENSE).

---

Give credit to any resources you used or modified for your implementation in this README. Ensure to update the placeholders with actual information and replace "your-username" with your GitHub username.
