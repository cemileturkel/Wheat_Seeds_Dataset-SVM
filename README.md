# Wheat Seeds Analysis

This repository contains data and code for analyzing different types of wheat seeds based on their characteristics. The primary dataset used in this analysis is Wheat_Seeds_Dataset.csv.

## Dataset
The `Wheat_Seeds_Dataset.csv` file contains the following columns:

- **Area**: The surface area of the seed.
- **Perimeter**: The perimeter of the seed.
- **Compactness**: The compactness ratio of the seed.
- **Length_of_kernel**: The length of the seed.
- **Width_of_kernel**: The width of the seed.
- **Asymmetry_coefficient**: The asymmetry coefficient of the seed.
- **Length_of_kernel_groove**: The length of the kernel groove.

## Analysis

The analysis includes the following steps:

1. **Data Loading and Preparation**:
      - Load the dataset using pandas.
      - Handle missing values and encode categorical variables.

2. **Exploratory Data Analysis (EDA)**:
      - Visualize the distribution of seed characteristics.
      - Analyze the relationships between different seed characteristics.

3. **Model Building**:
      - Build a Support Vector Machine (SVM) model to classify the types of wheat seeds.
      - Evaluate the model using metrics such as Accuracy.

4. **Prediction**:
Use the trained model to predict the type of wheat seeds for new data points.

## Usage
To run the analysis, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/cemileturkel/Wheat_Seeds_Dataset-SVM.git
    cd Wheat_Seeds_Dataset-SVM
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the analysis script:

    ```bash
    python analysis.py
    ```
## Results
The results of the analysis, including visualizations and model performance metrics, will be saved in the results directory.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
