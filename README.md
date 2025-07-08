# Mood-Driven Movie Recommender System Using NLP

This project demonstrates how to combine **Natural Language Processing (NLP)** and user sentiment analysis to build a personalized **Mood-Driven Movie Recommender System.** Users can input free-form text expressing their mood, and the system recommends movies aligned with the detected emotion.

---

## Project Overview

- **Objective:** Recommend movies tailored to a user’s current mood, enhancing movie discovery with a personalized touch.
- **Approach:** Fine-tune a transformer-based NLP model (DistilBERT) on emotion-labeled data to classify user mood, then fetch movies from The Movie Database (TMDb) API corresponding to the predicted emotion.
- **Model:** DistilBERT transformer from Hugging Face, fine-tuned on the **Emotion** dataset.
- **Emotions Detected:** joy, sadness, anger, etc.
- **APIs Used:** The Movie Database (TMDb) API.
- **Cloud Services:** Google Cloud Storage (optional).
- **Libraries:** transformers, accelerate, datasets, bertviz, umap-learn, PyTorch.

---

## Repository Contents

- `mood-driven-movie-recommender.ipynb` — Jupyter notebook containing:
  - Data loading and exploration
  - Model fine-tuning and evaluation
  - Inference and movie recommendation logic
- `Mood Driven Recommender Using NLP.pdf` — Project documentation.
- `README.md` — Project overview.



---

## Installation

Clone the repo:

```bash
git clone https://github.com/yourusername/mood-driven-movie-recommender.git
cd mood-driven-movie-recommender
```

## How Use
1. Launch Jupyter Notebook:

2. Open mood-driven-movie-recommender.ipynb.

3. Follow the notebook cells to:
  - Load and analyze the Emotion dataset.
  - Fine-tune DistilBERT for emotion classification.
  - Enter your own text to detect mood and receive movie recommendations.

```bash
User Input:
    "I feel so happy and full of energy today!"

→ Predicted Emotion:
    Joy

→ Movie Recommendations:
    [List of movies fetched from TMDb]
```

## Features
- Detects emotions in free-form text using NLP.
- Maps emotions to curated movie lists.
- Demonstrates fine-tuning of transformer models on custom tasks.
- Potential for deployment as a web app or chatbot.

## Possible improvements
- Expand emotion categories for finer granularity.
- Integrate real-time sentiment detection via speech or facial emotion analysis.
- Deploy as a web app using Streamlit or Flask.
- Enable personalized recommendations based on user watch history.
- Enhance visualization of emotion clusters or model insights.


