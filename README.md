# ITPM Assignment 01 - IT22081766

## Singlish to Sinhala Translator - Playwright Test Suite

This project contains automated test cases for testing the Singlish to Sinhala translator at [Swift Translator](https://www.swifttranslator.com/).

## Project Structure

```
ITPM_ASSIGNMENT1/
├── GitHub_Link.txt    # GitHub repository link
├── TestCases 
    └── Final_ITPM_Assignment1  # Excel file with test cases
├── README.md                      # This file
├── palywright-itpm/           # Playwright project
│   ├── test-results
    |-- playwright-report
    |-- node_modules
│   ├── tests/
│   │   ├── example.spec.ts
│   │   ├── Test_Check.spec.ts # All Test Cases Heer
│   │ 
│   ├── playwright.config.js
│   |── package.json
    |──package-lock.json
    |__.gitignore

└── test-results/                  # Test execution results
```

## Prerequisites

- Node.js (v18 or higher)
- npm (v8 or higher)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/Chamudika07/ITPM_2026_Assignment_1
cd playwright-itpm
```

2. Install dependencies:
```bash
cd singlish-playwright
npm install
```

3. Install Playwright browsers:
```bash
npx playwright install chromium
```

## Running Tests

### Run all tests:
```bash
cd singlish-playwright
npx playwright test
```

### Run tests with UI:
```bash
npx playwright test --ui
```

### View test report:
```bash
npx playwright show-report
```

## Test Cases Summary

| Category | File | Count |
|----------|------|-------|
| Positive Functional | Test_Check.spec.ts | 24 |
| Negative Functional | Test_Check.spec.ts | 10 |
| Positive UI | Test_Check.spec.ts | 1 |
| **Total** | | **35** |

### Expected Test Results

- **25 Positive tests pass** - These verify correct translator behavior
- **10 Negative tests fail** - These are intentional failures demonstrating edge cases the translator cannot handle (e.g., joined words, slang, special characters)

## Author

- Registration Number: IT22081766

## License

This project is for educational purposes only.