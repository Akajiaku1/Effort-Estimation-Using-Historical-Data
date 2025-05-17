# 📊 Effort Estimation Using Historical Data

This project provides a simple yet powerful Streamlit dashboard to estimate software development effort using historical project data and machine learning (Linear Regression). It allows users to train models and make predictions based on features like project size, team experience, and complexity.

## 🚀 Features

- 📁 Upload historical project data in CSV format.
- 🧠 Train a Linear Regression model on your data.
- 📈 View model performance (MSE and R²).
- 🔮 Predict person-month effort for new projects.
- 📊 Interactive and user-friendly Streamlit interface.

---

## 🛠️ Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/effort-estimation-app.git
   cd effort-estimation-app

    Install dependencies

pip install -r requirements.txt

Run the Streamlit app

    streamlit run effort_estimation_app.py

📂 Sample CSV Format

Your dataset should contain the following columns:
Project_Size	Team_Experience	Complexity	Estimated_Effort
10000	3	2	12
15000	5	3	20
8000	2	1	8

    Project_Size: Size of the project (e.g., Lines of Code or Function Points).

    Team_Experience: Average experience of the team (in years).

    Complexity: Numerical representation (1=Low, 2=Medium, 3=High).

    Estimated_Effort: Actual recorded effort (in person-months).

📸 App Screenshot

    (Insert a screenshot here after running the app locally)

📌 Requirements

    Python 3.8+

    Streamlit

    pandas

    scikit-learn

You can install them with:

pip install streamlit pandas scikit-learn

📤 Future Improvements

Add support for other ML models (Random Forest, XGBoost).

Plot feature importance and residuals.

Export trained model for reuse.

    Deploy to Streamlit Cloud or Hugging Face Spaces.

🤝 Contribution

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change or add.
📜 License

MIT License © 2025 [Your Name]


---

### ✅ Optional `requirements.txt` file

```txt
streamlit>=1.35.0
pandas>=2.1.0
scikit-learn>=1.4.0
