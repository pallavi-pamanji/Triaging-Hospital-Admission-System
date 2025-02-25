# Triaging Hospital Admission System  

## Overview  
The **Triaging Hospital Admission System** is a machine learning-based application designed to prioritize hospital admissions based on emergency severity. It predicts whether a patient requires immediate hospitalization using **Naïve Bayes, MLP, and LSTM**, ensuring efficient resource allocation in emergency departments.  

## Features  
- Machine learning model for emergency case prediction  
- User-friendly hospital web application  
- Fast and accurate predictions using optimized ML algorithms  
- Data preprocessing using `scikit-learn`  
- Result history to track previous predictions  

## Tech Stack  

**Backend:**  
- Python 3.10  
- Django  
- MySQL  
- Pandas  
- scikit-learn  

**Frontend:**  
- HTML, CSS, Bootstrap  

**IDE:**  
- PyCharm / VS Code  

## System Requirements  

**Hardware:**  
- Processor: Intel i7 or higher  
- RAM: 8GB+  
- Storage: 160GB+ HDD  

**Software:**  
- Windows 11 / macOS  
- Python 3.10+  
- MySQL  
- PyCharm or VS Code  

## Installation Guide  

1. Clone the repository:  
   ```sh
   git clone https://github.com/yourusername/triaging-hospital-admission.git
   ```  
2. Navigate to the project directory:  
   ```sh
   cd triaging-hospital-admission
   ```  
3. Create and activate a virtual environment:  
   ```sh
   python -m venv env
   source env/bin/activate  # For macOS/Linux
   env\Scripts\activate     # For Windows
   ```  
4. Install dependencies:  
   ```sh
   pip install -r requirements.txt
   ```  
5. Run the Django server:  
   ```sh
   python manage.py runserver
   ```  
6. Open the browser and visit: **http://127.0.0.1:8000/**  

## Usage Guide  

1. Register/Login to the system.  
2. Upload the dataset (downloaded from Kaggle).  
3. Preprocess data (handle missing values, scaling, etc.).  
4. Train machine learning models.  
5. Predict hospital admission based on input vitals.  
6. View results & history.  

## Dataset Information  

- **Dataset Name:** EDAdmissionDataset  
- **Source:** Kaggle (https://www.kaggle.com/)  
- **Size:** 9.08 MB  
- **Preprocessing:** Handling NaN values using `fillna()` (bfill, ffill, mode, mean).  

## Future Enhancements  

- Integrate deep learning models for better accuracy  
- Build a mobile app version  
- Add a data visualization dashboard  

## License  

This project is **open-source** under the MIT License.  

## Contributing  

We welcome contributions!  
1. Fork the repository.  
2. Create a new branch (`git checkout -b feature-name`).  
3. Commit your changes (`git commit -m "Added feature"`).  
4. Push to branch (`git push origin feature-name`).  
5. Create a **Pull Request**.  

## Contact  

For any queries, feel free to reach out:  
📧 Email: pallavipamanji@gmail.com  







