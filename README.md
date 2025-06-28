
# 🎵 Music Genre Classification Project

This project focuses on classifying music genres using various deep learning architectures, including **Fully Connected Neural Networks (FCNN)**, **Convolutional Neural Networks (CNN)**, **Long Short-Term Memory Networks (LSTM)**, and **Hybrid CNN-LSTM models**. The dataset is based on the widely used **GTZAN Music Genre Dataset**.

---

## 📂 Project Structure
```plaintext
├── DNN_proj_report.pdf         # Detailed project report
├── Untitled.ipynb              # Model training and evaluation notebook
├── README.md                   # Project documentation
```

---

## 📊 Dataset
- **Source:** [GTZAN Dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/data)
- **Description:** The dataset contains spectrogram images and pre-extracted audio features (MFCCs) for 10 music genres:  
  `blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, rock`

---

## 🛠️ Models Implemented
- **FCNN (Fully Connected Neural Network)**: From scratch using NumPy  
- **CNN (Convolutional Neural Network)**: Image-based classification using TensorFlow  
- **LSTM (Long Short-Term Memory)**: Sequential audio feature modeling  
- **CNN + LSTM (Hybrid Model)**: Combines CNN feature extraction with LSTM sequence modeling

---

## 🚀 Results Summary
| Model          | Accuracy  | Notes                         |
|----------------|-----------|-------------------------------|
| FCNN           | ~48%      | Not suitable for sequence data |
| CNN            | ~64%      | Overfitting observed          |
| LSTM           | ~57%      | Slower, less stable learning  |
| CNN + LSTM     | ~65%      | Best generalization, balanced |

---

## ✅ Conclusion
- **Best Model:** CNN + LSTM  
- **Key Learning:** Sequence structure in audio is crucial for genre classification. Pure FCNNs are ineffective, and pure CNNs tend to overfit.

---

## 📚 Requirements
- Python 3.x
- TensorFlow
- NumPy
- Scikit-learn
- Matplotlib

*(Add other libraries you used if needed)*

---

## 💻 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/music-genre-classification.git
   ```
2. Open the notebook:
   ```bash
   jupyter notebook Untitled.ipynb
   ```
3. Run all cells.

---

## 🙌 Acknowledgments
- GTZAN Music Genre Dataset  
- Kaggle community
