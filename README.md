# Mental Health Prediction System

## 📌 Project Overview
The Mental Health Prediction System is a Machine Learning-based project designed to analyze factors affecting students' mental health and predict academic pressure levels. The project uses data preprocessing, feature engineering, visualization, regression models, classification models, clustering techniques, and model persistence to build a comprehensive predictive analytics solution.

## 🎯 Objectives
- Analyze factors influencing student mental health.
- Predict academic pressure levels using machine learning algorithms.
- Categorize students into stress-level groups.
- Identify hidden patterns through clustering.
- Support early intervention for student well-being.

## 📊 Dataset
The project uses the **MentalHealthSurvey.csv** dataset containing information such as:

- Gender
- University
- Degree Level
- Degree Major
- Residential Status
- Average Sleep Duration
- Study Satisfaction
- Academic Workload
- CGPA
- Sports Engagement
- Academic Pressure

## 🛠 Technologies Used

### Programming Language
- Python

### Libraries
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 🔄 Project Workflow

### 1. Data Loading
- Load the Mental Health Survey dataset.
- Perform initial inspection and validation.

### 2. Data Preprocessing
- Handle missing values.
- Convert sleep duration categories into numerical values.
- Fill missing data using statistical methods.

### 3. Feature Engineering
- One-Hot Encoding for categorical variables.
- Creation of interaction features:
  - Workload × Study Satisfaction

### 4. Exploratory Data Analysis
- Descriptive statistics
- Correlation analysis
- Heatmaps
- Distribution plots
- Count plots

### 5. Regression Models
The following regression algorithms were implemented:

- Random Forest Regressor
- Decision Tree Regressor
- Linear Regression
- Support Vector Regression (SVR)

Evaluation Metrics:
- Mean Squared Error (MSE)
- R² Score

### 6. Classification Models
Academic pressure was categorized into:

- Low
- Medium
- High

Classification Algorithms:
- Random Forest Classifier
- Decision Tree Classifier

Evaluation Metrics:
- Accuracy Score
- Classification Report

### 7. Clustering Analysis
K-Means Clustering was used to group students based on similar characteristics.

- Number of Clusters: 3
- Visualization using scatter plots

### 8. Model Evaluation
Comparison of machine learning models using:
- Accuracy
- Mean Squared Error
- R² Score

### 9. Model Saving
The trained Random Forest model is saved as:

```bash
StressPredictor.pkl
```

## 📈 Visualizations
The project includes:

- Correlation Heatmap
- CGPA Distribution Histogram
- Sports Engagement Count Plot
- Stress Cluster Visualization

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/mental-health-prediction.git
cd mental-health-prediction
```

### Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn joblib
```

### Run the Notebook




## 🔮 Future Improvements

- Deep Learning Models
- Real-Time Stress Monitoring Dashboard
- Web-Based Prediction System
- Mobile Application Integration
- Personalized Mental Health Recommendations

## 👨‍💻 Author

**Chathura Weerasekara**

- BSc (Hons) Networking & Mobile Computing
- Machine Learning Enthusiast
- UI/UX Designer & Full Stack Developer

## 📄 License

This project is developed for educational and research purposes.
