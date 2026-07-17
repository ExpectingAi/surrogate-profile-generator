# Surrogate Profile Generator

Internal tool for Expecting.Ai that generates branded surrogate profiles from Zoho CRM questionnaire exports.

## How to use

1. Open `generator.html` in any browser (or host it via GitHub Pages)
2. Upload a CSV/XLSX export from the Zoho "Surrogate Prospects Initial Screening Questionnaire" module
3. Add up to 8 photos
4. Review and edit parsed data
5. Generate, download as HTML, or print to PDF

## Features

- Auto-parses all 182 Zoho questionnaire columns including pregnancy subform rows
- Auto-cleans education codes, relationship status codes, BMI formatting, fee formatting
- Branded output with Expecting.Ai palette (Navy, Purple, Teal, Yellow), Montserrat font, and official SVG logo
- Journey timeline auto-detects surrogacy pregnancies
- Full pregnancy detail table with inline editing
- Responsive mobile layout
- 100% client-side - no surrogate data leaves the browser

## Tech

Single HTML file (~88KB) with embedded CSS/JS. Uses SheetJS (cdnjs) for XLSX parsing and Google Fonts for Montserrat.
