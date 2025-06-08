# Jupyter Notebook to HTML Converter

This repository contains a Google Colab notebook that converts Jupyter Notebook (`.ipynb`) files to HTML. It handles issues with interactive widgets (e.g., `ipywidgets`) that may cause conversion errors.

## How to Use
1. Open the notebook in Google Colab:
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dim-tsoukalas/ipynb-to-html-converter/blob/main/Jupyter_Notebook_to_HTML_Converter.ipynb)
2. Run the cells to install dependencies and start the conversion process.
3. Upload your `.ipynb` file when prompted.
4. Download the generated HTML file.

## Features
- Cleans widget metadata to avoid conversion errors.
- Silently installs required libraries (`nbconvert`, `jupyter`, `nbformat`).
- Includes fallback conversion for robustness.

## Issues
If you encounter errors, check the output messages or open an issue in this repository.

