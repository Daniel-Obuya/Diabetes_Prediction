
# Diabetes Prediction

This project predicts the likelihood of diabetes in patients using machine learning techniques. It leverages Python libraries such as pandas and scikit-learn to preprocess data, train classification models, and evaluate their performance. The dataset used is based on medical diagnostic measurements.

## Features
- Data preprocessing and visualization
- Model training and evaluation
- User-friendly Jupyter Notebook format
- Streamlit web app for live predictions

## Getting Started
1. Clone the repository.
2. Install required Python packages.
3. Run the Jupyter Notebook to explore the analysis and results.
4. Deploy the Streamlit app for live predictions.

## Dataset
The dataset (diabetes.csv) contains medical diagnostic measurements for diabetes prediction.

## Requirements
- Python 3.x
- pandas
- scikit-learn
- Jupyter Notebook
- streamlit

## Usage

### Jupyter Notebook
Open the `Diabetes_Prediction.ipynb` notebook and follow the steps to preprocess data, train models, and view results.

### Streamlit App
1. After training your model and scaler in the notebook, ensure `trained_model.sav` and `scaler.sav` are saved in the project directory.
2. Run the Streamlit app:
	```bash
	streamlit run app.py
	```
3. Enter patient data in the web interface to get diabetes predictions.

## License
This project is for educational purposes.
