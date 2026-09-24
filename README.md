# 🤖 AI Automation Workflows by @rajgirase

Welcome to my personal collection of powerful AI-driven automation workflows built using **n8n**, **OpenAI**, **LangChain**, and various integrations like **Telegram**, **ClickUp**, **Google Sheets**, and **Gmail**.

Each JSON file in this repo represents a plug-and-play workflow that solves a specific business problem through intelligent automation.

---

## 📂 Workflow List

| File | Description |
|------|-------------|
| `CRM_automation.json` | Automates lead intake, qualification, and CRM population using AI-generated insights. |
| `Calender_ScheduleEvent.json` | Smart calendar event scheduling agent powered by GPT-4 and Google Calendar API. |
| `Expert_Candidate_Relevancy_Scoring_System (1).json` | Matches candidates with domain experts using role-tool-experience-based scoring. Ideal for DRDO or R&D hiring. |
| `HR_telegram_chat.json` | HR assistant chatbot integrated with Telegram to evaluate resumes and manage communication. |
| `Linkdin_Scraper.json` | Scrapes LinkedIn-like data from Apollo.io using dynamic search criteria, then appends it to Google Sheets. |
| `Research_Agent.json` | An AI research agent that gathers domain-specific insights and formats them for decision-making. |
| `Resume_Parsing_with_Clickup_integration.json` | Parses resumes, scores candidates via GPT, and updates status and custom fields in ClickUp. |
| `Sub_workflow_1_for_Gmail_with_hr.json` | Sub-workflow that sends HR-related emails to candidates based on JSON data structure. |
| `clickup_workflow_for_HR.json` | End-to-end workflow to manage HR processes inside ClickUp—task creation, status updates, and tagging. |

---

## 🧠 Tech Stack

- **n8n**: Workflow automation
- **OpenAI GPT-4o / GPT-4-mini**: Language processing & smart logic
- **LangChain**: AI agent orchestration
- **Google APIs**: Sheets, Calendar, Gmail
- **ClickUp API**: Task management and HR pipeline automation
- **Telegram API**: Chatbot integration
- **Apify + Apollo.io**: Web scraping and lead generation

---

## 🛠️ How to Use

1. **Import workflows** into your n8n instance (drag and drop JSON).
2. Set up necessary credentials: OpenAI, Google, Telegram, ClickUp, etc.
3. Customize any prompt logic or data mapping nodes.
4. Test using mock input or connected systems.
5. Deploy with webhook/chat triggers as needed.

---

> 🚀 _Let's automate the future, one AI agent at a time._