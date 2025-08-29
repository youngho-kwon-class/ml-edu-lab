# EN→FR Translation: From Scratch vs. Pretrained

This folder contains two Jupyter notebooks demonstrating two very different approaches to English→French translation:

## 1. BERT+GPT Hybrid Transformer (D2L Pattern) – From Scratch
**File:** `bert_gpt_hybrid_transformer_d2l.ipynb`  
- Based on the TransformerEncoder/Decoder structure and PositionalEncoding from the D2L *Transformer* chapter
- Reconfigured into a BERT‑style encoder and a GPT‑style decoder
- Trained on the small D2L EN–FR dataset  
- ⚠ Limited translation quality — goal is to understand the architecture and training process

## 2. Pretrained MarianMT (Hugging Face) – Instant Translation
**File:** `en2fr_hf_marianmt_instant_translation.ipynb`  
- Uses Hugging Face `Helsinki-NLP/opus-mt-en-fr` pretrained model
- Translates instantly without any training
- Pretrained on large‑scale parallel corpora → high‑quality results out of the box

---

## 🎯 Learning Objectives
- Understand the encoder–decoder Transformer architecture
- See the effect of dataset size and training time on performance
- Compare a scratch‑built model with a state‑of‑the‑art pretrained model

## 🚀 How to Use
1. Open and run the *from scratch* notebook first to explore the architecture and observe its limitations.
2. Then run the *pretrained* notebook on similar sentences and compare the outputs.
3. Reflect on the trade‑offs in time, data, and accuracy.

---

## 📦 Requirements
- Google Colab (recommended) or Jupyter Notebook
- PyTorch, `d2l`
- For pretrained demo: `transformers`, `sentencepiece`

## 📚 References
- [Dive into Deep Learning – Transformer chapter](https://d2l.ai/chapter_attention-mechanisms/transformer.html)
- [Hugging Face MarianMT Documentation](https://huggingface.co/Helsinki-NLP/opus-mt-en-fr)
