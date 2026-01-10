# ❤️ Heart Disease Prediction: From Scratch to Deep Learning

## 📌 Giới thiệu
Dự án **Heart Disease Prediction: From Scratch to Deep Learning** tập trung vào việc dự đoán khả năng mắc **bệnh tim** dựa trên tập dữ liệu **UCI Heart Disease Dataset**.

Mục tiêu chính:
- Tự triển khai Logistic Regression bằng NumPy
- So sánh với Scikit-learn
- Cải thiện kết quả bằng Deep Learning (TensorFlow)

---

##  Nội dung chính

### 1️Tiền xử lý dữ liệu
- Imputation giá trị thiếu
- Chuẩn hóa dữ liệu (StandardScaler)
- One-Hot Encoding cho biến phân loại
- Pipeline & ColumnTransformer

**Features**
- Numerical: age, trestbps, chol, thalch, oldpeak
- Categorical: sex, cp, restecg, slope, thal
- Target: num → nhị phân (0: không bệnh, 1: có bệnh)

---

###  Logistic Regression from Scratch
- Sigmoid Function
- Binary Cross-Entropy Loss + L2 Regularization
- Gradient Computation
- Gradient Descent tối ưu w, b

---

### Scikit-learn Models
- LogisticRegression
- LogisticRegressionCV (Cross Validation)

---

### Deep Learning (TensorFlow)
**Kiến trúc mạng:**
- Dense 128 → ReLU → BatchNorm → Dropout 45%
- Dense 64 → ReLU → BatchNorm → Dropout 35%
- Dense 32 → ReLU → Dropout 25%
- Output: Sigmoid

---

## Kết quả

| Model | Accuracy |
|------|----------|
| Manual Logistic Regression | ~74.35% |
| Scikit-learn Logistic | ~81.52% |
| Scikit-learn CV | ~80.54% |
| TensorFlow Neural Network | **~84.78%** |

---

## 🛠️ Cài đặt

```bash
pip install -r requirements.txt
```

---

## Kết luận
Dự án giúp hiểu sâu Logistic Regression, Pipeline tiền xử lý dữ liệu và cách áp dụng Deep Learning để cải thiện hiệu suất dự đoán.

---

