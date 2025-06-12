
## 🧩 PHASE 1: Classical NLP – The Foundations

### 📘 Concepts to Master:

| Area                                | Subtopics                                                            |
| ----------------------------------- | -------------------------------------------------------------------- |
| **Text Preprocessing**              | Tokenization, Lowercasing, Stemming, Lemmatization, Stopwords, Regex |
| **Text Representation**             | Bag of Words, TF-IDF, N-grams                                        |
| **Text Classification**             | Spam detection, sentiment analysis                                   |
| **Lexical Semantics**               | Word similarity, synonyms, antonyms                                  |
| **Syntax Parsing**                  | POS Tagging, Dependency Parsing, Constituency Parsing                |
| **Named Entity Recognition (NER)**  | Organizations, Locations, Names                                      |
| **Topic Modeling**                  | LDA, NMF                                                             |
| **Text Summarization (Extractive)** | TextRank                                                             |

### 💻 Code Focus:

- Build a text preprocessing pipeline (regex + nltk + spaCy)
- Implement BoW and TF-IDF from scratch and with `sklearn`
- Build a spam classifier using Naive Bayes
- POS tagging and NER using `spaCy` and `nltk`
- Topic modeling using `gensim` (LDA)

### 📘 Resources:

- _NLTK Book_ ([https://www.nltk.org/book/](https://www.nltk.org/book/))
- _Speech and Language Processing_ (Jurafsky & Martin) – Chapters 1–8
- RealPython NLP tutorials
- Blog series from TowardsDataScience

### ✅ Project Milestone:

- Build a **news classifier** that uses TF-IDF + Naive Bayes to detect fake news
- Build an **NER-powered resume parser**
