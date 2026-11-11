# Bengali review annotation page

This is a static GitHub Pages app for the 200 reviews in `annotation_sheet_v2.csv`. It does not include or read the annotation key.

## Publish on GitHub Pages

1. Create a GitHub repository and upload `index.html` (and this README if you want).
2. In the repository, open **Settings → Pages**.
3. Set the source to **Deploy from a branch**, choose `main` and `/ (root)`, then save.
4. Share the GitHub Pages URL with annotators.

## How responses are saved

- Each response auto-saves in that browser's local storage.
- At the end, the annotator selects **CSV ডাউনলোড** and sends you `annotation_answers.csv`. The CSV has the annotation columns and can be opened in Excel.
- Each annotator's device has a separate copy. The static GitHub Pages link does not collect responses centrally. Ask each annotator to send their downloaded CSV.
- **অগ্রগতির ব্যাকআপ ডাউনলোড** saves a JSON backup; **ব্যাকআপ আমদানি** can restore a JSON backup or merge a downloaded CSV.

## Bengali translation

The controls and instructions are Bengali. The source reviews remain in English so Q2 can be copied exactly. The optional translation button requests an on-demand Bengali translation from Google Translate's public web endpoint; it needs an internet connection. The translation is only a reading aid.
