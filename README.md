# IoT-Based Digital Scale for Agriculture: Results and Analysis

## Description

This project explores the implementation of an IoT-based digital scale system in the agricultural sector for weighing harvested crops. The goal of this research was to compare traditional manual weighing methods with modern digital techniques powered by IoT technology. The study focuses on evaluating the accuracy, efficiency, and potential benefits of using IoT-enabled devices for crop measurement, including insights into system optimization. The findings are supported by statistical methods, including descriptive statistics, deviation analysis, and MAPE (Mean Absolute Percentage Error), based on real-world field test data from **October 18, 2024**.

## Features

- **Comparison** of **traditional** versus **IoT-based digital weight measurement** methods in agriculture.
- **Data analysis** with **Pandas**, **NumPy**, and **Matplotlib** to process and visualize measurement logs.
- **Interactive visualizations** for comparing total weight, number of sacks, and deviations between methods.
- **Field test data analysis** from an actual agricultural trial conducted on **October 18, 2024**.

## Prerequisites

Ensure that **Miniconda** or **Anaconda** is installed on your system, along with **Python** and **Jupyter Lab** for running the notebook.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/dikhimartin/iot-digital-scale-agriculture.git
   cd iot-digital-scale-agriculture
   ```

2. **Create the Conda environment from the `environment.yml` file:**

   ```bash
   conda env create -f environment.yml
   ```

3. **Activate the Conda environment:**

   ```bash
   conda activate datascience_package
   ```

4. **Install Jupyter Lab if it's not already installed:**

   ```bash
   conda install -c conda-forge jupyterlab
   ```

5. **Launch Jupyter Lab:**

   ```bash
   jupyter lab
   ```

   Open the `main.ipynb` notebook to begin analyzing the data and comparing traditional versus digital weight measurement methods.

## Running the Project

Once the environment is set up, open the `main.ipynb` file to run the analysis. The notebook includes the following:

- A detailed **comparison of total weight** and the **number of sacks** measured by both traditional and digital IoT-based methods.
- **Statistical analysis** of the data, including Mean, Standard Deviation, and MAPE.
- **Visualizations** to highlight differences in the weight log data between traditional and digital methods.

## Results and Analysis

The first field test was conducted on a rice farm to evaluate the accuracy and efficiency of the IoT digital scale system. The key findings from the test are summarized below:

### **Comparison Between Traditional and Digital Methods**

The comparison of the logs from both traditional and digital weighing methods revealed notable differences. Key metrics from the field test are presented in the table below:

| Aspect       | Traditional | Digital    |
| ------------ | ----------- | ---------- |
| Total Sacks  | 136         | 138        |
| Total Weight | 8996.00 kg  | 9828.45 kg |

The results show a small difference in total weight between the two methods, attributed to inherent measurement variabilities in each method.

### **Comparison Approach**

Several methods were used to compare the performance of traditional and digital weighing systems:

#### **1. Descriptive Statistics**

Descriptive statistics offer an overview of the data distribution for both methods:

- Mean Weight per Sack :
  - Traditional: **142.79 kg**
  - Digital: **138.43 kg**
- Standard Deviation (reflecting variability in measurements):
  - Traditional: **3.97 kg**
  - Digital: **18.13 kg** (indicating greater variability in digital measurements)

#### **2. Deviation Analysis**

The total weight difference between the two methods was calculated as:

- **Total Weight Difference**: **832.45 kg**, showing a significant discrepancy between the two methods.

#### **3. Accuracy Evaluation (MAPE)**

The **Mean Absolute Percentage Error (MAPE)** was calculated to evaluate accuracy:

- **MAPE**: **7.19%**, indicating a reasonable level of accuracy despite differences between methods.

## Contributing

Feel free to contribute to this project by opening an issue or submitting a pull request. Contributions are welcome to further improve the system's functionality, accuracy, and usability in agricultural applications.

Resources for further reading and collaboration:

- [Paradigm Scale](https://dikhimartin.vercel.app/projects/paradigm-scales)

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).