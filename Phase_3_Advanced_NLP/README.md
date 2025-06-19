
# 🧠 PHASE 3: Advanced NLP – Transformers & Contextual Language Models

### 📘 Concepts to Master:

| Area                           | Subtopics                                            |
| ------------------------------ | ---------------------------------------------------- |
| **Transformers**               | Attention, Multi-head attention, Positional Encoding |
| **Pretrained Language Models** | BERT, RoBERTa, DistilBERT, GPT-2                     |
| **Fine-Tuning**                | Classification, QA, NER with transformers            |
| **Tokenizers**                 | Byte-Pair Encoding (BPE), WordPiece                  |
| **Contextual Embeddings**      | ELMo vs BERT                                         |
| **Transformer Architectures**  | Encoder-only, Decoder-only, Encoder-Decoder          |
| **Prompt Engineering**         | Prompt tuning vs fine-tuning                         |
| **Masked Language Modeling**   | MLM vs Causal LM                                     |
| **Multi-task Transfer**        | Zero-shot, Few-shot, Multi-task Learning             |

### 💻 Code Focus:

- Use `transformers` (by Hugging Face) to:
    - Fine-tune BERT for sentiment classification (IMDB)
    - Fine-tune BERT for NER
    - Fine-tune T5 or BART for text summarization
    - Use GPT-2 to generate text
- Learn `AutoTokenizer`, `AutoModel`, `Trainer`, and `Datasets` APIs
- Visualize attention weights with BertViz

### 📘 Resources:

- HuggingFace Course: [https://huggingface.co/learn/nlp-course](https://huggingface.co/learn/nlp-course)
- Annotated Transformer: [https://nlp.seas.harvard.edu/](https://nlp.seas.harvard.edu/)
- Papers with Code: Search for “NLP tasks” and SOTA models

### ✅ Project Milestone:

- Build a **custom document QA system using BERT**
- Create a **text summarizer using BART or T5**
- Deploy a **GPT-powered email writer**
