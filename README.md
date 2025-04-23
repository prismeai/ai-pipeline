# 📩 Email Classification Workflow — DSUL Template for Prisme.ai

This repository contains a ready-to-import **workspace template** for **automated email classification** in the insurance domain, using the **DSUL (Digital Service Universal Language)** format powered by Prisme.ai.

The workflow uses AI agents, business rules, and system integrations to classify incoming emails, extract entities, and trigger automated downstream processes such as reimbursement or complaint management.

---

## 🧩 What’s Included

- `classify.yaml`: Main automation combining all DSUL agentic patterns:
  - Classification agent (LLM)
  - Named entity extraction agent (NER)
  - Business rule routing
  - Contextual analysis agent
  - Loop over historical tickets
  - API integration (fetch)
- `trigger-reimbursement.yaml`: Sub-automation to process reimbursement requests.
- Sample page/block/automation structure (optional).
- Agent and collection references are **modular and configurable**.

---

## 🚀 How to Use

### **Download the Workspace ZIP**

Export this repository as a `.zip` archive and upload it on your prisme.ai instance.
