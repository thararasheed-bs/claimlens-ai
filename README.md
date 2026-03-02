# claimlens-ai
### Smart Health Insurance Claim Advisor  

**Team:** Thara  

---

## 🩺 Problem Statement

Health insurance policies are complex, difficult to interpret, and often misunderstood.  
Policyholders struggle to:

- Understand coverage before surgery  
- Estimate eligible claim amount after hospitalization  
- Identify exclusions, co-pays, and deductibles  
- Avoid unexpected out-of-pocket expenses  

This leads to financial stress, claim rejection risk, and lack of transparency.

---

## 💡 Solution Overview

**ClaimLens AI** is a document-intelligent advisory platform that provides clarity at two critical stages:

### 1️⃣ Policy Analysis (Before Surgery)

Users upload their insurance policy PDF.  
The system:

- Extracts key financial parameters
- Identifies inclusions & exclusions
- Highlights waiting periods
- Surfaces co-payment & deductible clauses
- Displays structured dashboard insights

---

### 2️⃣ Claim Assessment (After Surgery)

Users upload:

- Insurance policy
- Hospital discharge summary
- Hospital bills

The system:

- Estimates eligible insurance coverage amount
- Calculates expected out-of-pocket expense
- Flags potential claim risks
- Identifies required documentation for submission

---

## 🧠 Compound Engineering Architecture

ClaimLens AI follows a **layered compound engineering model**, where each system layer enhances the intelligence and automation of the previous one.

### 🔹 Layer 1 – Presentation Layer
Built using Lovable  
Provides intuitive document upload and dashboard visualization

### 🔹 Layer 2 – Workflow Orchestration Layer
Powered by n8n  
Handles:
- Webhook triggers
- PDF parsing
- Data extraction
- Business rule processing
- AI invocation

### 🔹 Layer 3 – AI Intelligence Layer
Processes:
- Policy clauses
- Claim eligibility estimation
- Risk detection logic
- Structured JSON output

### 🔹 Layer 4 – Engineering Governance Layer
Managed using GitHub and the EveryInc Compound Engineering Plugin  
Enables:
- Structured feature planning
- AI-assisted workflow design
- Iterative architectural improvement
- Compound development methodology

This modular approach ensures scalability, extensibility, and event-driven automation.

---

## ⚙️ Tech Stack

- Lovable – Frontend Interface
- n8n (Cloud) – Workflow Automation & Processing Engine
- GitHub – Version Control & Engineering Governance
- EveryInc Compound Engineering Plugin – AI-assisted engineering workflow methodology

---

## 🔄 System Flow

User Upload  
→ Lovable Frontend  
→ n8n Webhook Trigger  
→ PDF Parsing & AI Processing  
→ Structured JSON Response  
→ Dashboard Visualization  

Optional DevOps Events  
→ GitHub Issues & Workflow Planning  

---

## 🚀 Current Development Status

- n8n workflow restored and active
- Webhook-based architecture implemented
- Frontend reconnection in progress
- Compound Engineering Plugin integrated for structured development

---

## 📈 Future Enhancements

- Persistent claim history tracking
- Real-time insurer integration APIs
- Risk scoring engine
- Secure document vault
- Predictive claim rejection detection

---

## 🎯 Vision

ClaimLens AI aims to reduce uncertainty in healthcare financing by combining:

- Document intelligence
- Workflow automation
- AI-driven advisory logic
- Compound engineering methodology

Each engineering iteration compounds future system intelligence and maintainability.
