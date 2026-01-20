# TOPSIS-Task3-WebApp-102303113
# TOPSIS Task 3 (Web Application)

## Objective
Create a web-based TOPSIS service where users can:
- Upload a CSV file
- Enter weights and impacts
- Enter email ID
- Receive the output CSV on email

---

## Tech Stack
- Flask (Python)
- Pandas, NumPy
- SMTP (Gmail) for sending email

---

## Features
✅ Upload CSV input file  
✅ Validate weights and impacts  
✅ Run TOPSIS on server  
✅ Generate `output.csv`  
✅ Send output to user email  

---

## Input Rules
- CSV must have at least 3 columns
- First column: Alternative name/ID
- Remaining columns: Numeric criteria values only
- Weights: comma-separated numbers
- Impacts: comma-separated (+ or - only)

---

## How to Run Locally
### Install Dependencies
```bash
pip install -r requirements.txt
