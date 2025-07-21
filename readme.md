# Osteoporosis Risk Prediction

<div align="center">
  <img src="placeholder_image.jpg" alt="Osteoporosis Prediction" width="300" style="border-radius: 15px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);">
</div>

---

## 🌸 Welcome to the Project

This project, crafted by **Gagana**, aims to predict the risk of osteoporosis in patients using machine learning models based on their medical records. Osteoporosis weakens bones, making them fragile and prone to fractures, particularly in older adults. This repository provides a comprehensive analysis to identify at-risk individuals, enabling early intervention and prevention strategies.

---

## 🌷 Project Overview

The project leverages a dataset of patient medical records to predict osteoporosis risk through:
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and removing irrelevant features.
- **Exploratory Data Analysis**: Investigating key factors like age, hormonal changes, lifestyle, and medical history.
- **Predictive Modeling**: Training models including Logistic Regression, Random Forest, Decision Tree, and Support Vector Classifier.
- **Evaluation**: Assessing model performance using accuracy, precision, recall, and F1 score metrics.
- **Feature Importance**: Identifying critical risk factors for osteoporosis.

**Key Finding**: The Decision Tree Classifier achieved an impressive **~87% accuracy**, highlighting age, hormonal changes, medical conditions, and lifestyle as significant risk factors.

---

## 📊 Dataset

The dataset (`data/osteoporosis.csv`) includes features such as:
- **Age**: Patient's age
- **Gender**: Male or Female
- **Hormonal Changes**: Normal or Postmenopausal
- **Family History**: Presence of osteoporosis in family
- **Lifestyle Factors**: Smoking, alcohol consumption, physical activity
- **Medical History**: Conditions like Rheumatoid Arthritis or Hyperthyroidism
- **Bone Health**: Calcium and Vitamin D levels

*Note*: Due to potential sensitivity, the dataset is not included in the repository. Please contact the repository owner or refer to the source for access.

---

## 🛠 Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/gagana/osteoporosis-risk-prediction.git
   cd osteoporosis-risk-prediction
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **(Optional) Set Up Conda Environment**:
   ```bash
   conda env create -f environment.yml
   conda activate osteoporosis-env
   ```

4. **Ensure Dataset Availability**:
   Place `osteoporosis.csv` in the `data/` folder or follow instructions in the dataset source.

---

## 💻 Usage

Run the Jupyter notebook for an interactive experience:
```bash
jupyter notebook notebooks/Osteoporosis\ Risk\ Prediction\ by\ Gagana\ &\ Team.ipynb
```

Alternatively, use the modular Python scripts in the `src/` folder:
- `data_preprocessing.py`: Load and clean the dataset.
- `modeling.py`: Train and evaluate machine learning models.
- `visualization.py`: Generate feature importance plots.

---

## 📂 Folder Structure

```
osteoporosis-risk-prediction/
├── data/                    # Dataset (osteoporosis.csv)
├── notebooks/               # Jupyter notebooks
│   └── Osteoporosis Risk Prediction by Gagana & Team.ipynb
├── src/                     # Python scripts
│   ├── __init__.py
│   ├── data_preprocessing.py
│   ├── modeling.py
│   ├── visualization.py
├── requirements.txt         # Python dependencies
├── README.md                # This file
├── LICENSE                  # MIT License
├── .gitignore               # Git ignore file
└── environment.yml          # Conda environment configuration
```

---

## 🌟 Results

The analysis revealed:
- **Risk Factors**: Age, hormonal changes, medical conditions, medications, low body weight, calcium/vitamin D deficiency, and sedentary lifestyle increase osteoporosis risk.
- **Model Performance**: The Decision Tree Classifier outperformed others with ~87% accuracy, making it a reliable tool for predicting osteoporosis risk.
- **Visualizations**: Feature importance plots highlight the most influential factors across models.

This project empowers healthcare professionals with insights for early intervention and personalized prevention strategies.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 💌 Contact

Created with 💖 by **Gagana**. For questions or collaboration, reach out via [GitHub](https://github.com/gagana) or email.

---

<div align="center">
  <p style="color: #ff69b4; font-style: italic;">Empowering health through data and innovation.</p>
</div>