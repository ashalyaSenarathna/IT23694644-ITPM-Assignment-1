# IT3030 - ITPM Assignment 1: Transliteration Accuracy Testing
**Student Name:** SENARATHNA S M A N  
**Registration Number:** IT23694644

## Project Description
This project automates the accuracy testing of the Singlish to Sinhala transliteration function available at [PixelsSuite Chat Translator](https://www.pixelssuite.com/chat-translator). It uses Playwright to simulate user input and captures the actual transliterated output into an Excel file for analysis.

## Git Repository
[https://github.com/ashalyaSenarathna/IT23694644-ITPM-Assignment-1](https://github.com/ashalyaSenarathna/IT23694644-ITPM-Assignment-1)

## Prerequisites
- Python 3.11 or 3.12
- Google Chrome browser (or let Playwright install Chromium)

## Installation Instructions
1. Navigate to the project directory:
   ```bash
   cd IT23694644
   ```
2. Install the required Python packages:
   ```bash
   pip install playwright openpyxl
   ```
3. Install the Playwright browser binaries:
   ```bash
   playwright install chromium
   ```

## Running the Tests
To run the automated test cases and update the Excel file, use the following command:
```bash
python test_automation.py --excel "IT23694644.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```

## Files Included
- `IT23694644.xlsx`: The completed Excel file with 50 test cases and their execution results.
- `test_automation.py`: The Playwright automation script.
- `README.md`: Instructions for setup and execution.
- `Git_Repository_Link.txt`: Link to the public Git repository.
