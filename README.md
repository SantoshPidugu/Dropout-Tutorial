# Effect of Dropout on Overfitting in Neural Networks

## 📌 Overview
This project demonstrates the effect of dropout as a regularization technique in neural networks. The main objective is to analyze how dropout helps in reducing overfitting and improving the generalization of a model.

The experiment compares model performance:
- Without Dropout
- With Dropout
- Different Dropout values (0.2, 0.5, 0.8)

---

## 📊 Dataset
The MNIST dataset is used in this project. It contains grayscale images of handwritten digits (0–9), each of size 28x28 pixels. It is a standard benchmark dataset for classification tasks.

---

## ⚙️ Implementation
A simple feedforward neural network is implemented using TensorFlow/Keras.

### Models:
1. **Without Dropout**
   - Dense layers only
   - Tends to overfit

2. **With Dropout**
   - Dropout layers added (0.5)
   - Reduces overfitting

3. **Dropout Variations**
   - 0.2 → Slight overfitting
   - 0.5 → Optimal performance
   - 0.8 → Underfitting

---

## 📈 Results
The results show that:
- The model without dropout achieves high training accuracy but lower validation accuracy, indicating overfitting.
- The model with dropout shows a smaller gap between training and validation accuracy, demonstrating better generalization.
- Different dropout values affect performance significantly, highlighting the importance of tuning.

---

## 🧠 Key Insight
Dropout works by randomly disabling neurons during training. This prevents the network from relying too heavily on specific neurons and encourages it to learn more robust and generalized features.

---

## ▶️ How to Run the Project

1. Clone the repository:
```bash
git clone <your-repo-link>
