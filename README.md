# 🛡️ DataGuardian: AI-Powered Privacy Coach

A minimal, scenario-driven privacy assistant built with Claude 3.5 prompts. DataGuardian helps users assess digital risks, understand privacy threats, and take safer actions — all through mapped, modular AI coaching.

---

## 🔗 Live Demo  
Try the app here:  
https://partyrock.aws/u/prithika/1IfgddUWL/DataGuardian%253A-AI-Powered-Privacy-Coach

---

## 🧠 Powered by  
- Claude 3.5 Sonnet (`bedrock-anthropic.claude-3-5-sonnet-v2-0`)  
- Zero temperature for consistent, mapped output  
- Modular widget layout with prompt-driven logic

---

## 🧩 Modules

| Widget Title         | Functionality                                                                 |
|----------------------|-------------------------------------------------------------------------------|
| **Static Text**       | Intro message: “Worried about your digital footprint?”                       |
| **Your Privacy Scenario** | Text input for describing a concern or situation                          |
| **Risk Detector**     | Categorizes risk (e.g. Phishing, Data Leak, Over-Sharing) + short reason     |
| **Ask DataGuardian**  | Friendly, actionable advice with checklist-style guidance                    |
| **Privacy Risk Badge**| Returns a visual badge (Low 🟢, Medium 🟡, High 🔴) based on risk level        |

---

## 📦 Layout File  
The full widget configuration is stored in [`layout.json`](./layout.json).  
Includes:
- Widget coordinates and dimensions  
- Prompt logic for each module  
- Claude model parameters

---

## 🖼️ Screenshots  
See `/screenshots` for UI previews:
- `interface-1.png`: Full layout view  
- `interface-2.png`: Module breakdown

---

## 🚀 Use Cases  
- Privacy education  
- Scenario-based coaching  
- Cybersecurity awareness  
- Portfolio demonstration of AI prompt engineering

---

## 🧭 Mapped Workflow  
This project follows a mapped, modular design:
- Input → Risk Categorization → Advice → Badge  
- Each module runs independently and returns deterministic output  
- Ideal for showcasing prompt clarity and AI coaching logic

---



