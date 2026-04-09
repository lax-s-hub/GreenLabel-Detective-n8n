# 🕵️‍♂️ GreenLabel Detective: AI-Powered ESG Auditor

**Unmasking Greenwashing with Agentic Workflows & Computer Vision.**

---

## 🌟 Project Overview
GreenLabel Detective is an automated AI agent designed to empower consumers. By simply scanning a product label via Telegram, the bot deciphers complex chemical jargon, detects deceptive greenwashing tactics, and assigns an accurate **Eco-Score (A-F)**.

Built during the **IBM SkillsBuild 2026** program, this project bridges the gap between corporate sustainability data and everyday consumer decisions.

## 🚀 Key Features
- **Instant Ingredient Analysis:** Automatically extracts and simplifies complex chemical names using Google Gemini 1.5 Flash.
- **Greenwashing Detection:** Identifies misleading visual cues (earthy tones, fake nature imagery) and unsubstantiated buzzwords.
- **Standardized Eco-Score:** Provides an easy-to-understand rating system based on environmental impact.
- **Seamless Interface:** Accessible 24/7 via a lightweight Telegram Bot.

## 🛠️ Tech Stack
- **AI Engine:** Google Gemini 1.5 Flash (Vision & Reasoning)
- **Automation:** n8n (Agentic Workflow Orchestration)
- **Interface:** Telegram Bot API
- **Deployment:** n8n Cloud / Webhooks

## 🏗️ How it Works (The Workflow)
1. **Trigger:** User sends a product label image to the Telegram Bot.
2. **Processing:** n8n catches the webhook and passes the binary image data to the AI Agent.
3. **Reasoning:** The Gemini-powered agent analyzes the text and visual elements for ESG compliance.
4. **Output:** The agent sends a structured report back to the user with the final Eco-Score.

## 📂 Repository Contents
- [GreenLabelDetective.json](./GreenLabelDetective.json) - Full n8n workflow export.
- [Concept Note](./ConceptNote- GreenLabel Detective.pdf) - Detailed project documentation.
- [Lean Canvas](./What gaps are we addressing for our customers.pdf) - Business model and strategy.

---
**Developed by:** [Laxmi Sidral](https://github.com/lax-s-hub)  
**Program:** IBM SkillsBuild 2026
