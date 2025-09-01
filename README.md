# Liver Guardian ML

Liver Guardian ML is a machine learning project designed to assist in analyzing and predicting liver-related health conditions using structured clinical and laboratory datasets. The project provides an end-to-end pipeline covering data preprocessing, exploratory data analysis (EDA), model training, evaluation, and reporting.

---

## Project Structure

```
LiverGuardian/
│-- data/                # Raw data files (excluded from GitHub)
│-- dataset/             # Additional datasets (excluded)
│-- logs/                # Training and evaluation logs
│-- models/              # Saved ML models
│-- outputs/             # Model predictions and evaluation outputs
│-- plots/               # Visualizations and graphs
│-- processed/           # Preprocessed datasets
│-- reports/             # Generated reports and summaries
│-- scalers/             # Scaler objects used in preprocessing
│-- .vscode/             # IDE settings (excluded)
│-- venv/                # Virtual environment (excluded)
│-- main.ipynb           # Main Jupyter Notebook
│-- .gitignore           # Git ignore file
```

---

## 🚀 Features

* End-to-end ML pipeline for liver disease analysis
* Data preprocessing and feature engineering
* Exploratory Data Analysis (EDA) with visualizations
* Model training and evaluation (classification focus)
* Reports for metrics, preprocessing, and insights

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/MrCoss/Liver-Guardian-ML.git
   cd Liver-Guardian-ML
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

## 📊 Usage

Open the main Jupyter Notebook:

```bash
jupyter notebook main.ipynb
```

Or run Python scripts (if modularized):

```bash
python main.py
```

---

## 🧾 Reports

Reports are generated automatically after pipeline execution and stored in `reports/`. These include:

* Data report
* EDA summary
* Preprocessing summary
* Validation metrics

---

## 📈 Future Enhancements

* Integration with deep learning models
* API deployment for predictions
* Interactive dashboards

---

## 🤝 Contributing

Contributions are welcome. Please fork the repo, create a branch, and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.
