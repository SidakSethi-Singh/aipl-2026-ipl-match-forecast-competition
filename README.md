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




MIT License

Copyright (c) 2026 Sidak Singh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


Contributing
Contributions are welcome! Check the Issues tab for beginner-friendly tasks. Please open a PR with a clear description of your change.