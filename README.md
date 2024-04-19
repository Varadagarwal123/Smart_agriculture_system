### Overview
This project aims to build a crop recommendation system using machine learning algorithms. The system analyzes various environmental factors such as nitrogen, phosphorus, potassium levels in the soil, temperature, humidity, pH, and rainfall to recommend suitable crops for cultivation.

#### Dataset
The dataset used for training and testing the machine learning models is stored in Crop_recommendation.csv. It contains information about the nutrient levels and environmental conditions for different types of crops.

#### Features
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH level
- Rainfall

#### Target
- Crop

#### Dependencies
- pandas
- numpy
- statsmodels
- matplotlib
- seaborn
- scikit-learn
- mlxtend

Install the dependencies using the following command:

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/Varadagarwal123/Smart_agriculture_system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Smart_agriculture_system
    ```
3. Ensure you have Python installed. You can download Python from [here](https://www.python.org/downloads/).
4. Install the required dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```
5. Run the `CropPrediction.ipynb` Jupyter notebook to explore the dataset, preprocess the data, train machine learning models, and evaluate their performance.
6. Run the `crop_prediction_app.py` Python script to deploy the web application for crop prediction:
    ```bash
    python crop_prediction_app.py
    ```
7. Once the application is running, open a web browser and go to http://localhost:5000 to access the application.
8. Enter the required environmental parameters and click on the "Get Recommendations" button to get crop recommendations.
