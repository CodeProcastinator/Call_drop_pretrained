# 📞 Call Drop Prediction System  

## ✅ Project Idea  
This project predicts whether a phone call will drop or not based on input features like:  
- Signal strength  
- Tower distance  
- User speed  
- Network type  
- Weather condition  

It is useful for telecom companies and network engineers to identify weak coverage areas and optimize service.  

---

## 📂 Dataset  
The dataset used for this project is taken from **Kaggle**:  
> [Call Drop Prediction Dataset - Kaggle](https://www.kaggle.com) *(Add your actual dataset link)*  

The dataset contains columns like:  
- signal_strength  
- tower_distance  
- user_speed  
- network_type  
- weather_condition  
- call_dropped (target)  

---

## 🤖 Model  
I have used **Random Forest Classifier** from `sklearn` for this project because it:  
- Works well for classification problems  
- Reduces overfitting  
- Gives high accuracy  

Model accuracy achieved: **91%**  

---

## 🚀 How to Update Dataset & Retrain Model  
If you want to change the dataset or retrain the model, follow these steps:  

1. Replace the CSV file in the `/data` folder with your new dataset.  
2. Open the `model_training.py` file and run:  
```bash
python model_training.py
