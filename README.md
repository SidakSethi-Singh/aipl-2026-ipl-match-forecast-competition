# IPL 2026 Match Forecast
Machine learning model to predict IPL 2026 match outcomes.
Built using Python, pandas, and scikit-learn.
Metric: Log Loss
# IPL 2026 Match Forecast

Machine learning model to predict IPL 2026 match outcomes, built for the AIPL forecasting competition.

## Overview
This project uses historical IPL match and team data to predict the outcome of upcoming matches. The model is evaluated using Log Loss, a metric that rewards well-calibrated probability predictions rather than just correct/incorrect calls.

## Tech Stack
- Python
- pandas (data processing)
- scikit-learn (model training/evaluation)

## Project Structure
- `train_bundle/` — training data and model training scripts
- `README.md` — project overview

## How It Works
1. Historical match data is loaded and preprocessed
2. Features are engineered from team stats, venue, toss, and past performance
3. A classification model is trained to output win probabilities
4. Predictions are scored using Log Loss

## Setup
```bash
git clone https://github.com/SidakSethi-Singh/aipl-2026-ipl-match-forecast-competition
cd aipl-2026-ipl-match-forecast-competition
pip install -r requirements.txt



Contributing
Contributions are welcome! Check the Issues tab for beginner-friendly tasks. Please open a PR with a clear description of your change.