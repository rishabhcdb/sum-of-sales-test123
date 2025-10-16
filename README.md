# Publish a single-page site that fetches data.csv from attachments, sums its sale

## Overview
Auto-generated application built with LLM App Builder.

## Task Description
Publish a single-page site that fetches data.csv from attachments, sums its sales column, sets the title to "Sales Summary test123", displays the total inside #total-sales, and loads Bootstrap 5 from jsdelivr.

## Evaluation Criteria
- document.title === 'Sales Summary test123'
- !!document.querySelector("link[href*='bootstrap']")
- Math.abs(parseFloat(document.querySelector('#total-sales').textContent) - 3961.22) < 0.01

## Technology
- HTML5, CSS3, JavaScript
- Bootstrap 5
- Papa Parse (CSV processing)

## Usage
Open `index.html` or visit the GitHub Pages URL.

## License
MIT License
