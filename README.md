# 🩺 Agentic AI Health Symptom Checker (IBM Cloud )

This project is a **AI agent** built on **IBM Watsonx.ai** using **Granite/Mistral foundation models** and **trusted health documents**. It simulates an **educational AI health assistant** that helps users understand symptoms and get general wellness advice without medical diagnosis.

---

## ✅ Features

- 🧠 Accepts **natural language input** (e.g., “I have a sore throat and fever”)
- 🦠 Suggests **possible causes** from verified sources (like WHO, CDC)
- ⚠️ Classifies **urgency level** (Low / Moderate / High)
- 💡 Recommends **home remedies and preventive care**
- 📚 Uses real health documents (uploaded as **vector index**)
- 🌍 Optional: **Multi-language interaction** with IBM Translator
- 🚫 No self-diagnosis — provides **educational guidance only**
- 🛠 Built **100% on IBM Cloud Lite plan**, without writing code

---

## 🧱 Technology Stack

| Component           | Service Used                     |
|---------------------|----------------------------------|
| Agentic AI Core     | IBM Watsonx.ai Studio            |
| Foundation Model    | Granite-13B-chat / Mistral-large |
| Document Retrieval  | Vector Index (Watsonx Knowledge) |
| Multi-language      | IBM Language Translator (optional) |
| No-code UI          | Watsonx Agent                    |
| Deployment          | Watsonx Deployment Space         |

---

## 🚀 How It Works (User Flow)

1. User inputs symptoms in plain language
2. Agent retrieves info from uploaded health documents (PDFs)
3. Granite or Mistral model generates structured response:
   - Possible cause(s)
   - Urgency level
   - Advice and when to consult a doctor
4. Agent replies with **safe, educational**, and **non-diagnostic** information

---

## 📄 Trusted Health PDFs Used

These documents were uploaded and indexed:

- [CDC: Common Cold Fact Sheet (PDF, 4 pages)](https://www.cdc.gov/common-cold/media/pdfs/2024/04/CommonCold_fact_sheet_508.pdf)
- [CDC: Viral Illness Relief (PDF, 1 page)](https://www.cdc.gov/antibiotic-use/media/pdfs/RCx-Relief-Viral-Illness-sm-v8-508.pdf)
- [CDC: Measles Symptoms (PDF, 1 page)](https://www.cdc.gov/hearher/docs/pdf/CDC-Hear-Her-Womens-urgent-warning-signs-h.pdf)

> These documents are used only for **retrieval-based educational response** generation.

---

## 🧾 Agent Instructions

```plaintext
You are a responsible AI health assistant. You help users understand symptoms by:
- Suggesting possible causes
- Estimating urgency (low/moderate/high)
- Giving safe, general care advice
- Recommending when to consult a doctor

You only use public health sources (WHO, CDC). Do not diagnose. Add: "⚠️ This is not medical advice."

```

💬 Sample Questions Users Can Ask
“I have a sore throat and a headache. What could be the cause?”

“I feel dizzy and tired. Should I be worried?”

“When should I go to the doctor for a fever?”

“What are some home remedies for flu?”

“How do I know if I have heat stroke?”

🎯 Project Goal
To empower users with early symptom awareness using trusted public health guidance, while avoiding misdiagnosis and misinformation.
Built for health awareness, not clinical decision-making.

⚠️ Disclaimer
This agent is for educational and informational purposes only. It does not provide medical advice, diagnosis, or treatment. Always consult a qualified healthcare provider for medical concerns.

📌 Challenge Alignment
✅ Matches all key requirements of Problem Statement #28 – Agentic AI Health Symptom Checker:

IBM Cloud only (Lite plan)

Uses Watsonx + Foundation Models

Natural language input/output

Uses real medical documents (PDFs)

Provides care guidance, urgency level, referral advice

👨‍💻 Built By
Purvi Porwal 
Rajasthan Technical University
purviporwal46@gmail.com

