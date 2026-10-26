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
