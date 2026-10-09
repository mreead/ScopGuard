<div align="center">
  <img src="image_6c6105.png" alt="ScopeGuard AI Logo" width="250"/>[cite: 1]

  # 🛡️ ScopeGuard AI (V3 Final Demo)
  
  **The NeuroBridge Standard** | *Starnest Academy AI Hackathon - Top 3 Finalist*

  [![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
  [![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)](https://streamlit.io/)
  [![AI Processing](https://img.shields.io/badge/AI-Zero_Data_Retention-success.svg)]()
  [![Status](https://img.shields.io/badge/Status-V3_Final_Release-brightgreen.svg)]()

  > *An impenetrable, production-ready AI workflow designed to eliminate LLM hallucinations, handle edge cases, and give human Project Managers absolute technical authority.*
</div>

---

## 🚀 Overview

**ScopeGuard AI** is an elite Project Management and Statement of Work (SOW) analysis tool. Evolving from our highly-rated V2 architecture (Score: 91-95), the **V3 Final Demo** introduces critical, enterprise-grade safety patches. We have fundamentally separated probabilistic AI reasoning from deterministic logic, creating a "Human-in-the-loop" pricing and tri-state classification system that is immune to standard AI vulnerabilities.

## 🔑 Key Features (The V3 Patch)

### 1. Deterministic Citation Verification (The Anti-Hallucination Lock)
LLMs cannot be blindly trusted to "quote verbatim." V3 introduces a hard-coded Python validation layer:
```python
# Core Validation Logic
if extracted_quote not in raw_sow_text:
    raise VerificationError("Citation not found in source document")# ScopGuard

2. The 4th State: The "Silent SOW" Fallback
What happens when a client asks for a feature completely unmentioned in the SOW (e.g., Blockchain integration on a standard web app)?
ScopeGuard AI is explicitly trained to recognize the absence of evidence. It triggers the 4th state:

⚪ UNADDRESSED IN SOW

System Output: "No clauses found regarding [Topic]. Defaulting to Out-of-Scope as per standard exclusion rules."

3. Fully Editable Task Architecture (Absolute Human Override)
The AI analyzes intent and suggests technical implementations. However, these suggestions are strictly rendered as editable text fields in the Streamlit UI.

The PM is the final authority: Before logging hours, PMs can rewrite, delete, or add tasks to match their specific agency tech stack (e.g., overwriting generic "Build Auth" with "Enable Clerk SSO integration").

4. Enterprise Privacy Shield
Built from the ground up using Zero-Data Retention commercial APIs.

Prompts are never used for model training.

Documents are processed purely in-memory during the active session and are securely purged immediately upon closure.

⚙️ Technical Architecture
Frontend: Streamlit (Dynamic state management, editable task UI)

Backend/Logic: Python (Hard-coded string matching, deterministic verification)

AI Integration: Enterprise LLM endpoints (Zero-data retention policy)

Workflow: Human-in-the-loop (HITL) approval gates

# 1. Clone the repository
git clone [https://github.com/yourusername/ScopeGuard-AI.git](https://github.com/yourusername/ScopeGuard-AI.git)

# 2. Navigate to the project directory
cd ScopeGuard-AI

# 3. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the Streamlit application
streamlit run app.py

🎯 The Hackathon Verdict
The V3 architecture was specifically built to survive the "Devil's Advocate" stress test. By demonstrating the Hard-coded String Match Validation catching a forced hallucination in real-time, ScopeGuard proves it is not just an AI wrapper, but a structurally sound, enterprise-ready software solution.
