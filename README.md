# Spell Checker with Levenshtein Distance

A Python-based spell checking system that uses Levenshtein distance algorithm and keyboard distance calculations to suggest corrections for misspelled words.

## 📁 Project Files

- **`Levenshtein.ipynb`** - Main Jupyter notebook containing the spell checking implementation
- **`keyboard_distances.csv`** - CSV file with keyboard distance matrix for all letter pairs
- **`missp.dat.txt`** - Dataset containing common misspellings and their corrections

## 🔧 Features

- **Levenshtein Distance Calculation** - Computes edit distance between words
- **English Vocabulary Integration** - Uses NLTK corpus for word validation
- **Keyboard Distance Analysis** - Considers physical keyboard layout for more accurate suggestions
- **Birkbeck Spelling Error Corpus** - Leverages common misspelling patterns for improved corrections

## 📋 Requirements

- Python 3.x
- NLTK library
- Jupyter Notebook
- pandas (for CSV handling)

## 🚀 Getting Started

1. **Install dependencies:**
   ```bash
   pip install nltk pandas jupyter
   ```

2. **Download NLTK data:**
   ```python
   import nltk
   nltk.download('words')
   ```

3. **Run the notebook:**
   ```bash
   jupyter notebook Levenshtein.ipynb
   ```

## 💡 How It Works

1. **Vocabulary Loading** - Downloads and loads English words from NLTK corpus
2. **Distance Calculation** - Implements Levenshtein distance algorithm to measure word similarity
3. **Keyboard Awareness** - Uses keyboard distance matrix to weight corrections based on key proximity
4. **Suggestion Generation** - Combines multiple metrics to provide ranked spelling suggestions

## 📊 Data Sources

- **NLTK Words Corpus** - Standard English vocabulary
- **Keyboard Distance Matrix** - Pre-calculated distances between keyboard keys
- **Birkbeck Spelling Error Corpus** - Common misspelling patterns and corrections

## 🎯 Use Cases

- Text correction applications
- Educational tools for language learning
- Content validation systems
- Writing assistance software

## 📝 Notes

This project demonstrates practical applications of:
- Dynamic programming (Levenshtein distance)
- Natural language processing
- Data-driven spell correction
- Human-computer interaction considerations (keyboard layout)

---

*Part of AIO Project - Module 1: Fundamental Math and Programming*
