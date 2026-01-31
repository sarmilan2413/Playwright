# Tamil Transliteration Test Suite

A **Playwright-based automated test suite** for validating Tamil transliteration conversion in the [Changathi Tamil Translator](https://tamil.changathi.com) web application.

---

## 📖 Project Overview

The **Tamil Transliteration Test Suite** automates testing of Romanized Tamil (Singlish/Tanglish) input conversion into proper Tamil script.  
It ensures:

- ✅ Correctness of transliteration output  
- ✅ Handling of slang, typos, mixed English, numbers, and formatting  
- ✅ Realistic typing behavior simulation  
- ✅ Detailed pass/fail reporting  

This suite is suitable for **QA assignments, academic projects, and real-world automation testing**.

---

## ✨ Key Features

- **Positive functional tests** for clean inputs  
- **Negative / robustness tests** for messy or unusual inputs  
- **Character-by-character typing simulation** to mimic real user behavior  
- **Automatic retry** for temporary failures  
- **Markdown and HTML test reports** for easy review  
- **Robust handling** of dynamic conversion  

---

## 📂 Project Structure

amil-Transliteration-Test-Suite/ │ ├─ tests/                  # Playwright test scripts │   ├─ positive-tests.spec.ts │   └─ negative-tests.spec.ts │ ├─ data/                   # Input and expected output files │   ├─ positive-cases.json │   └─ negative-cases.json │ ├─ reports/                # Test reports │   ├─ html-report/ │   └─ markdown-report.md │ ├─ utils/                  # Helper functions │   └─ typing-helper.ts │ ├─ playwright.config.ts    # Playwright configuration │ └─ README.md               # Project documentation

---

## ⚙️ Setup & Usage

### Requirements
- [Node.js](https://nodejs.org/) (latest LTS recommended)
- [Playwright](https://playwright.dev/)

### Install Dependencies
```bash
npm install





