# 💾 Trained Models

This directory stores the serialized (saved) machine learning models using **Pickle (`.pkl`)** format.

## 📦 File List
All models are saved using Scikit-learn's serialization standards:

* **`mlr_model.pkl`**: Multiple Linear Regression model.
* **`rf_model.pkl`**: Random Forest Regression model.
* **`nn_model.pkl`**: Neural Network model (MLPRegressor).

---

# 🇹🇭 คำอธิบายโมเดล

โฟลเดอร์นี้เก็บไฟล์โมเดลที่ "เทรนเสร็จแล้ว" ในรูปแบบไฟล์ **Pickle (`.pkl`)** ซึ่งเป็นมาตรฐานของ Scikit-learn

## 📦 รายชื่อไฟล์
* `mlr_model.pkl`: โมเดล Linear Regression
* `rf_model.pkl`: โมเดล Random Forest
* `nn_model.pkl`: โมเดล Neural Network (เปลี่ยนจาก .h5 มาใช้ .pkl เพราะใช้ Scikit-learn)