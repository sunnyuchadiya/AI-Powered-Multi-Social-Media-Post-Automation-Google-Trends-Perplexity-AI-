# AI-Powered-Multi-Social-Media-Post-Automation-Google-Trends-Perplexity-AI 
The workflow monitors selected Instagram accounts via Apify, fetches recent Reels, analyzes engagement to detect early viral content, translates captions if needed, and stores structured results in Notion. Ideal for tracking trends, centralizing insights, and streamlining content planning.

Okay Sunny, main tumhare diye huye content ko ek **professional GitHub README / LinkedIn-ready format** me polish karke deta hoon, taaki presentation top-notch lage.

---

# 📌 Instagram Reels Hot Content Tracker

## 📺 **How It Works**

This n8n-powered workflow automatically monitors selected Instagram accounts via **Apify**, fetches their latest Reels, and analyzes performance in real-time.

It:

* Calculates engagement levels
* Detects early “new” content trends
* Translates captions when required
* Stores results in a **structured Notion database** — ready for review and production

---

## 📄 **Download Notion Database Structure**

Download the pre-configured Notion table structure (with all required columns and formats) here:
👉 [Notion Template](https://drive.google.com/file/d/1FVaS_-ztp6PDAJbETUb1dkg8IqE4qHqp/view?usp=sharing)

---

## 👤 **Who’s It For**

Ideal for:

* Marketers
* Content creators
* Social media managers
* Automation enthusiasts

Perfect for anyone who wants to **stay ahead of Instagram Reels trends**, streamline competitive analysis, or build an efficient content pipeline without manual tracking.

---

## 🔧 **Setup Guide**

1. Create the Notion database using the provided structure.
2. Import the `.json` workflow into your **n8n** instance.
3. Set up credentials for **Notion**, **Apify**, and **Gemini API**.
4. Link credentials in the workflow.
5. Update the **Variables** node with your test account list & settings.
6. Run with 3–5 profiles for validation.
7. Replace with full configuration once tested.

---

## 📋 **Requirements**

* n8n instance (self-hosted or cloud)
* Notion account (recommended: separate workspace)
* Apify account (usage-based pricing)
* Gemini API key (usage-based pricing)

---

## 🧩 **Customization**

* **Set Prompt node** → Define custom rules for content categories/video types
* **Adjust video filters** → Decide what counts as “hot” or “early hot”
* Modify Notion fields for your workflow
* Add more parsing logic in **Variables**
* Change translation target language
* Integrate with your content production pipeline


