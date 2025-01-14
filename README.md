# Employee Salary Prediction

## Overview
The Employee Salary Prediction project is designed to estimate employee salaries based on various features such as education, experience, job title, location, and more. By utilizing machine learning models, this system provides accurate predictions that can assist HR departments and organizations in making informed compensation decisions.

## Features
- **Data Preprocessing:** Cleans and processes raw data for analysis.
- **Feature Engineering:** Extracts meaningful features for better predictions.
- **Model Training:** Implements regression models for salary prediction.
- **Real-Time Prediction:** Accepts input features to predict salaries.
- **Performance Metrics:** Provides detailed evaluation metrics such as RMSE, MAE, and R².

## Prerequisites
- Python 3.7+
- Pip (Python Package Installer)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-salary-prediction.git
   cd employee-salary-prediction
   ```
2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The project uses datasets containing employee information. Example datasets include:
- [Kaggle HR Salary Dataset](https://www.kaggle.com)

Download the dataset and place it in the `data/` directory.

## Usage
1. Preprocess the data:
   ```bash
   python preprocess.py
   ```
2. Train the model:
   ```bash
   python train.py
   ```
3. Test the model:
   ```bash
   python test.py
   ```
4. Run the application:
   ```bash
   python app.py
   ```
   Open your browser and navigate to `http://127.0.0.1:5000/` to use the web interface.

## Directory Structure
```
employee-salary-prediction/
├── data/
│   ├── train.csv
│   └── test.csv
├── models/
│   ├── model.pkl
├── scripts/
│   ├── preprocess.py
│   ├── train.py
│   └── test.py
├── app.py
├── requirements.txt
└── README.md
```

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Pandas
  - NumPy
- **Visualization Tools:** Matplotlib, Seaborn

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature-name'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For any queries or suggestions, please contact:
- **Name:** [Debabrata Mohanty]
- **Email:** [mohantydebabrata38@gmail.com]

