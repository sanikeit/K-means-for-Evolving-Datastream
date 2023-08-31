# K-means for Evolving Datastream

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)

This repository contains an implementation of the K-means algorithm tailored for evolving data streams. K-means is a popular clustering algorithm, but traditional implementations are not well-suited for data streams where data points arrive continuously and may change over time. This implementation adapts the K-means algorithm to handle such evolving data streams efficiently.

## Features

- **Evolving Data Handling:** The implementation is designed to handle data streams where new data points arrive over time, and the underlying clusters might change.

- **Online Clustering:** The algorithm updates the cluster centroids and assignments incrementally as new data arrives, allowing for efficient and adaptive clustering.

- **Parameter Tuning:** The code provides flexibility in tuning parameters such as the number of clusters (K) and distance metrics, enabling users to customize the clustering process based on their data.

- **Usage Examples:** We provide examples demonstrating how to use the implementation on synthetic and real-world data streams.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/K-means-for-Evolving-Datastream.git
   cd K-means-for-Evolving-Datastream
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```




## Contributing

Contributions are welcome! Feel free to open a pull request if you find any issues or have improvements to suggest.

## License

This project is licensed under the [MIT License](LICENSE).

---

Give credit to any resources you used or modified for your implementation in this README. Ensure to update the placeholders with actual information and replace "your-username" with your GitHub username.
