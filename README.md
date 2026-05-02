# IT23661974-playwright-tests_Singlish
## Project Description
This project automates testing of the Chat Sinhala transliteration function at [PixelSuite Chat Translator](https://www.pixelssuite.com/chat-translator).  
Contains **50 negative test cases** where the system fails to convert Singlish to Sinhala correctly.

## Test Cases
| Total | Singlish Types | Expected Result |
|-------|----------------|-----------------|
| 50 | 24 | All FAIL |

## Prerequisites
- Python 3.12
- Google Chrome
- pip

## Installation

### 1. Install Packages
```bash
pip install playwright openpyxl
```
## Running the Tests

From the Command Prompt (inside E:\IT23661974), run the following command:

```bash
PS E:\IT23661974> py -3.12 IT23661974.py --excel "E:\IT23661974\IT23661974.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
