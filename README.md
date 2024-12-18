
# ReadMe

## Overview
This project provides an analysis of mobile phone specifications and their relationships using Python and data visualization libraries such as Matplotlib and Seaborn. The dataset includes various features of mobile phones, such as battery capacity, RAM, screen resolution, and support for technologies like 3G, 4G, and Wi-Fi.

---

## Dataset Description
The dataset contains 1000 rows and 21 columns, with each row representing a mobile phone and each column describing a specific feature. Below is a summary of the key columns:

| **Column**          | **Description**                                      |
|----------------------|------------------------------------------------------|
| `battery_power`     | Battery capacity in mAh                              |
| `blue`              | Bluetooth support (1 = Yes, 0 = No)                 |
| `clock_speed`       | Processor speed in GHz                               |
| `dual_sim`          | Dual SIM support (1 = Yes, 0 = No)                  |
| `fc`                | Front camera resolution in megapixels               |
| `four_g`            | 4G support (1 = Yes, 0 = No)                        |
| `int_memory`        | Internal memory in GB                                |
| `mobile_wt`         | Mobile weight in grams                               |
| `n_cores`           | Number of processor cores                            |
| `pc`                | Primary camera resolution in megapixels             |
| `px_height`         | Screen height resolution in pixels                  |
| `px_width`          | Screen width resolution in pixels                   |
| `ram`               | RAM capacity in MB                                  |
| `talk_time`         | Maximum talk time in hours                           |
| `three_g`           | 3G support (1 = Yes, 0 = No)                        |
| `touch_screen`      | Touchscreen support (1 = Yes, 0 = No)               |
| `wifi`              | Wi-Fi support (1 = Yes, 0 = No)                     |

---

## Features and Analysis
This project includes the following analysis:

1. **Visualizing Missing Data**:
   - Heatmaps to identify missing values in the dataset.

2. **Data Distributions**:
   - Histograms to visualize distributions of features like battery capacity, RAM, and camera resolution.

3. **Relationships Between Features**:
   - Scatter plots and regression lines to analyze relationships, e.g., between battery capacity and talk time.

4. **Technology Support Analysis**:
   - Bar plots to compare the number of phones supporting features like 3G, 4G, and Wi-Fi.

5. **Categorical Data Analysis**:
   - Boxplots to study the impact of features like touchscreen and dual SIM on talk time.

---

## Tools Used
The following Python libraries were used in this project:

- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib**: For creating static visualizations.
- **Seaborn**: For advanced and aesthetically pleasing visualizations.

---

## Installation and Usage
### Prerequisites
Ensure you have Python installed along with the required libraries. You can install the libraries using the following commands:

```bash
pip install pandas matplotlib seaborn
```

### Running the Code
1. Clone this repository to your local machine.
2. Load the dataset (`test.txt`) into your working directory.
3. Run the provided Python scripts or Jupyter Notebook to generate the visualizations and insights.

---

## Sample Visualizations
Here are some sample visualizations included in the project:

1. **Relationship Between Battery Capacity and Talk Time**
   - Visualized using scatter plots and regression lines.

2. **Distribution of RAM**
   - Boxplots and histograms to show the spread and outliers in RAM.

3. **Technology Support**
   - Bar plots showing the distribution of features like 3G, 4G, and Wi-Fi support.

---

## Contributing
Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Acknowledgments
The dataset was sourced from Kaggle and analyzed to uncover meaningful insights about mobile phone specifications.
