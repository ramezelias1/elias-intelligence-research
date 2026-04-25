# Elias Intelligence Research

Structural market analysis framework — Elias Intelligence Capital.

## Live Dashboard
**https://ramezelias1.github.io/elias-intelligence-research/**

## Setup (one time only)

### 1. Enable GitHub Pages
- Go to repo Settings → Pages
- Source: Deploy from branch → main → / (root)
- Save

### 2. Get a GitHub Personal Access Token
- GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
- Generate new token → check **repo** scope → copy it

### 3. Upload files to this repo
Upload these files via GitHub web interface (drag & drop):
- `index.html` (already here)
- `analysis.ipynb`

### 4. Run analysis
- Open `analysis.ipynb` in Google Colab
- Paste your token in the CONFIG cell
- Runtime → Run all (~3 mins)
- Results push automatically to GitHub Pages

### 5. Share with Claude for analysis
Just paste the URL: https://ramezelias1.github.io/elias-intelligence-research/results.json

## What it analyses
- 6 stocks: BHP, PLS, REA, ZIP, LTR, PLTR (2024-2025)
- Identifies every 15%+ move within 30 days
- 15-day pre-move window analysis (raw OHLCV only, no TA)
- Wealth Within trend detection (weekly swing highs/lows)
- Compression Score (structural tension indicator)
- Full backtest of compression signal across complete dataset
