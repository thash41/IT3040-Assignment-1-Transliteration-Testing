# Assignment 1 - Transliteration Accuracy Testing

## Description
This project tests the Chat Sinhala transliteration function in the Pixelssuite Chat Translator website.

Website:
https://www.pixelssuite.com/chat-translator

The Excel file contains 50 negative test cases where the system fails to correctly convert chat-style Singlish input into Sinhala output.

## Prerequisites
- Python
- Google Chrome
- Playwright
- openpyxl

## Install Dependencies
pip install -U pip
pip install playwright openpyxl
playwright install

## Run Tests
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 12000 --retry-wait-ms 4000 --retries 20 --type-delay-ms 150 --slow-mo-ms 500 --save-every 1 --keep-open

## Files
- Assignment 1 - Test cases.xlsx
- test_automation.py
- README.md
- GitHub_Link.txt