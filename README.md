🏦 AI-Powered Loan Approval Automation using n8n
📌 Project Overview

This project is an AI-Powered Loan Approval Automation System built using n8n, Google Sheets, and Gmail. The workflow automatically evaluates loan applications, classifies applicants into Low Risk, Medium Risk, or High Risk categories, updates the decision in Google Sheets, and sends personalized email notifications to applicants.

The system simulates a real-world banking loan approval process by analyzing applicant financial data and making automated decisions based on predefined risk assessment rules.

🚀 Features

✅ Automated Loan Risk Assessment

✅ Classification into:

Low Risk → Loan Approved
Medium Risk → Under Review
High Risk → Loan Rejected

✅ Real-time Google Sheets Integration

✅ Automated Gmail Notifications

✅ Dynamic Decision-Based Routing

✅ No-Code Workflow Automation using n8n

🛠️ Tech Stack
n8n – Workflow Automation
Google Sheets – Loan Applicant Database
Gmail API – Automated Email Notifications
JavaScript (Code Node) – Risk Calculation Logic
📊 Dataset Attributes

The loan dataset contains applicant information such as:

Loan ID
Applicant Name
Credit Score
Annual Income
Loan Amount
Debt-to-Income Ratio
Residence Years
Active Loans
Credit Card Outstanding
Previous Defaults
Bank Account Age
Property Ownership
Dependents
Collateral Value
FOIR Percentage
Risk Level
Loan Status
🔄 Workflow Process
Step 1: Read Loan Applications

The workflow fetches applicant records from Google Sheets.

Step 2: Risk Assessment

A JavaScript Code Node evaluates applicant financial data and calculates risk levels.

Step 3: Decision Routing
🟢 Low Risk
Loan Approved
Status updated in Google Sheets
Approval email sent automatically
🟡 Medium Risk
Loan marked "Under Review"
Requires manual verification
Review notification email sent
🔴 High Risk
Loan Rejected
Rejection reason generated
Rejection email sent automatically
Step 4: Update Records

The final loan decision is written back to Google Sheets.

Step 5: Send Email Notification

Applicants receive personalized email notifications based on their loan status.

📧 Automated Email Templates
🟢 Loan Approved
Credit profile verified
Low risk classification
Eligible for automatic approval
Documentation process initiated
🟡 Loan Under Review
Additional verification required
Manual assessment needed
Income and credit profile review pending
🔴 Loan Rejected
High-risk applicant detected
Credit score below threshold
Repayment capacity insufficient
Recommended improvement actions provided
📸 Project Screenshots
Workflow Architecture

Google Sheets Dataset

Loan Approved Email

Loan Under Review Email

Loan Rejected Email

🎯 Business Benefits
Reduces manual loan processing effort
Improves decision consistency
Accelerates approval turnaround time
Enhances customer communication
Supports scalable loan operations
📈 Future Enhancements
Machine Learning-based Credit Scoring
Integration with Banking APIs
PDF Loan Approval Reports
Dashboard & Analytics
Real-Time Applicant Portal
👨‍💻 Author

Noor Singla
MBA (Finance) | AI Automation & Workflow Enthusiast
