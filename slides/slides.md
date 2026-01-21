---
marp: true
title: ML + NLP One-Day Workshop
paginate: true
---

# ML + NLP (1-Day Hands-on Workshop)
**Audience:** Final-year students  
**Format:** 10% theory + 90% hands-on

---

## What you will build today
- ✅ Tabular ML baseline classifier
- ✅ NLP spam classifier (BoW → TF-IDF)
- ✅ Model evaluation + error analysis
- ✅ (Bonus) Transformers inference
- ✅ Mini-project presentation

---

## Agenda (9AM – 6PM)
- Setup + Warmup
- Easy ML (Iris)
- Medium NLP (Spam)
- Medium+ NLP (TF-IDF + tuning)
- Advanced NLP (Transformers)
- Mini-project (BBC News / Toxic comments)

---

## ML in 1 picture
**Data → Features → Model → Predictions → Metrics**

---

## Train/Test split (must-have)
Why?
- Prevent memorization
- Measure generalization

---

## Overfitting intuition
- Training score ↑
- Test score ↓  
➡️ model is memorizing, not learning patterns

---

## Metrics cheat sheet
- Accuracy
- Precision / Recall / F1
- Confusion matrix

---

## NLP: Why text is hard
Text is unstructured:
- Different lengths
- Noise (typos, slang)
- Meaning depends on context

---

## Convert Text → Numbers
Classic:
- Bag of Words
- TF-IDF

Modern:
- Transformers (pretrained)

---

## Pipeline mindset (real-world)
Always package steps together:

`Vectorizer → Model`

✅ prevents leakage  
✅ easy to save/reuse

---

## Mini-project rules
Your notebook must include:
1) Load data
2) Train/test split
3) Pipeline
4) Metrics + confusion matrix
5) Error analysis (10 wrong predictions)
6) Demo predictions (5 custom inputs)

---

## What “good” looks like
Accuracy alone is not enough ✅  
You must explain mistakes & patterns.

---

## Wrap-up
Next steps:
- Try a new dataset
- Package your project on GitHub
- Build a small demo app (Streamlit)

