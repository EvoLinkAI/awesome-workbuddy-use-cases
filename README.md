<div align="center">

# 🤖 Awesome WorkBuddy Use Cases

**The definitive collection of AI Agent automation scenarios for modern professionals**

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![Cases](https://img.shields.io/badge/Cases-230%2B-blue?style=flat-square)
![Professions](https://img.shields.io/badge/Professions-30-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)

**Language:** English | [简体中文](README.zh-CN.md)

</div>

---

## What is this?

WorkBuddy is not a chatbot. It's a **digital employee** that can browse the web, read and write local files, execute code, call APIs, and complete complex multi-step workflows — autonomously.

This repository is a curated, community-maintained collection of **230+ real-world automation use cases** organized by profession and task type. Each case is a ready-to-use scenario template: copy the description, feed it to WorkBuddy, and watch it work.

---

## Navigation

| | | |
|:---:|:---:|:---:|
| 👔 **[By Profession](#by-profession)** | 🔧 **[By Task Type](#by-task-type)** | 📖 **[Whitepaper](#whitepaper)** |
| 30 professional roles | 7 task categories · 100 cases | 100 cases with full detail tables |

---

## By Profession

*[Full details →](use-cases/by-profession/)*

<details>
<summary><b>🏢 General Office & Management</b> — 6 roles</summary>

### 1. Finance Staff

- **Multi-source reconciliation** — Automatically download bank statements and ERP exports, match every transaction, and flag discrepancies.
- **Invoice auto-archiving** — Batch-process PDF invoices in a folder, extract month/tax info to Excel, and rename files to a standard format.
- **Tax policy alerts** — Daily search of the tax authority website; summarize policy changes relevant to your company.

### 2. HR / Recruiter

- **Resume auto-screening** — Batch-read 50 resumes from the downloads folder, output a scoring table based on job requirements.
- **Onboarding package prep** — Given a name, auto-generate Offer letter, onboarding guide, and contract template with key fields filled in.
- **Pre-interview research** — Automatically search the candidate's social media, public portfolio, or industry reviews before the interview.

### 3. Legal / Lawyer

- **Contract compliance review** — Read contract files, compare against company standard templates, flag all "liability exemptions" and "breach clauses."
- **Legal case research** — Auto-search case law databases for similar verdicts and summarize judicial reasoning.
- **License expiry reminders** — Scan the company license folder, auto-generate an expiry schedule, and link to calendar.

### 4. Administrative Specialist

- **Automated asset inventory** — Auto-compare procurement exports against department registration forms; flag unregistered or missing items.
- **Travel expense classification** — Extract travel invoices from a folder, auto-categorize as flights/hotel/dining, generate summary report.
- **Meeting room scheduling** — Based on chat records or instructions, query calendar availability, send invites, and book rooms.

### 5. Procurement Specialist

- **Multi-vendor quote comparison** — Read quotes from multiple suppliers in different formats, extract key parameters and prices, generate a standardized comparison Excel.
- **Vendor qualification scan** — Scan supplier qualification documents, auto-query business registry for anomalies.
- **Order logistics tracking** — Daily access to logistics backend, capture latest status, auto-update local supply chain dashboard.

### 6. Executive Assistant

- **Fragmented invites → schedule** — Read WeChat screenshots or emails with scattered meeting info, auto-generate a structured daily agenda.
- **Smart email drafting** — Classify inbox every morning, auto-generate polished reply drafts for routine inquiry emails.
- **Cross-timezone meeting finder** — Identify guests' timezones, cross-reference with the boss's local calendar, recommend meeting slots within working hours for all parties.

</details>

<details>
<summary><b>📣 Marketing, Sales & Customer Success</b> — 7 roles</summary>

### 7. Social Media Operator

- **Trending topic library** — Periodically scrape trending lists on Xiaohongshu and Douyin, extract hot topics and generate 5 rewrite directions.
- **Multi-platform publishing** — Auto-convert local Markdown articles to formats optimized for WeChat Official Account, Zhihu, and Toutiao.
- **Comment sentiment analysis** — Auto-read backend messages, classify as "inquiry/complaint/praise," and suggest reply strategies.

### 8. E-commerce Operator

- **Negative review monitoring** — Auto-monitor store backend; trigger notification and generate follow-up script when a 3-star-or-below review appears.
- **Competitor price tracking** — Check competitor SKU price changes every 4 hours, auto-update internal pricing suggestion table.
- **Product description writing** — Input product selling points, auto-generate detail page copy in different sizes and promotional styles.

### 9. Sales Representative

- **Personalized opening pitch** — Visit prospect's website, generate a personalized visit email based on their latest news.
- **Sales opportunity scoring** — Analyze interaction frequency in CRM history, flag clients most likely to close this week.
- **Meeting recording → proposal** — Submit recording after meeting, auto-extract pain points and generate initial quote.

### 10. PR Specialist

- **Sentiment monitoring alert** — Periodically scrape brand-keyword mentions from media pool; screenshot and alert when sentiment turns negative.
- **Press release multi-version conversion** — Rewrite internal notices as formal PR copy; generate platform-specific social media variants.
- **Media library incremental update** — Auto-extract blogger info from industry ranking pages, update local media contacts Excel.

### 11. SEO / SEM Optimizer

- **Long-tail keyword mining** — Auto-scrape long-tail and autocomplete keywords, deduplicate and clean, save as CSV.
- **Competitor ad creative capture** — Auto-search specific keywords, screenshot competitor ad creatives and landing page copy.
- **Traffic anomaly attribution** — Compare backend traffic reports, auto-identify the specific ad plan or channel where conversion rate dropped.

### 12. Customer Service Manager

- **Ticket emotion tagging** — Read daily customer service chat export, identify "angry" or "complaint-prone" conversations.
- **Response library dynamic update** — Extract excellent replies from recently resolved complex tickets, add to shared response library document.
- **Return/exchange auto-reply** — Identify chats containing tracking numbers, auto-query ERP status, generate reply.

### 13. Market Research Analyst

- **Financial report data extraction** — Auto-download latest PDF annual reports from industry peers, extract revenue/profit data and plot charts.
- **Survey dirty data cleaning** — Batch-process survey Excel files, auto-correct typos, remove invalid responses.
- **Trend report translation & distillation** — Scrape latest long-form foreign research reports, fully translate, extract core conclusions, build into PPT.

</details>

<details>
<summary><b>💻 Tech, Design & Creative</b> — 8 roles</summary>

### 14. Software Engineer

- **PR auto-review** — Check new commits in the local codebase, evaluate code quality against company standards.
- **Technical docs sync** — Auto-update local README or API docs based on code changes.
- **Environment setup automation** — One instruction to run complex CLI combos, install dependencies, configure local environment variables.

### 15. Product Manager

- **Competitor analysis report** — Auto-search latest version changelogs of specific competitors, summarize their strategic intent.
- **PRD auto-completion** — Given core logic, auto-generate detailed boundary conditions and exception handling flows.
- **Feedback aggregation** — Summarize multiple user research forms, extract top-3 requested feature points.

### 16. Data Analyst

- **Report automation** — Scheduled daily open of local database or Excel, update dashboard charts, screenshot and send to team.
- **Anomaly detection** — Auto-scan sales figures; when period-over-period fluctuation exceeds threshold, auto-investigate potential causes.
- **Natural language → SQL** — Ask questions in plain language, auto-generate SQL queries and export results to desktop.

### 17. Copywriter

- **Multi-language rewrite** — Convert a local product plan into social media posts in Chinese, English, and Japanese with one click.
- **SEO keyword insertion** — Auto-optimize existing articles, reasonably embed high-traffic search terms without altering meaning.
- **Brand volume weekly report** — Search the past 7 days of brand discussion word clouds and sentiment across the web.

### 18. UI / UX Designer

- **Asset library auto-organization** — Batch-rename exported design assets based on visual content and sort into correct folders.
- **Placeholder text replacement** — Read product requirement docs, generate real copy, replace test text in design mockups.
- **Competitor visual audit** — Auto-visit competitor websites, screenshot and save specific modules (e.g. login page) to local reference library.

### 19. Video Editor / Director

- **Long-video "moment finder"** — Process audio transcripts of long videos, mark timestamps where laughter peaks or high-frequency words appear.
- **Multi-language subtitle pipeline** — Extract draft Chinese subtitles, auto-translate, export strict SRT files with timestamps.
- **Script B-roll matching** — Based on the local text storyboard script, auto-search corresponding B-roll footage on copyright-free sites.

### 20. Translator

- **Batch translation with formatting preserved** — First-pass machine translation of Word/PPT files in a folder without destroying original layout.
- **Terminology alignment & extraction** — Compare source and finalized translations, auto-extract professional term pairs to enrich local terminology database.
- **Localization polish** — Rewrite directly-translated English product introductions in natural, marketing-oriented native speaker style.

### 21. Academic Researcher / Graduate Student

- **Batch literature scanning** — Given a folder of PDF papers, auto-extract abstracts and methods into a literature review table.
- **Chart data reverse-engineering** — Recognize bar/line charts in old papers, convert to approximate Excel data tables.
- **Citation auto-formatting** — Convert rough URLs or book titles into properly formatted APA or IEEE reference lists.

</details>

<details>
<summary><b>🏥 Vertical Industries & Specialized Roles</b> — 9 roles</summary>

### 22. Teacher / Trainer

- **Exam paper generation & layout** — Given a knowledge outline, auto-generate a paper with multiple-choice and short-answer questions plus answer explanations.
- **Homework batch pre-grading** — Read student submissions, check against answer keys for initial scoring, flag suspected plagiarism.
- **Handout → PPT slides** — Input textbook chapter text, auto-extract teaching outline and generate lecture PPT.

### 23. Real Estate Agent

- **Multi-channel listing distribution** — Based on local listing info, auto-generate different copy for Moments, Xiaohongshu, and listing platforms.
- **Historical transaction comparison** — After receiving client budget, auto-query similar unit transaction records in the same complex, generate negotiation reference card.
- **Contract auto-fill** — Extract ID card photo information, auto-fill into corresponding lines of rental/sale contracts.

### 24. Doctor / Medical Admin

- **Electronic medical record structuring** — Convert doctor dictation transcripts into standard format: chief complaint, history of present illness, diagnosis.
- **Frontier literature tracking** — Weekly auto-search medical databases for new treatment methods for specific diseases, translate to Chinese brief.
- **Follow-up patient list extraction** — From discharged patient Excel, filter those with specific conditions, discharged over N days, and not yet re-examined.

### 25. Insurance Agent

- **Policy clause comparison** — Read two critical illness insurance PDFs, compare "exclusion clauses" and key differences in a table.
- **Protection plan auto-generation** — Input client family structure and income, auto-generate Family Protection Gap Planning PPT draft.
- **Claims document pre-audit** — Extract client medical invoice photos, OCR-recognize total amount and out-of-pocket items, estimate claim amount.

### 26. Logistics / Supply Chain

- **Document anomaly comparison** — Auto-compare core data consistency between commercial invoices, packing lists, and bills of lading.
- **Abnormal shipment interception** — Scan carrier-returned Excel status sheets, auto-extract "damaged" or "refused" order numbers for customer service.
- **Timeliness gap analysis** — Consolidate one month of delivery data, auto-identify routes with longest average delays and mark reasons.

### 27. Event Planner

- **Venue scouting comparison sheet** — Given requirements, auto-search hotel venue info and sales contacts online, organize into research table.
- **Materials checklist audit** — Compare event plan document with supplier quote, check for missing materials or quantity errors.
- **Post-event report automation** — Auto-collect event-day photos and social media mentions, generate Event Summary Report PPT.

### 28. Architect / Interior Designer

- **Standards intelligent search** — Precisely search fire protection and smoke exhaust clauses in local National Building Standards PDF library.
- **Soft furnishing BOM extraction** — Extract furniture and lighting model descriptions from design plans or CAD annotations, generate procurement list Excel.
- **Reference image batch collection** — Based on style descriptions, auto batch-download high-quality reference images and organize into space-specific folders.

### 29. Management Consultant

- **Macro data charting** — Auto-scrape specific industry data from statistics bureaus or industry sites, directly generate local Excel trend charts.
- **Interview notes structuring** — Convert verbatim expert interview transcripts into "Background, Challenge, Solution" summaries following the McKinsey Pyramid.
- **Framework-based deck formatting** — Extract content from messy text and basic charts, fill into company standard report PPT template.

### 30. Psychologist / Social Worker

- **Scale auto-scoring** — Batch-process client-filled test questionnaire Excel files, auto-apply scoring formulas and output analysis tables.
- **Case record anonymization** — Auto-scan case documents, replace real names, employers, and other sensitive info with pseudonyms.
- **Helpline pain point distillation** — Analyze text records from public helpline calls, extract common emotional pain points, generate monthly report.

</details>

---

## By Task Type

*[Full details →](use-cases/by-task/)*

### 1. Data Processing & Automation Workflows

> `Scheduled Tasks` `Web Scraping` `File I/O` `Code Execution` `API Calls`

| Case | Description |
| :--- | :--- |
| **Daily financial report summary** | **Daily financial report summary** — Scheduled scraping, extract core data, send summary to Telegram. <br> **核心能力:** `Scheduling` `Web Scraping` `NLP` |
| **Invoice auto-reimbursement entry** | **Invoice auto-reimbursement entry** — Monitor email folder, OCR invoices, auto-submit to OA system. <br> **核心能力:** `File Monitoring` `OCR` `API Call` |
| **Competitor price monitoring** | **Competitor price monitoring** — Scheduled scraping of e-commerce pages, auto-update local CSV. <br> **核心能力:** `Scheduling` `Web Scraping` `File I/O` |
| **Sales leads (CRM) cleaning** | **Sales leads (CRM) cleaning** — Read CRM export, remove invalids, deduplicate, tag by industry. <br> **核心能力:** `File I/O` `Code Execution` `NLP` |
| **Real-time multi-currency quote calculation** | **Real-time multi-currency quote calculation** — Auto-query live exchange rates and compute on demand. <br> **核心能力:** `API Call` `NLP` `Logic` |
| **Auto-write weekly report draft** | **Auto-write weekly report draft** — Every Friday, extract calendar/Git/email activity, generate report. <br> **核心能力:** `Multi-source API` `Memory` `NLG` |
| **Business report anomaly alert** | **Business report anomaly alert** — Read monitoring output, alert when conversion rate drops. <br> **核心能力:** `File Monitoring` `Logic` `Push Notification` |
| **Desktop file auto-organization** | **Desktop file auto-organization** — One-click classify and rename documents in Downloads by content. <br> **核心能力:** `File I/O` `NLP` `Shell Commands` |
| **Cross-platform task status sync** | **Cross-platform task status sync** — Auto-sync Notion project progress updates to Jira. <br> **核心能力:** `Cross-platform API` `Data Mapping` |
| **Meeting recording → action items** | **Meeting recording → action items** — Extract Action Items from transcript, write to Todoist. <br> **核心能力:** `File I/O` `NLP` `API Call` |
| **Employee attendance anomaly stats** | **Employee attendance anomaly stats** — Calculate and filter late/early departure records from raw data. <br> **核心能力:** `File I/O` `Code Execution` |
| **Morning industry news brief** | **Morning industry news brief** — Daily 7am: collect top-5 industry news, summarize, send to group. <br> **核心能力:** `Scheduling` `Web Search` `NLG` |
| **Customer service chat sentiment analysis** | **Customer service chat sentiment analysis** — Batch-read previous day's chats, score service quality. <br> **核心能力:** `Batch File Read` `NLP Sentiment` |
| **Local data auto-visualization** | **Local data auto-visualization** — From CSV in chat, auto-write Python to generate charts. <br> **核心能力:** `Code Generation` `Code Execution` `File I/O` |
| **Server/website status probe** | **Server/website status probe** — Periodically ping company website, alert via WhatsApp if down. <br> **核心能力:** `Scheduling` `HTTP Request` `Push Notification` |

### 2. Document Management & Deep Reading

> `PDF Parsing` `RAG` `OCR` `Semantic Comparison` `File Monitoring`

| Case | Description |
| :--- | :--- |
| **Long document immersive translation** | **Long document immersive translation** — Translate hundreds-of-pages PDF maintaining terminology consistency. <br> **核心能力:** `Large File Chunking` `Memory` `MT` |
| **Bidding document version comparison** | **Bidding document version comparison** — Compare two Word docs, highlight clause differences, output risk summary. <br> **核心能力:** `File Parsing` `Semantic Diff` |
| **Legal contract initial risk review** | **Legal contract initial risk review** — Auto-scan downloaded contract, identify unfavorable clauses. <br> **核心能力:** `File Read` `Domain Knowledge` `NLP` |
| **Resume auto-screening** | **Resume auto-screening** — Score all resume attachments from recruiting email vs JD, sort into table. <br> **核心能力:** `Batch Processing` `OCR` `NLP Matching` |
| **Local knowledge base index building** | **Local knowledge base index building** — Monitor folder, extract tags and summaries from new docs, update index. <br> **核心能力:** `Directory Monitoring` `Summarization` `File Write` |
| **Email attachment rule-based archiving** | **Email attachment rule-based archiving** — Detect key client emails, auto-download attachments by year/project. <br> **核心能力:** `IMAP` `File System` |
| **Complex data table split & distribute** | **Complex data table split & distribute** — Split company-wide Excel by department, email to each head. <br> **核心能力:** `Code Execution` `Email Send` |
| **Company policy "living dictionary"** | **Company policy "living dictionary"** — Use employee handbook as knowledge base to answer policy questions. <br> **核心能力:** `Local RAG` `NLP` |
| **Historical chat & decision tracing** | **Historical chat & decision tracing** — Search long-term chat logs for past discussions with context. <br> **核心能力:** `DB Search` `Long-term Memory` `NLP` |
| **Shared file co-sign tracking** | **Shared file co-sign tracking** — Monitor collaborative doc edits, remind unsigned stakeholders. <br> **核心能力:** `Doc API` `Data Diff` `Scheduling` |
| **Sensitive data auto-masking** | **Sensitive data auto-masking** — Before sending, auto-detect and mask ID numbers, financial data. <br> **核心能力:** `Regex` `NER` `File Rewrite` |
| **Product operation manual generation** | **Product operation manual generation** — From PM notes and screenshots, generate structured user guide. <br> **核心能力:** `Multimodal` `NLG` |
| **Whiteboard photo → structured notes** | **Whiteboard photo → structured notes** — OCR meeting whiteboard photo, convert to tidy Markdown. <br> **核心能力:** `Vision/OCR` `Formatted Output` |
| **Long PPT → one-page summary** | **Long PPT → one-page summary** — Read 50-page PPT, extract core arguments and conclusions. <br> **核心能力:** `Doc Parsing` `Summarization` |
| **Code / doc change summary** | **Code / doc change summary** — Read Git commits or doc edits, generate readable release notes. <br> **核心能力:** `Terminal/API` `Technical NLG` |

### 3. Communication & Scheduling

> `Calendar API` `Email Automation` `Timezone Logic` `Long-term Memory`

| Case | Description |
| :--- | :--- |
| **Complex email intelligent drafting** | **Complex email intelligent drafting** — Given a complaint email and instruction, auto-generate professional reply. <br> **核心能力:** `Context Understanding` `NLG Tone Control` |
| **Schedule conflict auto-coordination** | **Schedule conflict auto-coordination** — When meeting invite arrives, check calendar; reply with available slots if conflict. <br> **核心能力:** `Calendar API` `Time Logic` `Auto-reply` |
| **Cross-timezone best meeting time** | **Cross-timezone best meeting time** — Given US/EU/CN participants, exclude sleep hours, recommend intersection. <br> **核心能力:** `Timezone Logic` `Data Filtering` |
| **Pre-meeting materials push** | **Pre-meeting materials push** — 15 min before meeting, send link + last meeting's summary via IM. <br> **核心能力:** `Scheduling` `Memory Retrieval` |
| **Business dinner restaurant recommendation** | **Business dinner restaurant recommendation** — Combine boss's dietary preferences, search nearby restaurants, send 3 options. <br> **核心能力:** `Personal Memory` `Web Search` `API Call` |
| **Client visit route planning** | **Client visit route planning** — Read today's schedule addresses, calculate commute times, estimate departure. <br> **核心能力:** `Maps API` `Time Calculation` `Notification` |
| **Focus mode message filtering** | **Focus mode message filtering** — During focus, take over chat app, only alert for "extremely urgent." <br> **核心能力:** `IM API Monitoring` `NLP Priority` |
| **Cross-national group chat live translation** | **Cross-national group chat live translation** — Monitor all-English work group, translate core discussions to Chinese brief. <br> **核心能力:** `Real-time Stream` `Machine Translation` |
| **Offboarding asset auto-collection** | **Offboarding asset auto-collection** — On offboarding instruction, send form, compile all assets and handover links. <br> **核心能力:** `RPA` `Info Aggregation` |
| **Client birthday / holiday custom greetings** | **Client birthday / holiday custom greetings** — Daily scan CRM for birthdays, auto-generate personalized greetings. <br> **核心能力:** `DB Query` `Scheduling` `Personalized NLG` |
| **Automated interview scheduling** | **Automated interview scheduling** — Multi-round email exchange with candidates, then calendar invite to interviewers. <br> **核心能力:** `Multi-turn Dialog` `Calendar Write` |
| **Cross-department process gentle reminder** | **Cross-department process gentle reminder** — Periodically check OA approvals stuck at a node, send polite follow-up. <br> **核心能力:** `Page Scraping/API Poll` `High-EQ NLG` |
| **Visitor Wi-Fi auto-distribution** | **Visitor Wi-Fi auto-distribution** — Guest @s Agent in group, Agent verifies daily visitor list, DMs temp password. <br> **核心能力:** `List Verification` `Trigger Response` |
| **IT/admin ticket initial triage** | **IT/admin ticket initial triage** — Classify repair ticket intent, route to network or facilities team. <br> **核心能力:** `Text Classification` `Routing Rules` |
| **Post-vacation "catch me up" context restore** | **Post-vacation "catch me up" context restore** — Ask "what did I miss," get progress and key decisions summary per project. <br> **核心能力:** `Log Aggregation` `Summarization` |

### 4. Project Management & Research

> `Git Integration` `Jira/Trello API` `Web Search` `Vector DB` `Code Execution`

| Case | Description |
| :--- | :--- |
| **Agile board daily inspection** | **Agile board daily inspection** — Read Jira/Trello, summarize "at-risk of delay" tasks, send to PM before end of day. <br> **核心能力:** `PM API` `Data Filter` |
| **Fast Code Review assistant** | **Fast Code Review assistant** — On new PR, auto-pull code, run basic checks, provide standards suggestions. <br> **核心能力:** `Git/Shell` `Code LLM` `Static Analysis` |
| **Industry report auto-downloader** | **Industry report auto-downloader** — Monitor consulting websites, download new reports matching keywords. <br> **核心能力:** `Web Change Detection` `Auto Download` `File Mgmt` |
| **Patent & technical prior art scan** | **Patent & technical prior art scan** — Background-compare with public patent database for infringement risks. <br> **核心能力:** `Vector DB` `Text Similarity` |
| **Competitor deep background check** | **Competitor deep background check** — Input company name, auto-collect bid wins, negative news, executive changes. <br> **核心能力:** `Deep Web Search` `Entity Extraction` |
| **Daily standup auto-facilitator** | **Daily standup auto-facilitator** — At fixed time, @members in sequence, summarize each person's blockers. <br> **核心能力:** `Scheduled Group Msg` `Dialog Summary` |
| **API docs auto-sync** | **API docs auto-sync** — Monitor backend routing comment changes, auto-generate latest API docs. <br> **核心能力:** `File Monitoring` `Code Parsing` |
| **PRD logic error-checking** | **PRD logic error-checking** — Check new PRD against historical docs, flag function contradictions or missing logic. <br> **核心能力:** `Historical Text Diff` `Business Logic Reasoning` |
| **Online bug log clustering** | **Online bug log clustering** — Denoise and cluster thousands of error logs, find top-3 root causes. <br> **核心能力:** `Batch Data Processing` `ML Clustering` |
| **Non-standard vendor quote comparison** | **Non-standard vendor quote comparison** — Extract PDFs from multiple vendors, normalize parameters, generate comparison Excel. <br> **核心能力:** `Complex Table OCR` `Data Alignment` |
| **Local disk space alert & cleanup** | **Local disk space alert & cleanup** — Monitor disk; when near full, identify large useless log files and ask for confirmation. <br> **核心能力:** `OS Commands` `Conditional Trigger` |
| **Vertical academic paper tracking** | **Vertical academic paper tracking** — Weekly auto-search arXiv/PubMed, generate translated abstracts list. <br> **核心能力:** `Academic API` `PDF Processing` `Domain MT` |
| **Project budget burn monitoring** | **Project budget burn monitoring** — Link invoice folder to budget table; alert when budget 80% consumed. <br> **核心能力:** `Cross-file Calculation` `Threshold Trigger` |
| **Software license expiry reminder** | **Software license expiry reminder** — Read subscription list, auto-draft renewal email 30 days before expiry. <br> **核心能力:** `DB Read` `Time Calculation` `Email Draft` |
| **App store review sentiment word cloud** | **App store review sentiment word cloud** — Pull latest reviews, segment words, generate pain point word cloud. <br> **核心能力:** `Store Scraping` `Segmentation` `Image Gen` |

### 5. Copywriting & Creative Strategy

> `NLG Style Control` `Web Trending` `Long-form Planning` `Multi-language`

| Case | Description |
| :--- | :--- |
| **Viral social title A/B generator** | **Viral social title A/B generator** — Feed a dry draft, combine with trending words, generate 10 attention-grabbing titles. <br> **核心能力:** `Trending Scraping` `Stylized NLG` |
| **SEO content optimization & rewrite** | **SEO content optimization & rewrite** — Analyze existing blog post, optimize keyword density and structure. <br> **核心能力:** `SEO Rules` `Text Restructuring` |
| **Large speech / launch event structuring** | **Large speech / launch event structuring** — Input key highlights, auto-derive PPT speaking outline with hook and closing. <br> **核心能力:** `Logic Planning` `Long-form Framework` |
| **Corporate news release expander** | **Corporate news release expander** — Turn sparse data points into a polished thousand-word PR article. <br> **核心能力:** `NLG Register Mimicry` `Info Expansion` |
| **Brand origin story writing** | **Brand origin story writing** — Combine founder quotes and early photos, craft emotionally resonant brand story. <br> **核心能力:** `Multimodal` `Memory Synthesis` `Emotional NLG` |
| **B2B sales pitch customization** | **B2B sales pitch customization** — Convert generic product intro into industry-specific pitches (medical/education/manufacturing). <br> **核心能力:** `Vertical Domain Knowledge` `Text Adaptation` |
| **Cross-cultural transcreation** | **Cross-cultural transcreation** — Not just translate, but rewrite for Japanese or Middle East cultural context and idioms. <br> **核心能力:** `Cross-cultural Context` `Deep NLP` |
| **PR crisis statement drafting** | **PR crisis statement drafting** — When negative sentiment detected, generate "clarification + apology + measures" draft in 5 min. <br> **核心能力:** `Crisis PR Template` `High-sensitivity NLG` |
| **Business plan (BP) professional polish** | **Business plan (BP) professional polish** — Rewrite colloquial startup ideas into investor-facing copy with TAM and business model. <br> **核心能力:** `Business Reasoning` `Professional Terminology` |
| **Brand slogan brainstorming engine** | **Brand slogan brainstorming engine** — Input selling points, use puns/rhymes/contrast to batch-generate memorable slogans. <br> **核心能力:** `Rhetorical Modeling` `Short-text Creative Gen` |
| **Novel / script → storyboard script** | **Novel / script → storyboard script** — Auto-decompose novel text into "scene / character / dialogue / shot type" storyboard format. <br> **核心能力:** `Text Structuring` `Film Industry Terms` |
| **Podcast show notes extraction** | **Podcast show notes extraction** — From transcript, auto-extract timestamps, guest quotes, and mentioned links. <br> **核心能力:** `Long-text Summary` `Entity Extraction` |
| **Marketing copy multi-platform adaptation** | **Marketing copy multi-platform adaptation** — Same event auto-generates WeChat Moments / Xiaohongshu / Zhihu versions. <br> **核心能力:** `Platform Tone Learning` `Multi-style Conversion` |
| **Long-form fiction setting consistency check** | **Long-form fiction setting consistency check** — Monitor setting database; alert if character/world details contradict earlier chapters. <br> **核心能力:** `Knowledge Graph` `Long-context Consistency` |
| **Interactive game plot multi-branch derivation** | **Interactive game plot multi-branch derivation** — Given a key plot decision, derive 3 outcomes matching character personalities. <br> **核心能力:** `Character Model` `Logic Branch Reasoning` |

### 6. Social Media & Marketing Automation

> `Browser Automation` `RPA` `IM API` `Real-time Monitoring`

| Case | Description |
| :--- | :--- |
| **Xiaohongshu "trendy" post direct output** | **Xiaohongshu "trendy" post direct output** — Upload product photo, auto-add emoji-heavy review copy. <br> **核心能力:** `Visual Feature Extract` `Stylized NLG` |
| **Short-video golden 3-second script** | **Short-video golden 3-second script** — Scrape TikTok/Douyin trends, generate hook script and camera direction. <br> **核心能力:** `Trend Scraping` `Audio-visual Language` |
| **Social media fan humanized auto-reply** | **Social media fan humanized auto-reply** — Randomly humanized auto-reply to common repetitive questions. <br> **核心能力:** `API Monitoring` `Intent ID` `Varied Reply` |
| **Competitor social media viral post analysis** | **Competitor social media viral post analysis** — Daily scrape competitor's top posts, reverse-engineer topic angle. <br> **核心能力:** `Web Data Scraping` `Attribution NLP` |
| **Matrix account one-click content distribution** | **Matrix account one-click content distribution** — Put article in folder, auto-publish to WeChat / Zhihu / Toutiao. <br> **核心能力:** `File Monitoring` `RPA or API` |
| **Full giveaway campaign management** | **Full giveaway campaign management** — Auto-post giveaway, clean fake accounts, randomly select real fans, DM winners. <br> **核心能力:** `Platform API` `Code Execution` `Random Algo` |
| **Brand annual marketing calendar reminders** | **Brand annual marketing calendar reminders** — One week ahead, push brand-aligned marketing copy and strategy for holidays. <br> **核心能力:** `Long-term Calendar Memory` `Scheduling` `Creative Synthesis` |
| **Live room moderation & comment distillation** | **Live room moderation & comment distillation** — Real-time ingest comment stream, auto-ban toxic words, surface top-3 audience questions. <br> **核心能力:** `Stream Processing` `Sensitive Word Filter` `Aggregation` |
| **Viral poster dynamic update** | **Viral poster dynamic update** — Based on user's referral tier, auto-run script to replace invite code and copy in poster. <br> **核心能力:** `Image Processing Lib` `Dynamic Synthesis` |
| **KOL batch custom outreach** | **KOL batch custom outreach** — Import blogger list, batch-generate heartfelt collaboration invites praising specific posts, and send. <br> **核心能力:** `Web Content Quick Read` `Email Automation` `NLG` |
| **Trending event rapid content creation** | **Trending event rapid content creation** — On industry-related hot topic, generate high-quality commentary draft in 10 min. <br> **核心能力:** `High-frequency Monitoring` `Rapid Gen` |
| **Real user UGC collection net** | **Real user UGC collection net** — Auto-search all brand mentions, compile positive-sentiment image-text screenshots. <br> **核心能力:** `Full Web Search` `Sentiment Classification` `Screenshot` |
| **Executive / IP persona WeChat script** | **Executive / IP persona WeChat script** — Custom daily posting plan, remind and provide draft for one-click publish. <br> **核心能力:** `Persona Prompt Tuning` `Scheduled Task Mgmt` |

### 7. Multimedia, Design & Code Support

> `Image Processing` `Code Gen` `Shell/FFmpeg` `Vector DB` `Multimodal`

| Case | Description |
| :--- | :--- |
| **AI image prompt enhancer** | **AI image prompt enhancer** — Input "cyberpunk girl," expand to full Midjourney prompt with lighting and engine params. <br> **核心能力:** `Prompt Engineering` `Design Vocabulary` |
| **Local untagged asset library natural language search** | **Local untagged asset library natural language search** — Scan thousands of unnamed assets, add vector tags, search by description. <br> **核心能力:** `Multimodal Tagging` `Local Vector DB` |
| **Video rough-cut marking** | **Video rough-cut marking** — From audio transcript, auto-cut silent segments, record valid segment timestamps for editor. <br> **核心能力:** `Audio-video Transcript` `Logic Calculation` |
| **Virtual voice-over TTS pre-processing** | **Virtual voice-over TTS pre-processing** — Convert colloquial text to TTS-ready format, annotate emphasis and pauses. <br> **核心能力:** `Phonology Rules` `SSML Format Output` |
| **Event invitation batch auto-synthesis** | **Event invitation batch auto-synthesis** — Read 100-person CSV, run Python with design template, render 100 personalized invitation images. <br> **核心能力:** `Code Execution (Image Render)` `Batch File Write` |
| **Hand-drawn sketch → front-end prototype** | **Hand-drawn sketch → front-end prototype** — Send whiteboard sketch photo, Agent generates running HTML/Tailwind CSS page. <br> **核心能力:** `Visual Layout Understanding` `Code Gen` `Local Preview` |
| **Animation script keyframe timeline calculation** | **Animation script keyframe timeline calculation** — Based on VO script, calculate speaking pace, generate timestamped keyframe script for AE. <br> **核心能力:** `Data Calculation` `Specific File Format Gen` |
| **Complex game plot tree visualization** | **Complex game plot tree visualization** — Read branching story text, auto-convert to Mermaid code, render into flow network. <br> **核心能力:** `Logic Topology Extract` `Mermaid Code Draw` |
| **All-platform idea fragment collector** | **All-platform idea fragment collector** — Send flash ideas anytime, auto-tag and file into correct Notion creative project. <br> **核心能力:** `Multi-endpoint Input` `NLP Classification` `Knowledge API Write` |
| **Music composition chord recommendation** | **Music composition chord recommendation** — Input melody direction or mood, recommend 3 chord progression arrangements. <br> **核心能力:** `Domain Knowledge (Music Theory)` `Logic Derivation` |
| **Personal e-book EPUB one-click packaging** | **Personal e-book EPUB one-click packaging** — Combine Markdown chapters and cover image into standard EPUB via local script. <br> **核心能力:** `Directory Parsing` `Compile Script Execution` |
| **AI assistant self-"weekly review & evolution"** | **AI assistant self-"weekly review & evolution"** — Agent reviews its own execution logs, generates "how to give me better instructions" report. <br> **核心能力:** `Self-reflection` `Long-text Summary` `NLG` |

---

## Whitepaper

*[Full detail tables →](use-cases/whitepaper/README.md)*

The **WorkBuddy 100-Case Whitepaper** provides structured tables (case name / scenario / core capabilities) across 10 subcategories.

| Part | Category | Cases | Highlight |
|---|---|:---:|---|
| Office 1 | Administration | 01–10 | Smart inbox cleanup, automated meeting loop |
| Office 2 | Finance, Legal & HR | 11–20 | Invoice OCR reimbursement, smart resume screening |
| Office 3 | R&D & Ops | 21–30 | Autonomous bug fix PR, distributed log monitoring |
| Office 4 | Sales & Customer Success | 31–40 | Prospect web harvesting, smart CRM sync |
| Office 5 | Data & Research | 41–50 | Financial report analysis, knowledge base auto-tagging |
| Creative 1 | Writing & Editing | 51–60 | Deep research report agent, style transfer engine |
| Creative 2 | Visual Art & Design | 61–70 | Midjourney batch experiment, UI design → code |
| Creative 3 | Audio & Video | 71–80 | Short-video remix agent, podcast post-production |
| Creative 4 | Social Media Ops | 81–90 | Multi-platform distribution, giveaway full loop |
| Creative 5 | Experimental | 91–100 | Personal digital twin, self-optimizing workflow |

[→ View full whitepaper](use-cases/whitepaper/README.md)

---

## Agent Capability Map

A cross-reference of which capabilities appear most across all 230+ cases.

| Capability | Frequency | Representative Cases |
|---|:---:|---|
| 🌐 Browser Automation | 30+ | Resume screening, flight check-in, contract download |
| 📁 Local File Read/Write | 35+ | Invoice archiving, asset organization, knowledge index |
| ⏰ Scheduled Task | 25+ | Morning brief, competitor monitoring, expiry reminders |
| 🧠 NLP / LLM Analysis | 50+ | Sentiment analysis, semantic comparison, summarization |
| 🔌 API Integration | 30+ | CRM sync, calendar write, payment platforms |
| 💻 Code Execution | 25+ | Data viz, image rendering, script automation |
| 👁️ OCR / Multimodal | 20+ | Invoice OCR, whiteboard photos, UI screenshot |
| 🗄️ Vector DB / RAG | 15+ | Policy Q&A, patent scan, literature tracking |
| 📧 Email Automation | 15+ | Attachment archiving, reply drafting, batch send |
| 🔄 Workflow Orchestration | 40+ | Onboarding pipeline, event full-loop, offboarding |

---

## How to Use This List

1. **Find your role** → Jump to [By Profession](#by-profession), copy the scenario and give it to WorkBuddy.
2. **Search by task** → Use [By Task Type](#by-task-type) to find automation by the type of work you want to automate.
3. **Build a custom Agent** → Use the [Capability Map](#agent-capability-map) to identify what tools your Agent needs.
4. **Go deep** → The [Whitepaper tables](use-cases/whitepaper/README.md) include full structured detail for 100 cases.
5. **Contribute** → Add your own cases via [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Contributing

Contributions are welcome! If you have a real-world automation scenario that WorkBuddy or any AI Agent can handle, please share it.

Read the [Contributing Guide →](CONTRIBUTING.md)

---

## License

[MIT](LICENSE) © Awesome WorkBuddy Use Cases Contributors
