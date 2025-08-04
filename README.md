
#  ClauseLens: Clause-Level Legal Contract Analyzer

**ClauseLens** is an AI-powered tool that detects and analyzes key legal clauses in contracts using NLP and local LLMs. It helps legal professionals quickly identify risks, ambiguities, and imbalances — all with **100% offline, private inference**.

> No data leaves your machine — runs entirely locally.



##  Key Features

- **Detects 8+ Legal Clauses**
  `CONFIDENTIALITY`, `TERMINATION`, `NON_COMPETE`, `LIABILITY`, `FORCE_MAJEURE`, `PAYMENT_TERMS`, and more.
-  **Local LLM Analysis**
  Powered by **TinyLlama-1.1B** via `llama.cpp` — no cloud API, no data leakage.
-  **Privacy-First Design**
  Runs 100% offline after setup — ideal for sensitive legal documents.
-  **PDF & DOCX Support**
  Extracts text from both formats using `PyMuPDF` and `python-docx`.
-  **Exportable Reports**
  Download results as **JSON** or **PDF** for sharing and review.
-  **Gradio Web Interface**
  Clean, interactive UI for easy use.

---

##  How It Works

1. **Upload**: User uploads a PDF or DOCX contract.
2. **Parse**: Text is extracted using `PyMuPDF` / `python-docx`.
3. **Detect**: spaCy's `Matcher` identifies clause keywords.
4. **Analyze**: Local LLM (TinyLlama) reviews each clause for risk, fairness, and suggestions.
5. **Report**: Results are displayed and exported as JSON/PDF.
