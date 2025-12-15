# 🚀 n8n AI Automation Collection

![n8n](https://img.shields.io/badge/Workflow-n8n-ff6d5a?style=for-the-badge&logo=n8n)
![AI](https://img.shields.io/badge/AI-Powered-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge)

This repository contains a collection of advanced **n8n workflows** designed to demonstrate the power of AI in business automation and content creation. Each `.json` file represents a standalone, fully functional project ready to be imported.

---

## 📂 Project List

| File Name | Category | Integrations |
| :--- | :--- | :--- |
| **1_Hotel_Bookings_Automation_Agent.json** | 🏨 AI Agent / Support | OpenAI, Airtable, GSheets, WhatsApp |
| **2_Viral_ASMR_Automation.json** | 🧠 Content Creation | OpenAI, Fal.ai (Video/Audio) |
| **3_AI_Automation_Factory_Tech_Future.json** | 📺 YouTube Automation | OpenAI, Replicate, Creatomate |

---

### 1️⃣ Hotel Bookings Automation Agent
**Type:** `Customer Support AI Agent`

An intelligent virtual assistant for WhatsApp/Messenger, capable of managing hotel reservations through natural conversation. It goes beyond a simple chatbot by using an **AI Agent with Tools** (Function Calling).

*   ✅ **Natural Language Processing:** Understands complex user requests.
*   ✅ **Price Check:** Queries a Google Sheet for real-time room rates.
*   ✅ **Availability Check:** Searches Airtable records to see if rooms are free.
*   ✅ **Booking Management:** Can create new reservations or modify existing ones directly in the database.

---

### 2️⃣ Viral ASMR Automation
**Type:** `Social Media Content Generator`

An automated generator for ASMR and "Satisfying Loop" videos, optimized for viral growth on TikTok, Instagram Reels, and YouTube Shorts.

*   ✅ **Brainstorming:** OpenAI generates relaxing visual concepts (e.g., soap cutting, kinetic sand).
*   ✅ **Video Generation:** Uses **Fal.ai (Fast SVD)** to create fluid, hyper-realistic animations.
*   ✅ **Audio Generation:** Uses **Fal.ai (MMAudio)** to generate matching ASMR sounds.
*   ✅ **Distribution:** Pre-configured nodes for social media upload.

---

### 3️⃣ AI Automation Factory (Tech & Future)
**Type:** `Faceless YouTube Channel Automation`

A fully automated "Content Factory" for a Tech/Cyberpunk niche YouTube channel. The system autonomously decides the content type and produces it from scratch.

*   ✅ **Smart Routing:** Daily decision logic to produce either Shorts, Mid-form Docs, or Long-form Ambience.
*   ✅ **Scripting:** OpenAI (GPT-4o) writes viral "Infinite Loop" scripts.
*   ✅ **Visuals:** Generates abstract 3D animations (Cyberpunk, Neural Networks) using **Replicate/Luma**.
*   ✅ **Editing:** Automatically assembles the video, voiceover, and dynamic subtitles using **Creatomate**.

---

## 🛠️ How to Use

1.  **Download:** Save the `.json` file of the project you want to use.
2.  **Import:** Open your [n8n](https://n8n.io/) instance, go to the top-right menu, and select **"Import from file"** (or paste the code from Clipboard).
3.  **Credentials:** You will see nodes marked with a red warning ⚠️. You must add your own API keys for the services used (OpenAI, Replicate, Airtable, etc.).
4.  **Activate:** Turn on the workflow!

### ⚠️ Note on Costs
These workflows utilize generative AI services (OpenAI, Fal.ai, Replicate, Creatomate) which charge per usage (API costs). Please ensure you have sufficient credits in your respective accounts before running these workflows in a loop.

---
*Created with ❤️ using n8n*