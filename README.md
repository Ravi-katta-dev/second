# RRB Section Controller Mock Tests

A lightweight, browser-based practice interface for the RRB Section Controller 2025–26 question PDF.

## Use it

1. Open [index.html](./index.html) in a browser, or enable GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder).
2. Choose the original RankMitra RRB Section Controller PDF and select **Import question PDF**.
3. Choose a mock test. Questions are grouped in batches of 100 (the final batch contains the remaining questions).
4. Select an option, navigate with the question palette, mark questions for review, and submit.

The PDF is processed in the browser using PDF.js. No PDF upload is sent to a server by this page.

## Important limitations

- The supplied PDF's answer key was not detected, so the interface records responses and unanswered/review counts but does not mark answers correct or incorrect.
- Some questions or choices may be image-based. PDF text extraction may not capture those parts; consult the original PDF for diagrams or missing option text.
- The PDF.js library is loaded from a CDN, so importing the PDF requires an internet connection.

Unofficial practice tool; not affiliated with Indian Railways or RankMitra.
