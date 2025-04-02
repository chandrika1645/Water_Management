# ML Prediction with Streamlit

## Overview
This project was my **3rd-year annual project at VIT**, where I developed the **front-end using Streamlit**. The goal of the project is to predict water levels based on environmental factors such as **precipitation, salinity, and evaporation** using a pre-trained deep learning model.

## Features
- **Streamlit-based UI** for easy interaction
- **User input fields** for precipitation, salinity, and evaporation
- **Data preprocessing** to normalize input values
- **Deep learning model (Keras)** for making predictions
- **Gauge meter visualization (Plotly)** to display predicted water levels

## Tech Stack
- **Frontend:** Streamlit (Python-based UI framework)
- **Backend:** Keras (for loading and predicting with the ML model)
- **Visualization:** Plotly (for gauge meter display)
- **Data Processing:** Pandas & NumPy

## Setup & Installation
### Prerequisites
Ensure you have **Python 3.x** installed along with the required dependencies:

    pip install streamlit pandas numpy plotly keras tensorflow
1. Clone this repository:

    ```bash
    git clone https://github.com/chandrika1645/Water_Management.git
    cd Water_Level_Sensing-master
    
2. Run the Streamlit app:

    ```bash
    streamlit run app.py
3. Open the localhost URL displayed in the terminal to interact with the app.

## Usage

Enter values for precipitation, salinity, and evaporation.

Click the Submit button to process the input and generate predictions.

View the predicted water level on the gauge meter.

Project Structure

    📂 Water_Level_Sensing-master/
    ├── 📄 app.py  # Main Streamlit application
    ├── 📄 model.h5  # Pre-trained Keras model
    ├── 📄 requirements.txt  # List of dependencies
    └── 📄 README.md  # Project documentation
