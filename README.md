# 📚 Text Summarization using BART 

This project demonstrates how to use a **pre-trained BART transformer model** (`facebook/bart-large-cnn`) to perform **abstractive text summarization** on a dataset of text highlights.

---

## 📂 Dataset

- **Input File**: `Text Summarization Data.csv`
- **Column Used**:
  - `highlights`: Text passages to summarize

The dataset is loaded using Pandas:
```python
df = pd.read_csv('/content/Text Summarization Data - Text Summarization Data.csv')
