# MoodLens — AI Sentiment Analyzer 🤖

A simple, single-file website that analyzes any review or comment and predicts whether it's **Positive 😊**, **Negative 😠**, or **Neutral 😐** — instantly, right in your browser.

🔗 **Live demo:** https://yourusername.github.io/sentiment-analyzer/
*(replace this with your actual GitHub Pages link)*

## Features

- 🧠 Instant sentiment detection — Positive, Negative, or Neutral
- 📊 Confidence score and percentage breakdown for each sentiment
- 🔑 Highlights the specific words that influenced the result
- 🕒 Keeps a short history of your recent analyses
- 📱 Fully responsive — works on desktop and mobile
- 🔒 100% private — runs entirely in your browser, no data is sent anywhere
- ⚡ No installation, sign-up, or API key needed

## How it works

This project uses a **lexicon-based NLP model**: it scans the text for known positive and negative words, applies weighting for things like negation ("not good") and intensifiers ("very bad"), and calculates an overall sentiment score — all in plain JavaScript, with no backend or external API required.

## How to use

1. Open the website (link above) or open `index.html` directly in any browser.
2. Type or paste a review/comment into the text box.
3. Click **Analyze Sentiment**.
4. View the result, confidence score, and the words that drove the prediction.

## Tech stack

- HTML, CSS, JavaScript (no frameworks, no dependencies)

## Limitations

This is a rule-based model, not a trained machine-learning model. It works well for clear, direct language but may be fooled by sarcasm, slang, or very subtle phrasing.

## License

Free to use and modify.
