# Employee Attrition Rate Prediction

This project aims to predict the likelihood of employees leaving an organization (attrition) using machine learning techniques. It includes data analysis, model training, and a web-based interface for interacting with the predictions.

## 🚀 Overview

Attrition is a critical challenge for organizations. This project leverages historical employee data to identify patterns and factors contributing to attrition, enabling proactive management.

## 📂 Project Structure

- **`Attrition Rate code/`**: Contains the core logic and resources.
    - **`Attrition Rate.ipynb`**: Jupyter Notebook for Exploratory Data Analysis (EDA) and Model Development.
    - **`Table_1.csv`**: The primary dataset used for training and evaluation.
    - **`mysite/`**: A Django web application providing a user-friendly interface.

## 🛠️ Tech Stack

- **Data Analysis**: Python, Pandas, NumPy, Matplotlib
- **Machine Learning**: Scikit-Learn
- **Web Framework**: Django
- **Version Control**: Git

## ⚙️ Setup & Installation

### Prerequisites
- Python 3.x
- Jupyter Notebook (for `.ipynb` files)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/PRATIKYADAV0104/Attribution-Rate-Prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r "Attrition Rate code/mysite/requirements.txt"
   ```

## 🖥️ Usage

### Data Analysis
To explore the data and model training process, open the Jupyter Notebook:
```bash
jupyter notebook "Attrition Rate code/Attrition Rate.ipynb"
```

### Running the Web App
1. Navigate to the Django project directory:
   ```bash
   cd "Attrition Rate code/mysite"
   ```
2. Run migrations:
   ```bash
   python manage.py migrate
   ```
3. Start the development server:
   ```bash
   python manage.py runserver
   ```
4. Access the app at `http://127.0.0.1:8000/`.

## 📊 Dataset

The project uses `Table_1.csv` which includes features such as:
- Tenure
- Experience
- Age
- Hiring Source
- Marital Status
- Promoted/Non-Promoted
- Job Role Match

---
Developed by [PRATIK YADAV](https://github.com/PRATIKYADAV0104)
