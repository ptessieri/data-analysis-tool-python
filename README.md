# Data Analysis Tool

## Project Overview

This project is a comprehensive data analysis tool built with Python, featuring clustering, PCA, and time series analysis. It enables users to visualize and interpret complex datasets, making it ideal for applications in utilities, finance, research, and other fields where data-driven insights are essential.

---

## Features

1. **PCA Visualization with Eigenvectors and Spectral Clustering Visualization**  
   Visualizes principal components along with eigenvectors and clusters using spectral clustering, helping to reveal patterns and structures in high-dimensional data.

   ![PCA Visualization with Eigenvectors](https://github.com/ptessieri/data-analysis-tool-python/blob/main/Screenshot%202024-10-28%20181428_resized.png?raw=true)

2. **Original Data with Vector Field and KDE Visualization**  
   Depicts original data distributions with vector fields for directional insights and uses Kernel Density Estimation (KDE) to highlight data density, assisting in identifying data concentrations and anomalies.

   ![Original Data with Vector Field](https://github.com/ptessieri/data-analysis-tool-python/blob/main/Screenshot%202024-10-28%20181703_resized.png?raw=true)

3. **Time Series Analysis**  
   Breaks down time series data into trend, seasonal, and residual components, facilitating trend analysis and anomaly detection over time.

   ![Time Series Analysis](https://github.com/ptessieri/data-analysis-tool-python/blob/main/Screenshot%202024-10-28%20182800.png?raw=true)

4. **Histogram Visualization**  
   Displays a 3D histogram of data distribution, providing insights into data variability and spread across multiple dimensions.

   ![Histogram Visualization](https://github.com/ptessieri/data-analysis-tool-python/blob/main/Screenshot%202024-10-28%20181808_resized.png?raw=true)

---

## Use Cases

This tool can be applied in various fields to uncover insights through data visualization:
- **Utilities**: Analyze infrastructure data for maintenance and load predictions.
- **Finance**: Spot trends and anomalies in financial time series data.
- **Research**: Cluster and reduce dimensionality of datasets for pattern recognition and hypothesis testing.

---

## Technical Stack

The tool is built with Python, leveraging the following libraries:
- `matplotlib` for data visualization
- `sklearn` for clustering and PCA
- `scipy` for advanced statistical functions
- `ipywidgets` for interactive controls

---

## Installation

To set up the tool, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/ptessieri/data-analysis-tool-python.git
   ```

2. Navigate to the project directory:
   ```bash
   cd data-analysis-tool-python
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Use

1. **Launch the Tool**: Run the main script to start the tool.
   ```bash
   python main.py
   ```

2. **Interface**: Use the drop-down menu to select data types, sliders to adjust sigma and clusters, and specify bin size to customize the visualizations.

3. **Visualization Options**: 
   - **PCA and Spectral Clustering**: Choose this option to analyze data patterns in high-dimensional spaces.
   - **Time Series Analysis**: Use for trend detection and seasonal analysis.
   - **KDE and Histogram Visualizations**: Analyze data density and distribution patterns.

---

## Future Enhancements

Planned improvements include:
- Additional clustering techniques (e.g., DBSCAN, hierarchical clustering).
- Enhanced customization options for visualizations.
- Integration with other data sources for extended analysis.

---

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

---

## License

This project is open-source and available under the MIT License.

---

## Acknowledgments

Special thanks to resources and tutorials that inspired parts of this project, including [Matplotlib Documentation](https://matplotlib.org/stable/index.html) and [Scikit-Learn User Guide](https://scikit-learn.org/stable/user_guide.html).

---
