# Test Automation Setup

## Prerequisites

Install the required Python and Node.js dependencies:

Python 3.11 or 3.12 is required.

Open directory ```test_automation``` in terminal and then run the following commands one by one.

```bash
pip install --upgrade pip
```
```bash
pip install playwright openpyxl
```
```bash
python -m playwright install chromium
```

## Run with Excel input

```bash
 python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```

## Student's details:

HEWAGE D. H. D. R.  
IT23585508 


## Notes

- `playwright` is used for browser automation.
- `openpyxl` is used for working with Excel files.
