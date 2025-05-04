# Irrigation Prediction Using Decision Tree

This project is a machine learning-based solution for predicting irrigation needs based on environmental and crop-specific data. Built using Python and scikit-learn, the project utilizes a Decision Tree Classifier to determine whether or not irrigation is required for various crops, based on key environmental indicators.

## Project Overview

The model is trained on agricultural data that includes:

- **Rainfall (Curah Hujan)**
- **Temperature (Suhu)**
- **Soil Moisture (Kelembapan Tanah)**
- **Crop Type (Jenis Tanaman)**

The target variable is whether a crop **needs irrigation** (`Butuh Irigasi`). The crop types in the dataset include:
- **Rice (Padi)**
- **Peanut (Kacang)**
- **Corn (Jagung)**

## Features & Methodology

- **Data Wrangling**: Cleaned and mapped categorical features, handled missing values, removed duplicates, and explored statistical summaries.
- **Exploratory Data Analysis (EDA)**: Boxplots, histograms, correlation heatmaps, and class distributions were used to understand the dataset.
- **Model Training**: A Decision Tree Classifier was trained and evaluated using train-test splits.
- **Performance Metrics**:
  - Accuracy
  - Classification Report (Precision, Recall, F1-score)
  - Confusion Matrix
- **Visualization**: The trained decision tree was plotted for interpretability.

## Insights & Visualizations

- Time-based trends were analyzed by grouping data by **months** and **quarters**.
- Irrigation prediction trends were plotted across months and quarters for each crop type.
- A heatmap was created to visualize irrigation intensity across crops and months.

## Dataset

The training and testing datasets were sourced from Google Drive and include labeled agricultural records.

## Dependencies

- Python
- Pandas
- NumPy
- scikit-learn
- seaborn
- matplotlib
- gdown (for downloading datasets)

## How to Run

1. Clone this repository.
2. Ensure all dependencies are installed (`pip install -r requirements.txt`).
3. Run the main notebook or script file in Google Colab or your local environment.
4. The model will train, test, and generate performance metrics and visualizations.

## License

This project is released under the MIT License.

## Acknowledgements

- Google Colab for the development environment
- scikit-learn for ML modeling
- Seaborn and Matplotlib for data visualization

---

Feel free to fork or contribute to improve this tool for smart agriculture!
