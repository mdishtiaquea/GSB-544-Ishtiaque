
# Practice Activity 1.2 — Quarto Submission Guide

## Files
- `pa1_2_mtcars.qmd` — your main notebook (edit and render this)
- `requirements.txt` — Python dependencies for this doc (plotnine, pandas, numpy, statsmodels)

## Render to HTML
1. Install Quarto: https://quarto.org/docs/get-started/
2. Create/activate a Python env and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Render:
   ```bash
   quarto render pa1_2_mtcars.qmd --to html
   ```
   This will produce `pa1_2_mtcars.html` in the same folder.

## Push to GitHub
```bash
git init
git add .
git commit -m "PA 1.2: decode + mtcars visualizations"
git branch -M main
git remote add origin https://github.com/<YOUR-USER>/<YOUR-REPO>.git
git push -u origin main
```

Then submit the repository link in your quiz.
