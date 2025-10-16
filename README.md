🩺 Diabetes Prediction using Machine Learning
📘 Overview

This project aims to predict whether a person is diabetic or not based on medical diagnostic measurements such as glucose level, blood pressure, BMI, and age.
Using Machine Learning techniques (Support Vector Classifier), this project helps demonstrate how AI can contribute to early disease detection and improve healthcare outcomes.

🎯 Project Motivation

Diabetes is one of the fastest-growing health issues worldwide.

Early prediction can help prevent complications and improve quality of life.

Machine Learning models can assist doctors by providing quick, data-driven insights.

📊 Dataset

Dataset Used: PIMA Indians Diabetes Dataset (Kaggle)

Feature	Description
Pregnancies	Number of times pregnant
Glucose	Plasma glucose concentration
BloodPressure	Diastolic blood pressure (mm Hg)
SkinThickness	Triceps skinfold thickness (mm)
Insulin	2-Hour serum insulin (mu U/ml)
BMI	Body Mass Index
DiabetesPedigreeFunction	Diabetes pedigree function
Age	Age in years
Outcome	1 = Diabetic, 0 = Non-Diabetic
🧠 Machine Learning Model

Algorithm Used: Support Vector Machine (SVC)
Why SVC?

Performs well with small to medium datasets.

Effectively handles non-linear data using kernel functions.

Provides clear decision boundaries for classification problems.

⚙️ Workflow

Import Libraries

pandas, numpy, matplotlib, seaborn, sklearn

Load and Explore Dataset

View shape, summary statistics, and missing values.

Preprocess Data

Handle nulls, normalize using StandardScaler.

Split Dataset

Train:Test = 80:20

Model Training

Train SVC classifier on scaled data.

Evaluation

Accuracy Score, Confusion Matrix, Prediction Probability.

Prediction

User can input new data for prediction.

📈 Results
Metric	Value
Training Accuracy	~82%
Testing Accuracy	~78%
Prediction Example	0 → No Diabetes, 1 → Diabetes
Probability Example	[0.73, 0.27] → 73% No Diabetes, 27% Diabetes
💡 Impact on Society

Enables early detection of diabetes risk.

Assists healthcare professionals with data-driven decision support.

Demonstrates the potential of AI in preventive medicine.

Can be extended into a mobile or web app for public use.

🚀 Future Enhancements

Use Deep Learning models (e.g., ANN, CNN).

Integrate API for real-time prediction.

Improve dataset size and diversity.

Build dashboard or web interface for easier access.

🛠️ Tech Stack
Category	Tools / Libraries
Language	Python
ML Library	scikit-learn
Data Processing	pandas, numpy
Visualization	matplotlib, seaborn
Notebook	Jupyter Notebook / VS Code
📂 How to Run
# Clone this repository
git clone https://github.com/<your-username>/Diabetes-Prediction-ML.git

# Navigate into the folder
cd Diabetes-Prediction-ML

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook

🧑‍💻 Author

Prince Jha
Department of Computer Science
📧 [jhap9630@gmail.com
]

🩵 Acknowledgment

Dataset: UCI Machine Learning Repository / Kaggle

Libraries: scikit-learn, pandas, matplotlib

Guided by: [Your Faculty / Mentor Name]
