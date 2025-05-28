# 🧠 Myke's AI & Healthtech Portfolio

Columbia-trained physician-scientist turned builder.

This space showcases my pivot into AI, healthtech, and systems strategy. I'm blending clinical expertise with real technical execution—from NLP for neuro consults to real-time triage intelligence and recovery forecasting.

## 🔧 Projects

### Triage AI
**Real-Time Medical Triage Engine with Gemini 2.0**

**Tech Stack:** Python · Gemini 2.0 Flash API · JSON-based Clinical Reasoning · Risk Stratification · Batch Processing · RESTful Architecture

**Description:** Triage AI is a lightning-fast clinical risk stratification engine that analyzes free-text clinical inputs—ED presentations, consult notes, EMS handoffs—and returns structured triage decisions in under 2 seconds. Built on Google's Gemini 2.0 Flash, it categorizes patients into EMERGENT/URGENT/SEMI_URGENT/ROUTINE levels with confidence scoring, red flag identification, and next-step clinical actions.

The system mimics expert emergency physician reasoning, extracts subtle clinical patterns, and provides explainable triage rationale. Safety-first design defaults to higher acuity on uncertainty. Handles batch processing for surge scenarios and outputs JSON for seamless EHR integration.

**Outcome:** Achieves 85%+ confidence on standard ED presentations. Processes complex clinical narratives in 1-2 seconds. Built for real-world deployment with color-coded urgency display, audit trails, and HIPAA-compliant architecture. Ready for pilot testing in triage departments and telemedicine platforms.

[→ View Triage AI Repo](https://github.com/neuron-cloud/triage-ai)

### Synapse v2.0
**Real-Time NLP Risk Flagging Engine for Neurosurgical Consults**

**Tech Stack:** Python · RegEx · NLP · Clinical Pattern Recognition · Contextual Negation · GPT Integration · OOP

**Description:** Synapse v2.0 is a real-time, neurosurgery-specific natural language processing engine designed to extract critical neurological findings from unstructured consult notes. Built for clinical decision support in high-acuity settings, it flags subtle red flags—motor weakness, sensory deficits, pathological reflexes, AMS, cauda equina signs—with structured severity grading and confidence scoring.

It mimics expert-level clinical reasoning, differentiates baseline vs acute deficits, and contextualizes negated findings using a custom-built engine of compiled regex patterns, medical abbreviation expansion, and pattern-aware negation logic.

**Outcome:** Validated on real neurosurgical consults with high sensitivity, low false positives. Replicates manual triage logic in less than 10ms per note. Deployed in Jupyter/Colab for live testing and physician-facing demonstrations. Designed for future expansion into EMR integration, JSON export, and specialty adaptation.

[→ View Synapse Repo](https://github.com/neuron-cloud/synapse-engine)

### NEURA
**Recovery Forecasting AI for Post-Treatment Clinical Care**

**Tech Stack:** Google Colab · GPT Integration · Prompt Chaining · Python · Clinical Risk Modeling

**Description:** NEURA predicts and supports patient recovery after surgery, hospitalization, or serious illness. From a single clinical note, it generates a structured recovery risk score (Cognitive, Emotional, Functional, Adherence, Social) and delivers emotionally intelligent journaling prompts and recovery guidance for patients. NEURA bridges the blind spot between "discharged" and "actually healing."

**Outcome:** Working prototype demo live in Colab. Open-sourced for pilots, partnerships, and feedback. Outputs explainable domain-level forecasts + Recovery OS patient support. Future plans include web deployment, structured PDF exports, and pilot testing with high-acuity clinical teams.

[→ View NEURA Repo](https://github.com/neuron-cloud/neura-recovery-score)

## 🎯 The Clinical AI Stack

My projects form a continuum of care intelligence:

1. **Triage AI** → Front door risk stratification (Who needs help NOW?)
2. **Synapse v2.0** → Specialty-specific pattern recognition (What exactly is wrong?)
3. **NEURA** → Post-discharge recovery intelligence (How do we get them home safe?)

Together, they represent a vision for AI that enhances every touchpoint of clinical care—from first contact to full recovery.

## 💬 Why This

Because clinical judgment deserves a second brain—and AI shouldn't stop at diagnosis.

I'm building tools I wish I had when the system went silent after discharge. Tools that think like a clinician *and* care like a human. Tools that flag the stroke in triage, catch the cauda equina in consults, and remember patients exist after they leave the hospital.

## 🚀 What's Next

- **Integration:** Working on unified API architecture to chain Triage → Synapse → NEURA
- **Pilots:** Seeking partnerships with EDs, telemedicine platforms, and health systems
- **Expansion:** Adapting engines for specialty-specific use cases (psych, peds, trauma)
- **Research:** Publishing validation studies on real-world clinical performance

## 📫 Connect

Building something similar? Have a use case? Let's talk.

[LinkedIn](https://www.linkedin.com/in/mychael-delgardo-a258a8357/) | [Email](mailto:mwdelgardo@gmail.com) | [GitHub](https://github.com/neuron-cloud)

---

*"The best time to plant a tree was 20 years ago. The second best time is now."*  
*The best time to augment clinical intelligence? Right now.*
