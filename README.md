# FinanceFirst
A hierarchical multi-agent AI system that simulates end-to-end personal loan sales, verification, underwriting, and sanction letter generation through a human-like conversational chatbot. Built for EY Techathon 6.0.

Agentic Loan Orchestrator

A multi-agent, AI-powered conversational system that completes the full personal loan journey — from chat to sanction.

📌 Overview

Agentic Loan Orchestrator is a hierarchical multi-agent AI system designed for NBFCs and digital lenders.
It replaces static chatbots and manual verification steps with a human-like, intelligent loan sales and fulfillment process.

This project simulates the complete journey:

Landing → Sales Conversation → Verification → Underwriting → Sanction Letter

Everything happens inside a single seamless chat.

This solution was built as part of EY Techathon 6.0.

🚀 Key Features
✔ Master Agent (MA)

Human-like conversation

Context handling

Orchestrates all worker agents

✔ Worker Agents
1. Sales Agent

Captures loan need

Suggests best offer

Handles tenure, EMI, interest negotiation

2. Verification Agent

Simulated KYC

Aadhaar/PAN pattern check

Mock OTP flow

3. Underwriting Agent

Generates random credit score (650–850)

Applies predefined business rules:

Score ≥ 720 → Approve

650–719 → Conditional approval

<650 → Reject

4. Sanction Letter Agent
Generates a PDF with:

Customer Name

Loan Amount

Tenure

Interest Rate

EMI

Approval Conditions
