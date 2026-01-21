# ML + NLP 1-Day Workshop Pack (9AM–6PM)

Audience: Final-year (4th year) B.Tech students  
Format: 10% theory + 90% hands-on

## Folder Structure

- `notebooks/` : Colab-ready labs (Lab 0 to Lab 5)
- `slides/`    : Marp slides (Markdown)
- `trainer/`   : Trainer notes, rubric, schedule

## Suggested Schedule (9:00–18:00)

- 09:00–09:20 — Lab 0: Setup + Warmups
- 09:20–10:30 — Lab 1: Easy ML baseline (Iris)
- 10:30–10:45 — Break
- 10:45–12:00 — Lab 2: NLP spam (BoW)
- 12:00–13:00 — Lunch
- 13:00–14:30 — Lab 3: TF-IDF + SVM + tuning
- 14:30–14:45 — Break
- 14:45–15:45 — Lab 4: Transformers (SST-2)
- 15:45–17:45 — Lab 5: Mini Project (BBC News recommended)
- 17:45–18:00 — Demos + Wrap-up

## Notebooks

1. `Lab_0_Setup_and_Warmup.ipynb`
2. `Lab_1_ML_Baseline_Iris_Classification.ipynb`
3. `Lab_2_NLP_Spam_BoW_LogReg.ipynb`
4. `Lab_3_NLP_TFIDF_LinearSVC_GridSearch.ipynb`
5. `Lab_4_Transformers_Sentiment_Advanced.ipynb`
6. `Lab_5_MiniProject_EndToEnd.ipynb`

## Dataset Notes

- Easy track uses built-in `sklearn.datasets`
- Medium/Advanced track downloads public datasets:
  - SMS Spam (UCI)
  - BBC News CSV (public GitHub)
  - SST-2 via HuggingFace datasets
  - Optional: Toxic comments via HuggingFace `civil_comments`

## Tips for Smooth Delivery

- Keep everyone moving with checkpoint questions:
  - "Did everyone print metrics?"
  - "Did confusion matrix show?"
- Encourage error analysis (wrong predictions) over only accuracy.

## License / Usage

Free to reuse for internal academic workshops.
