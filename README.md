<div align="center">

# 🧠 Deep Learning — Neural Network Architectures

**Six core neural network architectures, built and trained end to end — ANN, CNN, LSTM, Self-Organizing Maps, Boltzmann Machines and AutoEncoders — with TensorFlow/Keras and PyTorch.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-FF6F00?logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![Colab](https://img.shields.io/badge/Runs%20on-Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)

</div>

---

## 🎯 What's inside

Each notebook takes one architecture from raw data to a working model on a real-world problem — customer churn, image classification, stock-price forecasting, fraud detection and movie recommendation.

| # | Architecture | Type | Problem solved | Framework | Data |
|---|---|---|---|---|---|
| 1 | [Artificial Neural Network (ANN)](1.%20ANN/artificial_neural_network.ipynb) | Supervised | Predict which bank customers will churn — encoding, scaling, a deep ANN, confusion matrix | TensorFlow / Keras | `Churn_Modelling.csv` (included) |
| 2 | [Convolutional Neural Network (CNN)](2.%20CNN/convolutional_neural_network.ipynb) | Supervised | Classify cat vs. dog images — image augmentation, convolution, pooling, single-image prediction | TensorFlow / Keras | Cats & dogs images ([Kaggle](https://www.kaggle.com/c/dogs-vs-cats)) |
| 3 | [Recurrent Neural Network (LSTM)](3.%20RNN%20and%20LSTM/rnn.ipynb) | Supervised | Forecast Google stock price trends with a stacked LSTM using 60-day time steps | TensorFlow / Keras | `Google_Stock_Price_Train/Test.csv` (included) |
| 4 | [Self-Organizing Map (SOM)](4.%20SOM/SOM.ipynb) | Unsupervised | Detect potential fraud in credit-card applications by visualising outliers on the map | MiniSom | `Credit_Card_Applications.csv` (included) |
| 5 | [Restricted Boltzmann Machine](5.%20Boltzmann%20Machine/Boltzmann_Machine.ipynb) | Unsupervised | Build a movie recommender that predicts like / dislike ratings | PyTorch | MovieLens — downloaded by the notebook |
| 6 | [Stacked AutoEncoder](6.%20AutoEncoders/AutoEncoders.ipynb) | Unsupervised | Predict movie ratings (1–5 stars) for a recommender system | PyTorch | MovieLens — downloaded by the notebook |

---

## 🚀 Getting started

```bash
git clone https://github.com/ahmadhassan-aiops/deep-learning-neural-network-architecture.git
cd deep-learning-neural-network-architecture
pip install numpy pandas matplotlib scikit-learn tensorflow torch minisom jupyter
jupyter notebook
```

Run each notebook from inside its folder. **Google Colab** is recommended for the CNN and PyTorch notebooks (free GPU).

- **CNN:** download the cats & dogs images and arrange them as `dataset/training_set/`, `dataset/test_set/` and `dataset/single_prediction/` inside `2. CNN/`.
- **Boltzmann Machine & AutoEncoders:** the first cells download the [MovieLens](https://grouplens.org/datasets/movielens/) ml-100k and ml-1m datasets from GroupLens automatically (`wget` works on Colab and Linux/macOS).

---

## 📌 About these notebooks

I had the opportunity to go through the **Deep Learning A-Z** course (SuperDataScience) for my own understanding, and these notebooks are based on its code templates — I worked through and experimented with them to build my deep learning foundations.

🚧 **Coming soon:** complete, course-wise deep learning notebooks with my own detailed explanations and worked examples will be uploaded to this repository.

---

## 🧭 Part of a complete Data Science path

**Python basics → NumPy → Pandas → Matplotlib → Seaborn → Statistics → Machine Learning → Deep Learning**

- 🐍 [Python for Data Science](https://github.com/ahmadhassan-aiops/python-for-data-science)
- 🔢 [NumPy](https://github.com/ahmadhassan-aiops/Numpy)
- 🐼 [Pandas](https://github.com/ahmadhassan-aiops/Pandas)
- 📈 [Matplotlib](https://github.com/ahmadhassan-aiops/matplotlib)
- 🎨 [Seaborn](https://github.com/ahmadhassan-aiops/seaborn)
- 📊 [Statistics](https://github.com/ahmadhassan-aiops/statistics-for-data-science)
- 🤖 [Machine Learning](https://github.com/ahmadhassan-aiops/machine-learning-algorithms-and-techniques)
- 🧠 **Deep Learning** ← you are here

---

## 👨‍🏫 About the author

**Ahmad Hassan** — AI/ML Engineer & Instructor with 5+ years of experience
1,500+ hours of live teaching, 100+ students mentored from medicine, business and engineering into data roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmadhassan--aiops.github.io-0EA5A4)](https://ahmadhassan-aiops.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad%20Hassan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-hassan-79a44b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadhassan--aiops-181717?logo=github&logoColor=white)](https://github.com/ahmadhassan-aiops)

⭐ Star the repo to get notified when the full course notebooks land!
