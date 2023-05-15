# K-Means-from-scratch

This is a Python implementation of the K-means clustering algorithm from scratch. K-means is an unsupervised machine learning algorithm used for clustering data points into K different clusters based on their similarity.

## Getting Started

### Prerequisites
- Python 3.x
- NumPy
- Matplotlib
- Pandas
- Jupyter Notebook

### Installation

You can install the required dependencies using pip:

```
pip install numpy matplotlib pandas jupyter
```

### Usage

1. Clone the repository:
   ```
   git clone https://github.com/your-username/kmeans-from-scratch.git
   ```

2. Change directory to the project folder:
   ```
   cd kmeans-from-scratch
   ```

3. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

4. Open the `kmeans.ipynb` notebook in your browser.

5. Run the notebook by clicking on the "Run" button or by pressing Shift+Enter to execute each cell.

## Description

The `kmeans.ipynb` notebook contains the code for K-means clustering from scratch. The notebook uses the following steps:

1. Import the required libraries.
2. Read the data from the CSV file using pandas.
3. Set the stopping criteria for the algorithm.
4. Define the number of clusters (`K`) and the maximum number of iterations.
5. Initialize the centroids randomly.
6. Perform the K-means algorithm by repeating the following steps until the stopping criteria are met or the maximum number of iterations is reached:
   - Assign each data point to the nearest centroid.
   - Update the centroids by computing the mean of the data points assigned to each centroid.
7. Visualize the clusters by plotting the data points and centroids using matplotlib.

The notebook provides an example of using K-means clustering on the "Mall_Customers.csv" dataset. The dataset contains information about customers' annual income and spending score.

The stopping criteria for the algorithm is met after approximately 10 iterations. You can adjust the stopping criteria and other parameters in the notebook according to your needs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

This implementation was inspired by the K-means clustering algorithm. Special thanks to the contributors of the [NumPy](https://numpy.org/), [Matplotlib](https://matplotlib.org/), [Pandas](https://pandas.pydata.org/), and [Jupyter Notebook](https://jupyter.org/) for their excellent tools.

## References

- [K-means clustering](https://en.wikipedia.org/wiki/K-means_clustering)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Jupyter Notebook Documentation](https://jupyter.org/documentation)
