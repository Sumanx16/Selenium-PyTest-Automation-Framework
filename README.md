# 🚀 Selenium-PyTest-Automation-Framework

Build-from-scratch **Web Test Automation Framework** using **Pytest** and **Selenium**.  
This framework provides methods for testing **functionality logic** as well as **front-end validation**.  
Tests can be run **in parallel** to improve execution time and efficiency.

---

## 🧩 Prerequisites
- Python **3.x**
- Browsers supported:
  - Google Chrome  
  - Mozilla Firefox  

---

## ⚙️ Local Setup & Installation
1. **Create and activate virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate       # For macOS/Linux
   venv\Scripts\activate          # For Windows

2. Install project requirements
```
pip install -r requirements.txt
```

🧪 Execution
✅ Run all tests
```
pytest
```

🧾 Run one specific test
```
pytest tests/acceptance_tests.py::AcceptanceTests::test_fare_for_adult
```

⚡ Run all tests in parallel
```
pytest -vs -nauto
```
📂 Directory Structure
```
Selenium-PyTest-Automation-Framework/
│
├── tests/                # Test files
├── screenshots/          # Test failure screenshots
├── requirements.txt      # Dependencies
└── report.html           # HTML report (generated after test run)
```

📊 Reporting with Screenshots

Generate an HTML report with screenshots:
```
pytest --html=report.html
