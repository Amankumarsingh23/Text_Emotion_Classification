# 😃 Text Emotion Classification  

A **Deep Learning project** that classifies text into different emotions such as **joy, sadness, anger, fear, love, and surprise** using **Keras + TensorFlow**.  

---

## 📌 Project Overview  

This project uses Natural Language Processing (NLP) techniques to build a model that predicts emotions from text.  
It is trained on a labeled dataset and can take custom text input to predict the corresponding emotion.  

✅ **Key Highlights:**  
- Text preprocessing with tokenization and padding  
- Label encoding and one-hot encoding of target emotions  
- Deep Neural Network built with **Keras Sequential API**  
- Real-time text emotion prediction  

---

## 🗂 Dataset  

- **Source:** `train.txt` (labeled dataset)  
- **Columns:**  
  - `Text` → The text input  
  - `Emotions` → Target labels (joy, anger, sadness, fear, love, surprise)  

---

## 📊 Data Processing  

- **Tokenization:** Converts words into integer sequences  
- **Padding:** Ensures all sequences have equal length  
- **Label Encoding:** Converts emotions into integers  
- **One-Hot Encoding:** Makes labels suitable for multi-class classification  

---

## 🧠 Model Architecture  

**Framework:** `Keras + TensorFlow`  

### Layers:  
1. **Embedding Layer:** Converts words into dense vector representation  
2. **Flatten Layer:** Flattens the embedding output  
3. **Dense Layer:** 128 neurons with ReLU activation  
4. **Output Layer:** Softmax activation for multi-class prediction  

---

## 💻 Example Run  

```python
Input:  "She is silent today because she found her dog yesterday!"
Output: ['joy']
