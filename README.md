# 🏦 AI-Powered Loan Approval Automation using n8n

An end-to-end loan processing automation workflow built using **n8n**, **Google Sheets**, **JavaScript**, and **Gmail**. This project automates loan evaluation, risk classification, decision-making, record updates, and customer notifications without manual intervention.

---

## 🚀 Project Overview

Financial institutions receive numerous loan applications daily. Manually reviewing each application can be time-consuming and error-prone. This workflow automates the process by analyzing applicant data, assigning a risk level, updating records, and sending personalized email notifications.

The system classifies applicants into:

* 🟢 Low Risk → Approved
* 🟡 Medium Risk → Under Review
* 🔴 High Risk → Rejected

---

## 🛠️ Technologies Used

* **n8n** – Workflow Automation
* **Google Sheets** – Applicant Data Storage
* **JavaScript** – Risk Assessment Logic
* **Gmail** – Automated Email Notifications

---

## 📊 Workflow Architecture

![Workflow](screenshots/n8n-workflow.png)

### Workflow Steps

1. Read loan applicant data from Google Sheets.
2. Execute JavaScript-based risk assessment.
3. Classify applicants into Low, Medium, or High Risk.
4. Route records through conditional logic.
5. Update loan status in Google Sheets.
6. Send automated email notifications.

---

## 📋 Dataset Structure

![Dataset](screenshots/google-sheet.png)

The dataset contains important applicant details such as:

* Loan ID
* Applicant Name
* Credit Score
* Annual Income
* Loan Amount
* Debt-to-Income Ratio
* Residence Years
* Active Loans
* Credit Card Outstanding
* Previous Defaults
* Property Ownership
* Dependents
* Collateral Value
* FOIR Percentage
* Risk Level
* Loan Status

---

## 🟢 Low Risk – Loan Approved

![Loan Approved](screenshots/loan-approved.png)

### Approval Conditions

* Strong credit score
* Low debt obligations
* No previous defaults
* Good repayment capacity

### Automated Actions

* Loan status updated to **Approved**
* Applicant receives approval email
* Processing moves to documentation stage

---

## 🟡 Medium Risk – Under Review

![Loan Under Review](screenshots/loan-under-review.png)

### Review Conditions

* Moderate credit profile
* Additional verification required
* Borderline eligibility criteria

### Automated Actions

* Loan status updated to **Under Review**
* Review notification email sent
* Application escalated for manual assessment

---

## 🔴 High Risk – Loan Rejected

![Loan Rejected](screenshots/loan-rejected.png)

### Rejection Conditions

* Low credit score
* High debt burden
* Multiple risk indicators
* Insufficient repayment capacity

### Automated Actions

* Loan status updated to **Rejected**
* Rejection email sent automatically
* Improvement recommendations provided

---

## 📧 Email Automation

The workflow generates personalized email notifications for each loan decision category:

### Approval Email

* Loan approved confirmation
* Risk assessment summary
* Next processing steps

### Review Email

* Additional verification request
* Assessment status notification
* Pending review details

### Rejection Email

* Rejection notification
* Risk analysis summary
* Recommendations for future applications

---

## 💡 Business Benefits

* Reduces manual processing effort
* Improves decision consistency
* Faster application turnaround time
* Automated customer communication
* Scalable loan assessment process
* Enhanced operational efficiency

---

## 🔮 Future Enhancements

* Machine Learning-Based Credit Scoring
* Banking API Integration
* Real-Time Dashboard
* PDF Report Generation
* Customer Self-Service Portal
* Predictive Risk Analytics

---

## 📂 Repository Structure

```bash
├── screenshots
│   ├── n8n-workflow.png
│   ├── google-sheet.png
│   ├── loan-approved.png
│   ├── loan-under-review.png
│   └── loan-rejected.png
├── workflow.json
└── README.md
```

---

## 👨‍💻 Author

**Noor Singla**

MBA (Finance) | AI Automation & Workflow Enthusiast

---

⭐ If you found this project useful, please consider giving the repository a star.
