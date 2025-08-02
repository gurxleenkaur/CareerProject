# Career Advisory AI System

This project provides an AI-powered career advisory system that helps students and users identify suitable career paths, backup options, college recommendations, and job roles based on their inputs. The application includes a predictive model and visualization dashboards using Streamlit.

## 🗂 Project Structure

- `CareerAdvisory.csv` – Main dataset used for training the models.
- `CareerProject.py` – Streamlit-based frontend interface for user interaction.
- `train.py` – Model training script for building and saving machine learning models.
- `requirements.txt` – Python dependencies needed to run the project.

## 🚀 Features

- Predicts the most suitable **Career Interest** and **Target College**.
- Recommends **Backup Courses**, **Job Roles**, and **Counseling Advice**.
- Loads pre-trained models from the `models/` directory.
- Interactive charts and visualizations based on user data.

## 🛠 Installation

1. Clone this repository or extract the ZIP file.
2. Navigate to the project folder.
3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Running the App

Start the Streamlit application:
```bash
streamlit run CareerProject.py
```

## 📂 Model Files

Make sure the following `.pkl` model files exist in the `models/` directory:
- `Target_College.pkl`
- `Career_Interest.pkl`
- `Backup_Course.pkl`
- `Counselor_Recommendation.pkl`
- `Target_Job_Role.pkl`
- `label_encoders.pkl`

These are created using `train.py`.

## 📊 Dataset

The dataset `CareerAdvisory.csv` contains various features such as:
- Academic stream
- Personality traits
- Interests and goals
- Scores or ranks (if applicable)

## 🧠 ML Models

Several classification models are trained and evaluated to predict different outcomes using scikit-learn. Model performance is also saved and visualized.

## 📎 License

This project is for educational and research purposes.

---

Feel free to customize it further or extend the logic to include more career counseling modules.
