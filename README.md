# Laptop-Price-Predictor
A machine learning web application that predicts the price of a laptop based on user-specified features such as brand, processor type, RAM, storage, and GPU.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.2.2-orange)
![Flask](https://img.shields.io/badge/Flask-2.2.5-lightgrey)
![Heroku](https://img.shields.io/badge/Deployed-Heroku-purple)

---

## 🚀 Live Demo

> Coming soon! *(If deployed on Heroku or other platforms, include the link here)*

---

## 📌 Features

- Predicts laptop prices based on user input.
- Built using regression algorithms with custom ML pipelines.
- Clean, user-friendly interface powered by Flask.
- Fully deployed and accessible via Heroku (or can be run locally).
- EDA and preprocessing handled through Jupyter Notebook.

---

## 🧠 Machine Learning Workflow

- **Data Collection**: Real-world dataset of laptop specifications.
- **Data Cleaning & Preprocessing**:
  - Missing value handling
  - Label encoding of categorical variables
  - Feature scaling
- **Model Training**:
  - Linear Regression and other regression models
  - Evaluation with R² score and RMSE
- **Model Deployment**:
  - Model serialized with `pickle`
  - Served through Flask web application
  - Configured for deployment using `Procfile`, `setup.sh`, and `requirements.txt`

---

## 🗂️ Project Structure

├── app.py # Flask web application
├── Laptop Price Predictor.ipynb # Jupyter Notebook for EDA and model training
├── pipe.pkl # Trained ML model pipeline
├── laptop_data.csv # Dataset used
├── requirements.txt # Dependencies
├── Procfile # Heroku deployment config
├── setup.sh # Heroku buildpack script
├── .gitignore

yaml
Copy
Edit

---

## 🔧 Installation & Usage

### Prerequisites
- Python 3.10+
- pip

### Setup Instructions

```bash
git clone https://github.com/yourusername/laptop-price-predictor.git
cd laptop-price-predictor

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
Open your browser and go to http://127.0.0.1:5000/ to use the app.

📈 Sample Input
Brand	Processor	RAM	Storage	GPU
Dell	i7	16GB	512GB SSD	NVIDIA

➡️ Output: ₹80,000 (example)