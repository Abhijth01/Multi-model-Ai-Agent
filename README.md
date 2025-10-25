# Multi-model-Ai-Agent
🤖 A Gemini-powered Multi-Agent Research Assistant that plans, searches, and synthesizes information into detailed research reports with TL;DR summaries.

# Gemini Multi-Agent Research Assistant

A multi-agent AI system built with **Google’s Gemini API** that autonomously performs **end-to-end research** on any user-provided topic.  
The system intelligently **plans research questions**, **retrieves web data**, and **synthesizes** a structured final report — complete with a concise **TL;DR summary**.

---

## 🚀 Features

- 🧠 **Planner Agent:** Generates structured, sub-topic research questions.
- 🔎 **Search Agent:** Gathers contextual information from online sources.
- 🧩 **Synthesizer Agent:** Writes detailed and coherent research reports.
- 🪄 **Orchestrator:** Coordinates all agents in a smooth research pipeline.
- ⚡ **Gemini Integration:** Uses `gemini-1.5-flash` (or `gemini-2.0-flash`) for fast, intelligent responses.
- 📄 **Final Report with TL;DR:** Includes a concise summary for quick insights.

---

## 🧬 System Architecture

+------------------------+
| User Input Topic |
+-----------+------------+
|
v
+-----------+------------+
| Planner Agent |
| (Generates questions) |
+-----------+------------+
|
v
+-----------+------------+
| Search Agent |
| (Retrieves insights) |
+-----------+------------+
|
v
+-----------+------------+
| Synthesizer Agent |
| (Creates report) |
+-----------+------------+
|
v
+-----------+------------+
| Final Output (Report) |
+-------------------------+

