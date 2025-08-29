# 📺 Video Chaptering Tool
---------------------------------------------------------------
Overview

The Video Chaptering Tool automatically generates meaningful chapters (segments) from YouTube videos using their transcripts. It fetches transcripts via the YouTube API, applies Topic Modeling (LDA / NMF), and produces a structured output with chapter titles. This makes it easier to navigate and summarize long-form video content.

# ✨ Features
----------------------------------------------------------------
Extracts YouTube transcripts (multi-language support).

Uses TF-IDF + NMF / LDA for topic modeling.

Automatically generates video chapters/segments.

Saves transcript + chapters to CSV.

Provides visualizations of topic distributions.

# 📦 Requirements
-----------------------------------------------------------------
Make sure you have the following installed:

python 3.8+
pandas
numpy
matplotlib
seaborn
scikit-learn
youtube-transcript-api
google-api-python-client
