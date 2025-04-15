
# 🌾 Crop Production Prediction in Maharashtra

This project aims to predict the most suitable crop to cultivate in a particular city in Maharashtra, based on environmental data like rainfall, temperature, and humidity. It is a machine learning project using a custom dataset.

---

## 📁 Files in This Repository

- `CropProductionProject.ipynb` – Main Jupyter notebook containing the code and ML pipeline  
- `dataset.xlsx` – Dataset with city-wise environmental data and recommended crops  
- `README.md` – Project documentation

---

## 🧠 Project Overview

This notebook includes:

- Data loading and exploration
- Preprocessing of categorical and numerical features
- Model training (Decision Tree / Random Forest / etc.)
- Prediction based on user input (City Name)
- Evaluation metrics and visualization

---

## 📊 Dataset Description

The dataset (`dataset.xlsx`) includes:

- **City/District Name**
- **Rainfall (mm)**
- **Temperature (°C)**
- **Humidity (%)**
- **Recommended Crop**

---

## 🏃‍♂️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/crop-prediction-maharashtra.git
   cd crop-prediction-maharashtra
   ```

2. Install required libraries (preferably in a virtual environment):
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook CropProductionProject.ipynb
   ```

4. Run the cells step-by-step to load the data, train the model, and make predictions.

---

## 🔍 Sample Input & Output

```python
Input: "Pune"
Output: "Recommended crop to grow: Sugarcane"
```

---

## 📌 Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📬 Feedback

If you find this project useful or have any suggestions, feel free to open an issue or fork the repo and contribute!
