A beginner-friendly Machine Learning project that predicts whether a student is likely to Pass or Fail based on study habits, attendance, and previous academic scores using a Decision Tree Classifier.

I created this project as a CS student to practice binary classification with scikit-learn, rule enforcement, and building interactive web tools using streamlit.

✨ Features
🌳 Decision Tree Classifier: Interpretable tree-based model trained on student performance metrics.
⚙️ Academic Minimum Eligibility Rules: Automatic rule checks (minimum 75% attendance and 2 hours daily study required to pass).
🌐 Streamlit Web Dashboard: Interactive sliders to adjust parameters and visualize real-time pass/fail predictions.
💻 CLI Mode: Run predictions directly from command line arguments.
🧪 Unit Tests: Full unit test coverage using pytest.
📊 Features Used for Prediction
Daily Study Hours (0 - 24 hours)
Attendance Percentage (0% - 100%)
Previous Test Score (0% - 100%)
Assignments Completed (0 - 20 assignments)
🚀 Installation & Setup
1. Clone Repository
git clone https://github.com/ashmit044/student-pass-fail-predictor.git
cd student-pass-fail-predictor
2. Create Virtual Environment & Install Dependencies
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Linux/macOS:
source venv/bin/activate

pip install -r requirements.txt
🏃 How to Run
1. Launch Streamlit Web UI
streamlit run app.py
2. Run CLI Mode
Interactive terminal prompt:

python app.py
Command-line parameters mode:

python app.py --study-hours 7 --attendance 80 --previous-score 72 --assignments-completed 9
3. Run Unit Tests
pytest
🛠️ Project Structure
student-pass-fail-predictor/
├── data/
│   └── student_performance.csv    # Synthetic student performance dataset
├── app.py                         # ML training, prediction logic, CLI & Streamlit app
├── tests/
│   └── test_predictor.py          # Unit test suite
├── requirements.txt               # Dependencies
├── .gitignore                     # Git ignore configuration
└── README.md                      # Project documentation
📚 What I Learned
Training a DecisionTreeClassifier with max_depth constraints to prevent overfitting.
Splitting data into training/testing sets using train_test_split.
Enforcing domain-specific validation rules alongside ML model predictions.
Building interactive sliders and status alerts using Streamlit.
📄 License
Distributed under the MIT License.
