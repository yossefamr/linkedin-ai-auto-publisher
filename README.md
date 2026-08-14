# 🚀 LinkedIn AI Auto-Publisher Engine

An automated content creation and publishing pipeline built with **Activepieces**, **OpenRouter (Claude 3.5 Sonnet / OpenAI)**, and the **LinkedIn API**.

This system automates the schedule and delivery of professional LinkedIn posts, taking raw topics, drafts, or scheduled ideas, expanding them with AI into high-engaging posts, and publishing them directly to a LinkedIn profile or page.

---

## 🛠️ Tech Stack & Architecture

* **Orchestration Engine**: [Activepieces](https://www.activepieces.com/)
* **AI Generation**: [OpenRouter / Claude 3.5 Sonnet / OpenAI](https://openrouter.ai/)
* **Publishing Platform**: [LinkedIn API (OAuth 2.0)](https://developer.linkedin.com/)
* **Trigger / Scheduler**: Activepieces Schedule / Webhook / Notion Database

### 🔄 Data Flow
* **Schedule / Topic Trigger** ➔ *(Prompt / Draft)*
* **Activepieces Orchestrator**:
  1. **OpenRouter / AI Engine** *(Generates optimized, emoji-rich post text & formatting)*
  2. **LinkedIn API Action** *(Publishes post live to user feed)*

---

## 🎯 System Features & Capabilities

* **Automated Content Expansion**: Converts short ideas or scheduled prompts into complete, professional LinkedIn posts.
* **Direct Social Publishing**: Connects via official LinkedIn API to post automatically without manual intervention.
* **Engagement-Driven Formatting**: Uses AI prompts optimized for viral readability, hooks, bullet points, and hashtags.
* **Hands-Free Scheduling**: Runs on pre-set time intervals or triggers upon approving a draft.

---

## 📖 How to Use (طريقة الاستخدام)

1. **Set Up Schedule or Trigger**:
   * Define the scheduling interval (e.g., daily at 9 AM) or add a topic to your connected draft trigger.

2. **Automated AI Generation**:
   * Activepieces sends the topic to the LLM via OpenRouter to craft a polished post formatted specifically for LinkedIn.

3. **Live Auto-Publishing**:
   * The workflow pushes the finalized text directly to your LinkedIn profile via API.

---

## 🚀 Setup & Installation (خطوات الإعداد)

1. **LinkedIn Developer App**:
   * Create an app in the LinkedIn Developer Portal and obtain `Client ID` and `Client Secret` with `w_member_social` permissions.

2. **Import Workflow**:
   * Import the `workflow.json` into your Activepieces workspace.

3. **Configure Connections**:
   * Connect your **LinkedIn Account** via OAuth 2.0 and enter your **OpenRouter API Key**.

4. **Publish**:
   * Run a test post, verify it appears on your LinkedIn feed, then turn on **Publish**.

---

## ⚖️ Rights & License (حقوق الملكية والاستخدام)

* **Author**: Youssef Amr (جو)
* **Role**: Automation Specialist & Developer
* **License**: MIT License – Free to use, modify, and distribute with attribution to the original author.

---
© 2026 **Youssef Amr**. All rights reserved.
