# Spotify-Spots 🎧

Spotify Spots is a web-based project that analyzes your Spotify listening data and predicts what you’re likely to enjoy next — based on your past listening behavior, liked tracks, and evolving music taste.

Think of it as a future-facing Spotify Wrapped, mixed with that iconic Spotify bot that judges your music taste — but instead of roasting you, it predicts your next era 😌

##🚀 What It Does

After logging in with your Spotify account, Spotify Spots:

Analyzes your top artists, tracks, and genres

Studies your listening habits and trends over time

Detects rising patterns in your music taste

Predicts:

Artists you’re likely to obsess over next

Genres you’re entering an era of

The overall vibe of your future listening

All predictions are personalized, using only your Spotify data.

##🔐 How It Works

User logs in securely using Spotify OAuth

The app fetches listening data via the Spotify Web API

Data is processed and analyzed using Python

Pattern-based logic forecasts future preferences

Results are displayed on a clean, Spotify-inspired interface

No generic recommendations.
No random guesses.
Just your taste, spotted early.

##🧠 Prediction Logic (High-Level)

Spotify Spots focuses on explainable, data-driven insights:

Artists with consistently high or increasing listens are predicted to stay relevant

Genres showing recent growth are flagged as upcoming favorites

Listening frequency, diversity, and recency are considered

Trends are extrapolated to predict future listening behavior

This keeps the predictions transparent, interpretable, and realistic.

##🛠️ Tech Stack

Frontend

HTML

CSS

JavaScript

Backend

Python

Flask

Data & APIs

Spotify Web API

Pandas

NumPy

Authentication

Spotify OAuth 2.0
