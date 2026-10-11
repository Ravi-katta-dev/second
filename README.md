# RRB Section Controller Mock Tests

A lightweight browser-based practice interface for the RRB Section Controller 2025–26 question PDF.

## Use it

1. Open [index.html](./index.html) in a browser, or enable GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder).
2. Choose the original RankMitra RRB Section Controller PDF and select **Import question PDF**.
3. The importer checks for 400 unique numbered questions and groups them into four 100-question mock tests.
4. Select the actual extracted choice text where available, navigate with the question palette, mark questions for review, and submit.
5. After submission, the summary reports correct, incorrect, unanswered, and percentage score. **Review answers** highlights the source PDF's green-marked answer in green and a selected wrong answer in red.

The PDF is processed in the browser using PDF.js. No PDF upload is sent to a server by this page.

## Validation and limitations

- The answer key is embedded from the green-highlighted answer options in the supplied PDF. It was checked against the PDF's green option labels for all 400 questions; all 400 matched.
- Some options are image-based or absent from extracted text. For those choices, the app keeps A–D selectable but displays a note to consult the original PDF. The original PDF should remain the authority for diagrams and image-only content.
- Importing is restricted to the expected 400-question source PDF. Missing IDs, duplicate markers, or an incomplete import are reported rather than silently accepted.
- The PDF.js library is loaded from a CDN, so importing requires an internet connection.

Unofficial practice tool; not affiliated with Indian Railways or RankMitra.
