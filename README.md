# Crop-Yield-Prediction-Using-Machin-Learning-Python

The Crop Yield Prediction using Machine Learning project is designed to forecast agricultural crop yields based on multiple environmental, climatic, and soil parameters. The aim is to assist farmers, agronomists, and government agencies in planning, resource allocation, and maximizing productivity.

By training predictive models on historical crop yield data, the system can provide accurate yield estimations for different crops in varying conditions. The project emphasizes efficiency, interpretability, and potential for real-world deployment in smart agriculture systems.

#  Crop Yield Prediction Using Machine Learning

This project is a web-based application that predicts crop yield based on historical agricultural data and climatic features using a trained machine learning model.

---

## Technologies Used

- **Python 3.10+**
- **Flask** – Web framework for backend
- **HTML + Bootstrap** – Frontend design
- **Scikit-learn** – ML model training (Decision Tree Regressor)
- **NumPy** – Numerical operations
- **Jupyter Notebook** – Data analysis & model development

---

## Project Structure

Crop-Yield-Prediction/
│
├── app.py # Flask app backend
├── dtr.pkl # Trained Decision Tree Regressor model
├── preprocessor.pkl # Preprocessing pipeline (encoding + scaling)
├── yield_df.csv # Dataset used for training
├── templates/
│ └── index.html # Frontend UI (form)
└── static/ (optional) # For any future styling/scripts

---

##  Machine Learning Model

- **Model**: Decision Tree Regressor
- **Features Used**:
  - Year
  - Average Rainfall (mm)
  - Pesticides Usage (tonnes)
  - Average Temperature (°C)
  - Area (Country)
  - Item (Crop Name)
- **Target**: `hg/ha_yield`

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Crop-Yield-Prediction.git
cd Crop-Yield-Prediction

2. Create Virtual Environment (Optional)
python -m venv venv
source venv/Scripts/activate   # On Windows (Git Bash: use 'source')

3. Install Dependencies
pip install -r requirements.txt

4. Run  the Flask
python app.py

5. Access in Browser
Go to: http://127.0.0.1:5000

### Limitations

1.Doesn't support image-based inputs
2.Doesn't use deep learning
3.May produce less accurate results for unseen values

### Future Enhancements

1.Integrate real-time weather API
2.Use satellite data
3.Add multilingual support
4.Mobile app integration
5.Deploy on cloud (Heroku/Render)

### License
This project is for educational and academic purposes only and it is a clone.











