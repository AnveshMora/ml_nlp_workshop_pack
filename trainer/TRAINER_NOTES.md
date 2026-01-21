# Trainer Notes (Quick Reference)

## Success Criteria per Lab

### Lab 0
- Everyone can run imports and sees a tiny text model predicting.

### Lab 1 (Iris ML)
- Students understand train/test split + evaluation.
- Expected accuracy: 0.90+.

### Lab 2 (SMS Spam BoW)
- Students build a working NLP pipeline.
- Expected accuracy: 0.95+ (often higher).
- Must show 5–10 misclassified examples.

### Lab 3 (TF-IDF + SVM)
- Students learn `Pipeline` and safe tuning via `GridSearchCV`.
- Must save model with `joblib`.

### Lab 4 (Transformers)
- Students run pretrained inference using HuggingFace `pipeline`.
- Evaluate small batch (20 samples).

### Lab 5 (Mini Project)
- Teams pick one track; recommended: BBC News.
- Must show metrics + confusion matrix + error analysis + demo predictions.

## Common Student Errors & Fixes
- **Install issues:** skip transformers & continue with Lab 5 (classical NLP).
- **Data leakage:** always split before fitting (Pipeline helps).
- **Imbalanced data:** focus on F1, not just accuracy.
