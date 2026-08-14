# Phone & Email Extractor (Clipboard Scraper) (affectionately named sales spider)

A lightweight Python utility that automatically scans text on your clipboard, extracts phone numbers and email addresses using regular expressions, and copies or outputs the clean results.

Based on the classic automation project from *Automate the Boring Stuff with Python*, this script makes grabbing contact information from messy documents, emails, or web pages instantaneous.

## Features

* **Regex-Powered Matching:** Robust regular expressions designed to handle optional area codes, multiple separator formats (spaces, hyphens, periods), and common phone extensions.
* **Email Extraction:** Case-insensitive email parser capturing standard domain patterns.
* **Clipboard Integration:** Pulls input directly from your system clipboard and processes it instantly.

## Technologies Used

* **Language:** Python 3.5+
* **Libraries:**
* `re`: For pattern matching and regular expression compilation.
* `pyperclip`: For cross-platform clipboard read/write operations.



## How It Works

1. Copy any block of text containing phone numbers and/or email addresses to your clipboard.
2. Run the script:
```bash
python script.py

```


3. The script strips out the clutter, parses the phone numbers and emails, and outputs the formatted results directly to your terminal.

---
