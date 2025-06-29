# Mnist_Dataset_Quantization

🧠 **MNIST Quantization with Keras**  
This project demonstrates how to apply Deep Learning Model Optimization techniques such as **Pruning** and **Quantization** using the MNIST dataset. It is built using **TensorFlow/Keras** and showcases different levels of model compression with accuracy benchmarking.

---

## 📁 Project Structure

- `Quantization.ipynb` : Main Jupyter notebook containing:
  - Model training on MNIST
  - Post-training quantization (PQT)
  - Quantization-aware training (QAT)
  - Model performance comparison

---

## 🚀 Techniques Covered

✅ Baseline model training  
✅ Post-training quantization (INT8)  
✅ Quantization-aware training (QAT)  
✅ Size and latency comparisons  
✅ Accuracy and loss evaluation  

---

## 📊 Sample Results (Model Comparison Table)

| Model Type                     | File Size | Loss    | Accuracy | Load Time (seconds) |
|---------------------------------|-----------|---------|----------|--------------------|
| Normal Model                    | 522 KB    | 0.1653  | 0.9531   | 0.0897             |
| PQT Compressed + Quantized Model | 45 KB     | 0.0903  | 0.9731   | 0.0359             |
| QAT Quantized Model              | 92 KB     | 0.9505  | 0.7449   | 0.0006             |

---

## 🛠 Requirements

```bash
pip install tensorflow numpy matplotlib
