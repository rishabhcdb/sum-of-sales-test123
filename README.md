# Add a Bootstrap table #product-sales that lists each product with its total sale

## Overview
Auto-generated application built with LLM App Builder.

## Task Description
Add a Bootstrap table #product-sales that lists each product with its total sales and keeps #total-sales accurate after render.

## Evaluation Criteria
- document.querySelectorAll('#product-sales tbody tr').length >= 1
- (() => { const rows = [...document.querySelectorAll('#product-sales tbody tr td:last-child')]; const sum = rows.reduce((acc, cell) => acc + parseFloat(cell.textContent), 0); return Math.abs(sum - 3961.22) < 0.01; })()

## Technology
- HTML5, CSS3, JavaScript
- Bootstrap 5
- Papa Parse (CSV processing)

## Usage
Open `index.html` or visit the GitHub Pages URL.

## License
MIT License
