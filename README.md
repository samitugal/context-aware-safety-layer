 # Context-Aware PII Detection and Safe Masking Layer

## Overview

This open-source demo showcases a **context-aware approach to detecting and safely masking Personally Identifiable Information (PII)** in real-world text streams.  
The project is presented as part of *“From Risk to Reality: AI Risk Assessment for LLMs & Agents” (February 2026)* on  [Ritual Foundation](https://x.com/ritualfnd), [Elif Hilal Kara](https://x.com/elifhilalumucu) X, and YouTube Channels. and the webinar is designed to demonstrate how **AI governance, risk management, and practical AI safeguards** can be translated into an executable technical layer.

<img align="left" img width="480" height="480" alt="image" src="https://github.com/HUX-AI/context-aware-safety-layer/blob/main/HUXAI-Ritual.jpeg" />

---

## What this demo is

A **research and demonstration project** that implements a **context-aware PII detection and masking layer** for unstructured text (e.g. emails, invoices, logs, medical notes).

Unlike pattern-only approaches, this demo emphasises **understanding meaning and usage context** to make safer, more precise masking decisions.

---

## Why it exists

Real-world text streams often contain **hidden, mixed, or ambiguous PII**.  
Traditional rule-based or regex-driven approaches:

- Over-mask non-sensitive content (false positives)
- Under-mask sensitive identifiers (false negatives)
- Reduce the usability and structure of text

This demo exists to show how **context awareness** can bridge that gap, supporting:
- Privacy and compliance
- Safe use of data for analytics and AI
- Responsible AI deployment aligned with governance principles

---

## What problem does it demonstrates

- How to **detect PII using context**, not just surface patterns  
- How to **mask sensitive data while preserving meaning and usability**
- Why **context-aware decisions** matter for real AI systems operating under regulatory and ethical constraints

---

## Demo Scope & Capabilities

### What the demo does

- Identifies **Direct, Indirect, and Sensitive PII** in unstructured text
- Uses **context-aware reasoning** to distinguish ambiguous cases  
  (e.g. company names vs. personal names, random numbers vs. IDs)
- Applies **safe masking strategies** that:
  - Protect identity
  - Preserve text structure and downstream usability
- Demonstrates the difference between:
  - Context-aware PII detection
  - Default pattern-based PII detection (side-by-side examples)

### What the demo explicitly does *not* do

- ❌ It is **not a production-ready PII compliance tool**
- ❌ It does **not guarantee full regulatory compliance on its own**
- ❌ It does **not replace organisational governance, audits, or legal review**
- ❌ It does **not claim perfect detection accuracy**

(These aspects are intentionally out of scope and left for future work or production systems.)

---

## Conceptual Background

### PII and masking

Personally Identifiable Information (PII) is **any data that can identify an individual directly or indirectly**.  
Masking transforms sensitive information so that individuals cannot be identified while preserving the remaining text's usability.

**Design principle:**  
> *Mask enough to protect identity, preserve enough to keep the text useful.* 

### Why context awareness matters

Context awareness enables a system to understand **what information means based on where, how, and why it appears**, not just what it looks like.

This approach:
- Reduces false positives
- Prevents under-masking of sensitive data
- Preserves document structure
- Enables **risk-aware, document-specific decisions**

Context is the difference between **noise reduction** and **privacy protection**. 

---

## Architecture / Workflow (High-Level)

1. **Input text ingestion**  
   Unstructured text in natural language (e.g. Turkish or English)

2. **Context-aware PII analysis**  
   - Evaluates surrounding words, document structure, and semantic cues  
   - Differentiates ambiguous tokens based on usage

3. **PII classification**  
   - Direct PII  
   - Indirect PII  
   - Sensitive PII

4. **Safe masking layer**  
   - Applies appropriate masking strategies  
   - Preserves readability and analytical value

5. **Output text**  
   Masked text suitable for safer downstream use (analytics, AI pipelines, sharing)

*(Exact implementation details are intentionally abstracted in this demo.)* 

---

## Getting Started

### Prerequisites

To be added/clarified based on future updates.

### Installation

To be added/clarified based on future updates.

### Running the demo

To be added/clarified based on future updates.

---

## Open-Source & Research Context

This project is intended for:

- Research and experimentation
- Demonstrating AI risk mitigation techniques
- Community discussion around responsible AI design

It is **not intended for direct production deployment** without further engineering, validation, and governance integration.

---

## Limitations & Responsible Use

- Context-aware systems can still make mistakes
- PII detection is inherently probabilistic
- Masking strategies must be adapted to:
  - Legal requirements
  - Domain-specific risks
  - Organisational policies

Users are encouraged to:
- Treat outputs as **decision support**
- Combine with governance processes, audits, and human oversight
- Avoid misuse in high-stakes or sensitive deployments without safeguards

---

## Citation / Acknowledgement

This demo is based on the presentation:

**“From Risk to Reality: AI Risk Assessment for LLMs & Agents”**  
February 2026 on [Ritual Foundation](https://x.com/ritualfnd), [Elif Hilal Kara](https://x.com/elifhilalumucu) X, and YouTube Channels!

[Dr. Merve Ayyüce KIZRAK](https://www.linkedin.com/in/merve-ayyuce-kizrak/), [Enes Basbug](https://www.linkedin.com/in/enesbasbug/), [Hayriye Anıl](https://www.linkedin.com/in/hayriye-anil/), [Sami Tuğal](https://www.linkedin.com/in/samitugal/)

Developed in the context of HUX AI’s research on:
- AI governance
- Risk assessment
- Responsible and human-centred AI systems

For more context: https://huxai.tech/hux-research-hub/

---

<img align="left" img width="640" height="360" alt="image" src="https://github.com/HUX-AI/context-aware-safety-layer/blob/main/HUX_AI-Ritual.pptx.jpg" />




<img align="right" img width="196" height="282" alt="image" src="https://github.com/user-attachments/assets/cfd9f7a9-7563-4884-8eb0-48cc401e4d13" />

* Join the [Community](https://huxai.tech/community-charter/) of learners and stay ahead together!
* [Subscribe on Luma](https://luma.com/huxai?k=c) and stay tuned for our events!
* [Subscribe on LinkedIn](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7365810411406868483) our Newsletter!
* [Super Study Guide: Dönüştürücüler ve Büyük Dil Modeli](https://leanpub.com/donusturuculer-buyuk-dil-modelleri)

---

### Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

### Contact

For any questions or inquiries, please contact [Dr. Merve Ayyüce KIZRAK](https://www.linkedin.com/in/merve-ayyuce-kizrak/), [Enes Basbug](https://www.linkedin.com/in/enesbasbug/), [Hayriye Anıl](https://www.linkedin.com/in/hayriye-anil/), [Sami Tuğal](https://www.linkedin.com/in/samitugal/)

