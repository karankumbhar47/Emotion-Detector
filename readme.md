# README: Emotion Detection Web App Using Streamlit

## Installation Guide

### Prerequisites
Ensure you have Python installed (version 3.7 or higher). You can check your Python version by running:
```bash
python --version
```

### Install Dependencies
1. Create a virtual environment (optional but recommended):
```bash
python -m venv env
```

2. Activate the virtual environment:
   - **Windows:**
     ```bash
     env\Scripts\activate
     ```
   - **Mac/Linux:**
     ```bash
     source env/bin/activate
     ```

3. Install required packages:
```bash
pip install streamlit pandas numpy altair joblib scikit-learn
```

## Running the Streamlit App

1. Ensure your trained model file (`emotion_predictor.pkl`) is in the same directory as your script.
2. Run the Streamlit application using:

```bash
streamlit run app.py
```

## How to Use the Web App

1. Open the Streamlit web page in your browser (the terminal will show the local URL, e.g., `http://localhost:8501`).
2. Enter a text in the text box under **"Write Here"**.
3. Click on the **"Know Emotion"** button.
4. The app will display:
   - The entered text.
   - The predicted emotion along with an emoji representation.
   - Confidence level of the prediction.
   - A bar chart displaying probabilities for each possible emotion.
