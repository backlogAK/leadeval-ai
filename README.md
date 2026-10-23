# 🚀 LeadEval AI — Conversational Leadership Assessment Prototype

An interactive, AI-powered leadership assessment platform built for the **AI Product Builder** work sample submission at **atrain**.

🔗 **Live Interactive Demo:** https://backlogAK.github.io/leadeval-ai/  
📂 **Repository:** https://github.com/backlogAK/leadeval-ai

---

## 💡 Executive Summary

Traditional leadership assessments rely on static, multiple-choice questionnaires that test memory and corporate awareness rather than real-time behavioral decision-making under stress. 

**LeadEval AI** reimagines the assessment experience by placing managers inside high-stakes conversational business simulations (e.g., toxic team dynamics, production outages, ethical dilemmas). Instead of choosing from pre-written answers, candidates must generate their own responses from scratch, which an AI evaluator then scores dynamically across 5 core competencies in real time.

---

## 🛑 The Problem with Legacy Assessments

Current enterprise assessments (like traditional Situational Judgment Tests used by Amazon and others) suffer from fundamental flaws:
- **They are highly gameable:** Candidates can easily guess the "most corporate" multiple-choice answer.
- **They rely on self-reporting:** Asking "How well do you handle stress?" relies on flawed human self-evaluation.
- **They score linearly:** Choosing Option B might give +1 for Empathy and -1 for Strategy, missing the nuance of *how* a candidate communicates.
- **They are a "Black Box":** Candidates spend 45 minutes on a test and receive zero feedback or value in return.

## ✨ The LeadEval AI Paradigm Shift

| Feature | Legacy HR Assessments | LeadEval AI |
| :--- | :--- | :--- |
| **Format** | Forced Multiple-Choice (Evaluative) | Open-Ended Chat (Generative) |
| **Measurement** | Tests if you *know* the right answer | Observes what you *actually do* |
| **Environment** | Static Questionnaire | Immersive Behavioral Simulation |
| **Candidate Value** | Zero feedback ("Black Box") | Real-time visual coaching & Archetype mapping |
| **Scoring Engine** | Rigid, Linear Logic | Nuanced NLP & LLM Multi-Dimensional Scoring |

---

## 🛠️ Key Technical & Product Features

1. **Dual Evaluation Engine**:
   - **Direct Gemini API Integration:** Connects directly with Google's `gemini-3-flash-preview` model for detailed qualitative feedback and structural metric scoring.
   - **Offline Heuristic Engine:** A smart fallback NLP engine ensures the application functions seamlessly for demonstration even without an active API key.
2. **Real-Time Competency Analytics**:
   - Interactive **Chart.js Radar Chart** displaying live scoring for *Empathy*, *Decisiveness*, *Clarity*, *Strategic Thinking*, and *Adaptability*.
3. **Dynamic Archetype Computation**:
   - Real-time classification into actionable leadership archetypes (e.g., *Empathetic Strategist*, *Decisive Commander*, *Adaptive Facilitator*).
4. **Multi-Scenario Engine**:
   - 5 diverse situational exercises designed to stress-test different soft skills (Conflict Resolution, Crisis Management, Restructuring, Ethics).
5. **Executive Assessment Report**:
   - One-click generated executive summary modal with a print-to-PDF export function for HR review.

---

## 💻 Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Data Visualization:** Chart.js
- **AI Integration:** Google Gemini REST API (`gemini-3-flash-preview`)
- **Deployment:** GitHub Pages (Client-side architecture)

---

## 🚀 Quick Start / Local Setup

Because LeadEval AI is built as a self-contained, serverless web application, running it locally is instant:

1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)backlogAK/leadeval-ai.git
