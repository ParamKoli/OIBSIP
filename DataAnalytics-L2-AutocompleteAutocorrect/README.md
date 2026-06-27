# 🔤 Autocomplete and Autocorrect Data Analytics

**Name:** Param Parag Koli
**Track:** Data Analytics
**Level:** 2 | **Task:** 5
**Batch:** July 2026

## Objective
Analyse the efficiency and accuracy of autocomplete and autocorrect algorithms using NLP techniques. Implement and compare multiple approaches for text prediction and spelling correction on a real text dataset.

## Files
| File | Description |
|------|-------------|
| `ParamKoli_L2_Task5.ipynb` | Main Jupyter Notebook with full analysis |
| `Shakespeare_data.csv` | Dataset used for analysis |

## Tech Stack
Python, Pandas, NumPy, NLTK, PySpellChecker, Matplotlib, Seaborn, Jupyter Notebook

## Analysis Performed
- Dataset loading and inspection
- Text preprocessing pipeline
- Top 20 most frequent words visualisation
- Autocomplete implementation using bigram and trigram n-gram models
- Autocorrect implementation using PySpellChecker
- Autocorrect confusion matrix
- Algorithm comparison — basic vs custom corpus SpellChecker
- Performance metrics for both autocomplete and autocorrect

## Key Findings
- Trigram models provide more contextually accurate predictions than bigrams
- Domain specific training data improves autocorrect accuracy
- Production systems combine n-gram models with neural language models for best results

## Business Recommendations
1. Use trigram models over bigrams for better prediction accuracy
2. Train on domain specific corpora for specialised applications
3. Combine frequency based and neural approaches for production systems
