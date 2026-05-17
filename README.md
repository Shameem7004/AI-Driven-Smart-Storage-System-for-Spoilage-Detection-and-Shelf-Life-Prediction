# 🧠 AI-Driven Smart Storage System for Spoilage Detection and Shelf Life Prediction

An end-to-end AI-powered system that uses **computer vision** and **machine learning** to detect food spoilage and predict the remaining shelf life of perishable items — helping reduce food waste and optimize storage management.

---

## 📌 Overview

Food spoilage costs billions annually and contributes significantly to global food waste. This project addresses the problem by combining **image classification** with **shelf life prediction** models to build an intelligent storage system capable of:

- Automatically identifying whether a food item is **fresh or spoiled** from an image
- Predicting the **remaining shelf life** (in days) of a stored item based on its condition and environmental factors
- Providing a data-driven foundation for smarter inventory and storage decisions

---

## 📂 Repository Structure

```
├── RP_Image_Classification.ipynb   # Deep learning model for food spoilage detection
├── RP_Shelf_Life_Prediction.ipynb  # ML model for predicting remaining shelf life
└── README.md
```

---

## 🚀 Features

- **Visual Spoilage Detection** — Classifies food images as fresh or spoiled using a Convolutional Neural Network (CNN)
- **Shelf Life Prediction** — Estimates remaining days of usability using regression-based ML models
- **End-to-End Pipeline** — From raw image input to actionable predictions
- **Exploratory Data Analysis** — Includes data visualization and feature analysis
- **Model Evaluation** — Performance metrics including accuracy, confusion matrices, and loss curves

---

## 🛠️ Tech Stack

| Category | Tools / Libraries |
|---|---|
| Language | Python 3 |
| Notebooks | Jupyter Notebook |
| Deep Learning | TensorFlow / Keras |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Image Processing | OpenCV, PIL |

---

## 📓 Notebooks

### 1. `RP_Image_Classification.ipynb`
This notebook builds a **CNN-based image classifier** to detect food spoilage.

**Workflow:**
- Loading and preprocessing food images
- Data augmentation to improve model generalization
- Building and training a CNN architecture
- Evaluating model performance (accuracy, loss, confusion matrix)
- Classifying new food images as **fresh** or **spoiled**

### 2. `RP_Shelf_Life_Prediction.ipynb`
This notebook trains a **regression/classification model** to predict how long a food item will remain usable.

**Workflow:**
- Dataset loading and exploratory data analysis (EDA)
- Feature engineering (storage conditions, temperature, humidity, item type, etc.)
- Training multiple ML models and comparing performance
- Predicting remaining shelf life in days

---

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

```bash
Python >= 3.8
Jupyter Notebook or JupyterLab
```

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Shameem7004/AI-Driven-Smart-Storage-System-for-Spoilage-Detection-and-Shelf-Life-Prediction.git
cd AI-Driven-Smart-Storage-System-for-Spoilage-Detection-and-Shelf-Life-Prediction
```

2. **Install required dependencies:**

```bash
pip install tensorflow scikit-learn pandas numpy matplotlib seaborn opencv-python pillow
```

3. **Launch Jupyter Notebook:**

```bash
jupyter notebook
```

4. **Open and run the notebooks** in order:
   - `RP_Image_Classification.ipynb`
   - `RP_Shelf_Life_Prediction.ipynb`

---

## 📊 Model Performance

| Model | Task | Metric |
|---|---|---|
| CNN (Image Classifier) | Spoilage Detection | Accuracy |
| ML Regressor | Shelf Life Prediction | MAE / RMSE |

> Detailed results and plots are available inside each notebook.

---

## 🎯 Use Cases

- **Smart Refrigerators & Storage Units** — Automated spoilage alerts
- **Supermarkets & Warehouses** — Inventory freshness management
- **Supply Chain Optimization** — Reduce waste by prioritizing items nearing expiry
- **Food Safety Systems** — Early warning systems for perishable goods

---

## 🔮 Future Improvements

- [ ] Deploy as a web app or REST API (Flask / FastAPI)
- [ ] Real-time detection using a live camera feed
- [ ] Expand dataset to cover more food categories
- [ ] Integrate IoT sensors (temperature, humidity) for richer predictions
- [ ] Build a mobile-friendly interface for in-storage scanning

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source. Feel free to use, modify, and distribute it with attribution.

---

## 👤 Author

**Shameem7004**  
GitHub: [@Shameem7004](https://github.com/Shameem7004)

---

> *"Reducing food waste, one prediction at a time."*
