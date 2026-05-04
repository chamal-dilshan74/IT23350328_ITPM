# IT23350328 â€“ IT3040 Assignment 1

##  Project Title
Automated Testing for Singlish to Sinhala Transliteration System

*  Repository
https://github.com/chamal-dilshan74/IT23350328_ITPM

---

* Project Structure

IT3040_Assignment_1/

- IT23350328_test_automation.py           â†’ Playwright automation script  
- IT23350328_Assignment 1 - Test cases.xlsx â†’ Excel file with test cases & results  
- IT23350328_requirements.txt             â†’ Python dependencies  
- IT23350328_README.md                    â†’ Project documentation  
- venv/ (optional)             â†’ Virtual environment (not required)

---

*  Technologies Used

- Python  
- Playwright (UI Automation)  
- OpenPyXL (Excel handling)

---

*  How to Run the Project

1. Open terminal inside project folder  

2. (Optional) Activate virtual environment  
   venv\Scripts\activate  

3. Install dependencies  
   pip install -r requirements.txt  
   playwright install  

4. Run the automation script  
   python test_automation.py --excel "IT23350328_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"  

---

*  Output

- Results are automatically written to the Excel file  
- Columns updated:
  - Actual output  
  - Status (PASS / FAIL)  

---

*  Test Case Details

- Total Test Cases: 50+  
- Test Type: Negative Testing  

### Covered Scenarios:
- Mixed language inputs (Singlish + English)  
- Spelling variations  
- Emojis & symbols  
- Real-world scenarios (banking, travel, apps)  
- System-related messages (errors, logs)  
- Numeric and date inputs  

---

*  Important Notes

- This system uses strict comparison  
- Even small differences in Sinhala output (spacing, formatting, spelling) will result in FAIL  
- Some failures are expected due to:
  - Transliteration inconsistencies  
  - Mixed language complexity  
  - UI timing delays  

---

*  Student Information

- Student ID: IT23350328 
- Module: IT3040  
- Assignment: Assignment 1 (Option 1)  

---

*  Final Status

âœ” Automation script working  
âœ” Excel-based validation completed  
âœ” Test coverage includes multiple edge cases  

---

*  Submission Notes

- Virtual environment (venv) is excluded from submission  
- All required files are included  
- Project is fully runnable using IT23350328_requirements.txt  

---
