# 📖 Nazrul Subword Language Model

A subword-level LSTM language model trained on the poetry of **Kazi Nazrul Islam**, using [SentencePiece](https://github.com/google/sentencepiece) for tokenization. Designed to improve perplexity and generate Bangla text more naturally.

---

## 🚀 Features

- 🔤 Subword tokenization with BPE (Byte-Pair Encoding)
- 🧠 Two-layer LSTM model with dropout regularization
- 📉 Tracks perplexity on training and validation sets
- ✍️ Generates Bangla text from seed prompts
- 🛠 Built with TensorFlow/Keras + SentencePiece

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/nazrul-language-model.git
cd nazrul-language-model
pip install -r requirements.txt
pip install sentencepiece
````
## 📜 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and distribute with attribution.

---

## 🤝 Acknowledgements

- 📚 [Kazi Nazrul Islam](https://en.wikipedia.org/wiki/Kazi_Nazrul_Islam) — for his literary contributions and inspiring text corpus  
- 🔤 [Google SentencePiece](https://github.com/google/sentencepiece) — for subword tokenization  
- 🧠 [TensorFlow/Keras](https://www.tensorflow.org/) — for model training and architecture
