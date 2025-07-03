# Email Threat Detector 🛡️📧

This project combines two approaches to email threat detection:

### 1. LLM-Based Email Classifier
Uses HuggingFace’s `facebook/bart-large-mnli` model to classify emails as:
- Phishing
- Spam
- Promotion
- Safe

### 2. Rule-Based Filter
A logic-based method that detects phishing or spam using custom keyword matching with Python and regex.

---

## 🔍 Project Purpose
To explore how both modern AI and traditional logic can be used to identify malicious emails — and to understand their strengths and limitations in a real-world security context.

---

## 🧠 Key Takeaways
- Compared LLM vs rule-based results on sample emails
- Observed where rule-based filters fail and LLMs succeed
- Understood threat classification workflows and model behavior

---

## 📂 Files
- `llm_email_classifier.ipynb` – LLM-based detection
- `rule_based_email_filter.ipynb` – Keyword-based detection
