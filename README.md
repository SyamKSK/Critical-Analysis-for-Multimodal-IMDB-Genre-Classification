# Multimodal IMDB Analysis with Keras

This project analyzes two deep learning models—**CNN** and **LSTM**—for predicting movie genres using **movie posters** (images) and **textual overviews** (text) from the IMDB dataset.

---

## Models

### 1. CNN Model
- **Input**: Movie posters (64x64 images).
- **Architecture**: Convolutional and max-pooling layers followed by fully connected layers.
- **Strength**: Good at identifying dominant genres from posters.
- **Limitation**: Struggles with multi-label classification and secondary genres.

### 2. LSTM Model
- **Input**: Textual overviews of movies.
- **Architecture**: Embedding layer, bidirectional LSTM layers, and dense layers.
- **Strength**: Better at capturing nuanced genre details from text.
- **Limitation**: May miss secondary genres in multi-genre films.

---

## Key Findings

- **CNN**: Excels at identifying dominant genres from posters but struggles with secondary genres.
- **LSTM**: Performs better with textual data, capturing more nuanced genre information but still faces challenges with multi-genre classification.

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/multimodal-imdb-analysis.git
   cd multimodal-imdb-analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the models:
   - CNN: `python cnn_model.py`
   - LSTM: `python lstm_model.py`

---

## Conclusion

The CNN model is effective for dominant genre prediction from posters, while the LSTM model performs better with textual overviews. Combining both approaches could improve multi-label genre classification.

---

## Contact

For questions, contact [your-email@example.com](syamksk@outlook.com).
