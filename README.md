# 🌐 Multilingual Language Identification System

A robust language identification system built using **Naïve Bayes**, **Convolutional Neural Networks (CNN)**, and **Long Short-Term Memory (LSTM)** networks. The project detects the language of a given text sample across **17 diverse languages**, including Indian and foreign scripts, leveraging machine learning and deep learning techniques.

---

## 🧠 Models Used

- **Naïve Bayes (NB)** – Traditional probabilistic classifier using bag-of-words features.
- **CNN** – Text classification using 1D convolutions and word embeddings.
- **LSTM** – Sequence modeling with embedding layers to capture contextual semantics.

---

## 📊 Dataset

- Source: Custom multilingual dataset (`Language_Detection.csv`)
- Total Languages: 17  
  - *Indian*: Hindi, Tamil, Kannada, Malayalam  
  - *Foreign*: Arabic, Danish, Dutch, English, French, German, Greek, Italian, Portuguese, Russian, Spanish, Swedish, Turkish
- Format: Text samples with corresponding language labels
- Preprocessing:
  - Lowercasing, tokenization
  - Label encoding
  - Padding (for deep learning models)

---

## 🏁 Model Performance

| Model       | Accuracy |
|-------------|----------|
| Naïve Bayes | 93.81%   |
| CNN         | 94.78%   |
| LSTM        | 96.52%   |

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- NLP: CountVectorizer, TfidfVectorizer, Tokenization, Padding

---

## 📂 Project Structure

├── Language_detection.ipynb # Main notebook with preprocessing, modeling, and evaluation
├── Language_Detection.csv # Dataset file (text samples and labels)
├── README.md # Project documentation

---

---

## 📝 Research Contribution

- This project was selected for presentation at a research conference.
- The associated paper has been accepted for publication in a **Scopus-indexed journal**.

---

## 📌 How to Run

1. Clone this repository  
2. Install required libraries  

```pip install -r requirements.txt```

3. Run the notebook: `Language_detection.ipynb`



---

## 👨‍💻 Author

**Harpreet**  
*AI & ML Enthusiast | NLP Researcher | Kotlin & Python Developer*  

---

