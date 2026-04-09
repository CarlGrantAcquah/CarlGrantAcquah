# Carl Grant-Acquah — AI Automation Portfolio

> I build systems that replace manual work with intelligent automation. Every tool here solves a real business problem.

**Stack:** n8n · Playwright · Make.com · Gemini AI · Pinecone · Vercel · Python · JavaScript

---

## Featured Projects

### 1. ProDispatcher — Business Autonomy System
**Live:** [prodispatcher-website.vercel.app](https://prodispatcher-website.vercel.app/home.html)

A full-stack AI automation system for HVAC and Plumbing business owners that eliminates missed calls and manual lead management.

**What it does:**
- AI voice receptionist that answers every call 24/7, handles FAQs, routes emergencies, books appointments
- 15-question Business Autonomy Audit that scores businesses 0–100 and prescribes tiered solutions
- Revenue Leakage Calculator showing exact dollar cost of missed calls
- Automated CRM sync, calendar integration, and review request system

**Tech stack:** Voice AI · CRM APIs · Calendar integration · JavaScript · Vercel

**Impact:** Clients recover an average of $15,000 in month 1 from previously missed leads

---

### 2. ProDispatcher RAG Knowledge Base Chatbot
**Demo:** [Loom Video](https://loom.com) <!-- update with your link -->

A production RAG (Retrieval-Augmented Generation) system that answers natural language questions from ProDispatcher's own business documents in real time.

**What it does:**
- Ingests and vectorizes business documents into Pinecone (3072-dimension embeddings)
- Retrieves semantically relevant chunks using Google's gemini-embedding-2-preview model
- Generates accurate, contextual answers using Gemini 2.5 Flash
- Returns structured JSON with answer, booking link, and audit CTA via webhook

**Tech stack:** n8n · Google Gemini (embedding + LLM) · Pinecone · Webhook API

**Architecture:**
```
Webhook → Extract Question → QA Chain → Format Response → Send Response
                                ↑              ↑
                    Vector Store Retriever   Gemini Flash LLM
                                ↑
                    Pinecone Vector Store ← Gemini Embeddings
```

**Sample response time:** 2.6–4.5 seconds end-to-end

---

### 3. Master Business Orchestrator — Single-Command Operations
**Status:** Active (in development — Phase 2 of 3)

A single terminal command that runs the entire daily business operation for ProDispatcher without manual intervention.

**What it does:**
- Phase 1 (Complete): Content research → AI content creation → social media posting → engagement with relevant content → outreach to prospects and partners
- Phase 2 (In progress): Daily bonus tasks for additional growth activities
- Phase 3 (Planned): Email outreach automation system

**Tech stack:** Python · Playwright · Browser automation · LLM APIs · Shell scripting

**Key feature:** Playwright bots operate in a humanized manner — mimicking human browsing patterns, timing, and behavior to prevent bot detection across social platforms

---

### 4. Playwright Humanized Social Automation Bots
**Status:** Active — running daily

Automated browser bots that manage the complete social media presence for ProDispatcher using real browser sessions.

**What they do:**
- Research trending content relevant to HVAC and Plumbing niche
- Generate and post AI-written content across platforms
- Engage with relevant posts from target audience
- Send personalized outreach messages to prospects and potential partners
- Operate within human-like timing windows to avoid detection

**Tech stack:** Playwright · Python · LLM APIs · Browser automation

---

### 5. Business Autonomy Audit Engine
**Live:** [prodispatcher-website.vercel.app/index.html](https://prodispatcher-website.vercel.app/index.html)

A scored diagnostic tool that evaluates a business across 3 categories and prescribes a tiered solution based on the result.

**What it does:**
- 15-question assessment covering Availability, Speed-to-Lead, and System Dependency
- Scoring algorithm produces a 0–100 Autonomy Score
- Score automatically places business in Crisis (0–40), Growth (41–70), or Scale (71–100) tier
- Generates personalized action plan and tier recommendation

**Tech stack:** JavaScript · Vercel · Form logic · Scoring algorithm

---

### 6. Revenue Leakage Calculator
**Live:** [prodispatcher-website.vercel.app/calculator.html](https://prodispatcher-website.vercel.app/calculator.html)

An interactive calculator that shows HVAC and Plumbing owners the exact dollar amount they are losing to missed calls annually.

**What it does:**
- Takes industry, average job value, daily call volume, and missed call rate as inputs
- Calculates annual revenue lost, monthly loss, and missed jobs per year
- After-hours toggle for businesses losing leads outside staffed hours
- Outputs a specific dollar figure that drives conversion to the audit

**Tech stack:** JavaScript · Real-time calculation · Vercel

---

### 7. Make.com Workflow Automations
**Status:** Historical — built across multiple client and personal projects

A collection of automation workflows built in Make.com connecting forms, CRMs, email platforms, and third-party APIs.

**Examples built:**
- Lead capture forms connected to CRM and email notification sequences
- Instagram content scheduling and posting automations
- LinkedIn engagement automation (comment generation and posting)
- Email sequences triggered by form submissions
- Landing page → CRM → email nurture pipelines

**Tech stack:** Make.com · Webhooks · REST APIs · Email platforms · Social APIs

---

## Skills Summary

| Category | Tools & Technologies |
|----------|---------------------|
| Workflow Automation | n8n, Make.com, Webhooks, REST APIs |
| AI & LLMs | Google Gemini, OpenAI, Prompt Engineering, RAG Systems |
| Browser Automation | Playwright, Humanized Bot Patterns, Session Management |
| Vector Databases | Pinecone, Semantic Search, Embedding Models |
| Frontend | JavaScript, HTML, CSS, Vercel, Carrd |
| Business Systems | CRM Integration, Calendar APIs, Voice AI, Lead Automation |

---

## What I Build For

I specialize in building **revenue-generating automation systems** for service businesses — tools that capture leads, eliminate manual work, and scale operations without adding headcount.

If you are building AI-powered products and need someone who can go from concept to working production system fast, I would love to connect.

**LinkedIn:** [linkedin.com/in/carl-grant-acquah](https://linkedin.com/in/carl-grant-acquah)
**Email:** carlgrantacquah@gmail.com, acquahgrantcarl@gmail.com
**Strategy call:** [calendly.com/acquahgrantcarl/30min](https://calendly.com/acquahgrantcarl/30min)
