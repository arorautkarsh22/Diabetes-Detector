# Diabetes-Detector

A machine learning application that predicts the likelihood of diabetes based on health metrics. This project combines a Jupyter Notebook for model development with a Streamlit web application for easy predictions.

## 🎯 Project Overview

Diabetes-Detector uses machine learning to analyze health indicators and predict whether a patient is likely to have diabetes. The model is trained on health data and exposed through an interactive web interface deployed on Vercel.

**Live Application:** [https://diabetes-detector.vercel.app](https://diabetes-detector.vercel.app)

## 📁 Project Structure

```
Diabetes-Detector/
├── README.md                      # This file
├── diabetes_prediction.ipynb       # Jupyter Notebook with model development
├── app.py                          # Streamlit web application
├── pickle.pkl                      # Trained machine learning model
├── scaler.pkl                      # Data scaler for feature normalization
├── requirements.txt                # Python dependencies
```

## 🚀 Features

- **Predictive Model**: Machine learning model trained to detect diabetes risk
- **Web Interface**: Interactive Streamlit app for user-friendly predictions
- **Pre-trained Model**: Ready-to-use trained model saved as pickle files
- **Feature Scaling**: Includes a scaler for consistent data preprocessing
- **Deployment Ready**: Configured for deployment on Vercel

## 📋 Requirements

All dependencies are listed in `requirements.txt`:

```
streamlit
numpy
pandas
scikit-learn
```

## 💻 Installation & Setup

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/arorautkarsh22/Diabetes-Detector.git
   cd Diabetes-Detector
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   streamlit run app.py
   ```

5. **Open in browser**
   - Navigate to `http://localhost:8501`

## 📊 How It Works

### Model Development
- The `diabetes_prediction.ipynb` notebook contains the complete machine learning pipeline:
  - Data exploration and preprocessing
  - Feature engineering
  - Model training and evaluation
  - Model serialization to pickle files

### Web Application
- The `app.py` file implements a Streamlit interface that:
  - Accepts user input for health metrics
  - Loads the pre-trained model
  - Applies feature scaling
  - Generates diabetes risk predictions
  - Displays results to the user

### Model Persistence
- `pickle.pkl`: Serialized trained machine learning model
- `scaler.pkl`: Fitted data scaler for feature normalization

## 📈 Usage

1. Open the web application
2. Enter your health metrics in the input fields
3. Click the prediction button
4. View your diabetes risk assessment

## 🛠️ Technologies Used

- **Python**: Programming language
- **Jupyter Notebook**: Model development and experimentation
- **Streamlit**: Web application framework
- **Scikit-learn**: Machine learning library
- **Numpy & Pandas**: Data processing
- **Vercel**: Deployment platform

## 📝 Model Details

The trained model uses health indicators to predict diabetes risk. The model has been:
- Trained on a diabetes dataset
- Optimized and evaluated for accuracy
- Serialized for production use
- Integrated into a web interface

## 🚢 Deployment

This application is configured for Vercel deployment:
- The Streamlit app can be deployed directly to Vercel
- Model files are included in the repository
- Configuration is ready for production

## 📚 Notebook Exploration

To explore the model development process:
1. Install Jupyter: `pip install jupyter`
2. Open the notebook: `jupyter notebook diabetes_prediction.ipynb`
3. Review the data analysis, preprocessing, and model training steps

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the MIT License.

## 📧 Contact

For questions or suggestions, please reach out to the project owner: [@arorautkarsh22](https://github.com/arorautkarsh22)

---

**Note**: This application is for educational and informational purposes. Always consult with healthcare professionals for medical diagnosis and treatment.
