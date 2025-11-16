🚀 GenAI Ops Automation Platform (Support + Finance)
AI workflow automation for Customer Support Triage & Invoice/Spend Intelligence
This repository contains an end-to-end GenAI automation platform built with n8n + Google Gemini + Pinecone + OCR + Sheets API to streamline customer support and finance operations, enabling businesses to scale without increasing headcount and make faster, data-backed decisions.


✨ Key Outcomes
Capability	Impact
LLM-based support triage & responses	Reduced manual workload ~80%
Invoice OCR + LLM field extraction	~95% accuracy across 9+ fields
Spend insights & due-invoice alerts	60–75% faster reconciliation cycles
ChatOps finance queries	Queries like: “Spend last 30 days?”
🧠 Platform Overview
The platform automates two critical business workflows:
1) 🤖 Customer Support Triage Engine
Auto-classifies emails into 5 support categories
Generates policy-grounded, context-aware replies using RAG
Escalates only high-priority cases with full context
Logs all interactions into Sheets / CRM
2) 📄 Invoice Intelligence & Spend Analytics
Extracts vendor, amount, dates, taxes, cost category & more
Auto-syncs structured data into Sheets/Data Warehouse
Generates weekly spend analytics and due-payment alerts
ChatOps answers queries like:
“Invoices above ₹50,000 due this week?”


🧩 Architecture (High-Level)
Gmail/Drive Triggers
        ↓
n8n Workflow Orchestration
        ↓
LLM Processing (Google Gemini)
        ↓
RAG Retrieval (Pinecone Vector DB)
        ↓
OCR / Document Parsing
        ↓
Sheets API / Data Warehouse Sync
        ↓
Ops Dashboards / ChatOps Layer


🛠 Tech Stack
Category	Tools
LLM / Reasoning	Google Gemini
Vector DB / RAG	Pinecone
Automation Engine	n8n
Document Parsing	OCR / Drive
Storage / Analytics	Google Sheets API, SQL
Scripting	JavaScript Functions
