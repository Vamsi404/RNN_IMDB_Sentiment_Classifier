# 🎥 RNN IMDB Sentiment Classifier

This repository contains the implementation of a Recurrent Neural Network (RNN) using LSTM/GRU layers to perform sentiment analysis on the IMDB movie reviews dataset. The goal is to classify reviews as either **positive** or **negative** based on the text content.

## 🚀 Features

- **Deep Learning Model**: Uses LSTM/GRU layers for sequential data processing.
- **IMDB Dataset**: Preprocessed dataset containing 50,000 highly polarized movie reviews.
- **Binary Classification**: Predicts whether a review is positive or negative.
- **Keras Implementation**: Utilizes Keras API for model building and training.

## 📂 Project Structure

```bash
├── RNN_IMDB_Classifier.ipynb  # Jupyter Notebook with the model code
├── README.md                  # Project documentation
└── requirements.txt           # Python dependencies
```

## 🧰 Prerequisites

- Python 3.x
- TensorFlow/Keras
- Numpy

You can install the required packages using:

```bash
pip install -r requirements.txt
```

## 📊 Dataset

The IMDB dataset contains 25,000 highly polar movie reviews for training and 25,000 for testing. The reviews are preprocessed, and each word is represented as an index based on its frequency.

## 🛠️ Model Architecture

The RNN architecture consists of the following components:

1. **Embedding Layer**: Converts word indices into dense vectors of fixed size.
2. **LSTM/GRU Layer**: Processes sequences to capture temporal dependencies.
3. **Dense Layer**: Outputs the probability of the review being positive.

## 🏃‍♂️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Vamsi404/RNN_IMDB_Sentiment_Classifier.git
   cd RNN_IMDB_Sentiment_Classifier
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook RNN_IMDB_Classifier.ipynb
   ```

3. Run all cells in the notebook to train and test the model.

## 📈 Results

The model achieves an accuracy of around **85%** on the test set, showcasing its ability to generalize well on unseen reviews.

## 🤖 Technologies Used

- **Python**
- **Keras & TensorFlow**
- **Jupyter Notebook**

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## ✨ Acknowledgements

- IMDB Dataset: [IMDB Reviews](https://ai.stanford.edu/~amaas/data/sentiment/)
- TensorFlow Documentation: [Keras API](https://www.tensorflow.org/api_docs/python/tf/keras)

## 👥 Author

- **Vamsi Manda** - [GitHub](https://github.com/Vamsi404)

Feel free to contribute to this project by raising issues or submitting pull requests!
