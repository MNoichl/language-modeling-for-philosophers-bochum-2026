# The Philosopher's Guide to Language Modeling

Reveal.js slides for the Bochum talk on 24 July 2026.

[View the live slides](https://mnoichl.github.io/language-modeling-for-philosophers-bochum-2026/)

[Open the text-analysis workbook in Google Colab](https://colab.research.google.com/github/MNoichl/language-modeling-for-philosophers-bochum-2026/blob/main/notebooks/workbook_01_text_analysis.ipynb)

## Build

```sh
quarto render talk.qmd
```

This creates `index.html`, the entry point expected by GitHub Pages.

## Preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.

## Publish with GitHub Pages

Push the repository to GitHub, then select **Deploy from a branch** in
**Settings → Pages** and serve the repository root from the default branch.

The `.nojekyll` file ensures that GitHub Pages serves the generated Quarto
assets without Jekyll processing.
