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

| # | Case | Key Capabilities |
|---|---|---|
| 1 | **Daily financial report summary** — Scheduled scraping, extract core data, send summary to Telegram. | `Scheduling` `Web Scraping` `NLP` |
| 2 | **Invoice auto-reimbursement entry** — Monitor email folder, OCR invoices, auto-submit to OA system. | `File Monitoring` `OCR` `API Call` |
| 3 | **Competitor price monitoring** — Scheduled scraping of e-commerce pages, auto-update local CSV. | `Scheduling` `Web Scraping` `File I/O` |
| 4 | **Sales leads (CRM) cleaning** — Read CRM export, remove invalids, deduplicate, tag by industry. | `File I/O` `Code Execution` `NLP` |
| 5 | **Real-time multi-currency quote calculation** — Auto-query live exchange rates and compute on demand. | `API Call` `NLP` `Logic` |
| 6 | **Auto-write weekly report draft** — Every Friday, extract calendar/Git/email activity, generate report. | `Multi-source API` `Memory` `NLG` |
| 7 | **Business report anomaly alert** — Read monitoring output, alert when conversion rate drops. | `File Monitoring` `Logic` `Push Notification` |
| 8 | **Desktop file auto-organization** — One-click classify and rename documents in Downloads by content. | `File I/O` `NLP` `Shell Commands` |
| 9 | **Cross-platform task status sync** — Auto-sync Notion project progress updates to Jira. | `Cross-platform API` `Data Mapping` |
| 10 | **Meeting recording → action items** — Extract Action Items from transcript, write to Todoist. | `File I/O` `NLP` `API Call` |
| 11 | **Employee attendance anomaly stats** — Calculate and filter late/early departure records from raw data. | `File I/O` `Code Execution` |
| 12 | **Morning industry news brief** — Daily 7am: collect top-5 industry news, summarize, send to group. | `Scheduling` `Web Search` `NLG` |
| 13 | **Customer service chat sentiment analysis** — Batch-read previous day's chats, score service quality. | `Batch File Read` `NLP Sentiment` |
| 14 | **Local data auto-visualization** — From CSV in chat, auto-write Python to generate charts. | `Code Generation` `Code Execution` `File I/O` |
| 15 | **Server/website status probe** — Periodically ping company website, alert via WhatsApp if down. | `Scheduling` `HTTP Request` `Push Notification` |

### 2. Document Management & Deep Reading

> `PDF Parsing` `RAG` `OCR` `Semantic Comparison` `File Monitoring`

| # | Case | Key Capabilities |
|---|---|---|
| 16 | **Long document immersive translation** — Translate hundreds-of-pages PDF maintaining terminology consistency. | `Large File Chunking` `Memory` `MT` |
| 17 | **Bidding document version comparison** — Compare two Word docs, highlight clause differences, output risk summary. | `File Parsing` `Semantic Diff` |
| 18 | **Legal contract initial risk review** — Auto-scan downloaded contract, identify unfavorable clauses. | `File Read` `Domain Knowledge` `NLP` |
| 19 | **Resume auto-screening** — Score all resume attachments from recruiting email vs JD, sort into table. | `Batch Processing` `OCR` `NLP Matching` |
| 20 | **Local knowledge base index building** — Monitor folder, extract tags and summaries from new docs, update index. | `Directory Monitoring` `Summarization` `File Write` |
| 21 | **Email attachment rule-based archiving** — Detect key client emails, auto-download attachments by year/project. | `IMAP` `File System` |
| 22 | **Complex data table split & distribute** — Split company-wide Excel by department, email to each head. | `Code Execution` `Email Send` |
| 23 | **Company policy "living dictionary"** — Use employee handbook as knowledge base to answer policy questions. | `Local RAG` `NLP` |
| 24 | **Historical chat & decision tracing** — Search long-term chat logs for past discussions with context. | `DB Search` `Long-term Memory` `NLP` |
| 25 | **Shared file co-sign tracking** — Monitor collaborative doc edits, remind unsigned stakeholders. | `Doc API` `Data Diff` `Scheduling` |
| 26 | **Sensitive data auto-masking** — Before sending, auto-detect and mask ID numbers, financial data. | `Regex` `NER` `File Rewrite` |
| 27 | **Product operation manual generation** — From PM notes and screenshots, generate structured user guide. | `Multimodal` `NLG` |
| 28 | **Whiteboard photo → structured notes** — OCR meeting whiteboard photo, convert to tidy Markdown. | `Vision/OCR` `Formatted Output` |
| 29 | **Long PPT → one-page summary** — Read 50-page PPT, extract core arguments and conclusions. | `Doc Parsing` `Summarization` |
| 30 | **Code / doc change summary** — Read Git commits or doc edits, generate readable release notes. | `Terminal/API` `Technical NLG` |

### 3. Communication & Scheduling

> `Calendar API` `Email Automation` `Timezone Logic` `Long-term Memory`

| # | Case | Key Capabilities |
|---|---|---|
| 31 | **Complex email intelligent drafting** — Given a complaint email and instruction, auto-generate professional reply. | `Context Understanding` `NLG Tone Control` |
| 32 | **Schedule conflict auto-coordination** — When meeting invite arrives, check calendar; reply with available slots if conflict. | `Calendar API` `Time Logic` `Auto-reply` |
| 33 | **Cross-timezone best meeting time** — Given US/EU/CN participants, exclude sleep hours, recommend intersection. | `Timezone Logic` `Data Filtering` |
| 34 | **Pre-meeting materials push** — 15 min before meeting, send link + last meeting's summary via IM. | `Scheduling` `Memory Retrieval` |
| 35 | **Business dinner restaurant recommendation** — Combine boss's dietary preferences, search nearby restaurants, send 3 options. | `Personal Memory` `Web Search` `API Call` |
| 36 | **Client visit route planning** — Read today's schedule addresses, calculate commute times, estimate departure. | `Maps API` `Time Calculation` `Notification` |
| 37 | **Focus mode message filtering** — During focus, take over chat app, only alert for "extremely urgent." | `IM API Monitoring` `NLP Priority` |
| 38 | **Cross-national group chat live translation** — Monitor all-English work group, translate core discussions to Chinese brief. | `Real-time Stream` `Machine Translation` |
| 39 | **Offboarding asset auto-collection** — On offboarding instruction, send form, compile all assets and handover links. | `RPA` `Info Aggregation` |
| 40 | **Client birthday / holiday custom greetings** — Daily scan CRM for birthdays, auto-generate personalized greetings. | `DB Query` `Scheduling` `Personalized NLG` |
| 41 | **Automated interview scheduling** — Multi-round email exchange with candidates, then calendar invite to interviewers. | `Multi-turn Dialog` `Calendar Write` |
| 42 | **Cross-department process gentle reminder** — Periodically check OA approvals stuck at a node, send polite follow-up. | `Page Scraping/API Poll` `High-EQ NLG` |
| 43 | **Visitor Wi-Fi auto-distribution** — Guest @s Agent in group, Agent verifies daily visitor list, DMs temp password. | `List Verification` `Trigger Response` |
| 44 | **IT/admin ticket initial triage** — Classify repair ticket intent, route to network or facilities team. | `Text Classification` `Routing Rules` |
| 45 | **Post-vacation "catch me up" context restore** — Ask "what did I miss," get progress and key decisions summary per project. | `Log Aggregation` `Summarization` |

### 4. Project Management & Research

> `Git Integration` `Jira/Trello API` `Web Search` `Vector DB` `Code Execution`

| # | Case | Key Capabilities |
|---|---|---|
| 46 | **Agile board daily inspection** — Read Jira/Trello, summarize "at-risk of delay" tasks, send to PM before end of day. | `PM API` `Data Filter` |
| 47 | **Fast Code Review assistant** — On new PR, auto-pull code, run basic checks, provide standards suggestions. | `Git/Shell` `Code LLM` `Static Analysis` |
| 48 | **Industry report auto-downloader** — Monitor consulting websites, download new reports matching keywords. | `Web Change Detection` `Auto Download` `File Mgmt` |
| 49 | **Patent & technical prior art scan** — Background-compare with public patent database for infringement risks. | `Vector DB` `Text Similarity` |
| 50 | **Competitor deep background check** — Input company name, auto-collect bid wins, negative news, executive changes. | `Deep Web Search` `Entity Extraction` |
| 51 | **Daily standup auto-facilitator** — At fixed time, @members in sequence, summarize each person's blockers. | `Scheduled Group Msg` `Dialog Summary` |
| 52 | **API docs auto-sync** — Monitor backend routing comment changes, auto-generate latest API docs. | `File Monitoring` `Code Parsing` |
| 53 | **PRD logic error-checking** — Check new PRD against historical docs, flag function contradictions or missing logic. | `Historical Text Diff` `Business Logic Reasoning` |
| 54 | **Online bug log clustering** — Denoise and cluster thousands of error logs, find top-3 root causes. | `Batch Data Processing` `ML Clustering` |
| 55 | **Non-standard vendor quote comparison** — Extract PDFs from multiple vendors, normalize parameters, generate comparison Excel. | `Complex Table OCR` `Data Alignment` |
| 56 | **Local disk space alert & cleanup** — Monitor disk; when near full, identify large useless log files and ask for confirmation. | `OS Commands` `Conditional Trigger` |
| 57 | **Vertical academic paper tracking** — Weekly auto-search arXiv/PubMed, generate translated abstracts list. | `Academic API` `PDF Processing` `Domain MT` |
| 58 | **Project budget burn monitoring** — Link invoice folder to budget table; alert when budget 80% consumed. | `Cross-file Calculation` `Threshold Trigger` |
| 59 | **Software license expiry reminder** — Read subscription list, auto-draft renewal email 30 days before expiry. | `DB Read` `Time Calculation` `Email Draft` |
| 60 | **App store review sentiment word cloud** — Pull latest reviews, segment words, generate pain point word cloud. | `Store Scraping` `Segmentation` `Image Gen` |

### 5. Copywriting & Creative Strategy

> `NLG Style Control` `Web Trending` `Long-form Planning` `Multi-language`

| # | Case | Key Capabilities |
|---|---|---|
| 61 | **Viral social title A/B generator** — Feed a dry draft, combine with trending words, generate 10 attention-grabbing titles. | `Trending Scraping` `Stylized NLG` |
| 62 | **SEO content optimization & rewrite** — Analyze existing blog post, optimize keyword density and structure. | `SEO Rules` `Text Restructuring` |
| 63 | **Large speech / launch event structuring** — Input key highlights, auto-derive PPT speaking outline with hook and closing. | `Logic Planning` `Long-form Framework` |
| 64 | **Corporate news release expander** — Turn sparse data points into a polished thousand-word PR article. | `NLG Register Mimicry` `Info Expansion` |
| 65 | **Brand origin story writing** — Combine founder quotes and early photos, craft emotionally resonant brand story. | `Multimodal` `Memory Synthesis` `Emotional NLG` |
| 66 | **B2B sales pitch customization** — Convert generic product intro into industry-specific pitches (medical/education/manufacturing). | `Vertical Domain Knowledge` `Text Adaptation` |
| 67 | **Cross-cultural transcreation** — Not just translate, but rewrite for Japanese or Middle East cultural context and idioms. | `Cross-cultural Context` `Deep NLP` |
| 68 | **PR crisis statement drafting** — When negative sentiment detected, generate "clarification + apology + measures" draft in 5 min. | `Crisis PR Template` `High-sensitivity NLG` |
| 69 | **Business plan (BP) professional polish** — Rewrite colloquial startup ideas into investor-facing copy with TAM and business model. | `Business Reasoning` `Professional Terminology` |
| 70 | **Brand slogan brainstorming engine** — Input selling points, use puns/rhymes/contrast to batch-generate memorable slogans. | `Rhetorical Modeling` `Short-text Creative Gen` |
| 71 | **Novel / script → storyboard script** — Auto-decompose novel text into "scene / character / dialogue / shot type" storyboard format. | `Text Structuring` `Film Industry Terms` |
| 72 | **Podcast show notes extraction** — From transcript, auto-extract timestamps, guest quotes, and mentioned links. | `Long-text Summary` `Entity Extraction` |
| 73 | **Marketing copy multi-platform adaptation** — Same event auto-generates WeChat Moments / Xiaohongshu / Zhihu versions. | `Platform Tone Learning` `Multi-style Conversion` |
| 74 | **Long-form fiction setting consistency check** — Monitor setting database; alert if character/world details contradict earlier chapters. | `Knowledge Graph` `Long-context Consistency` |
| 75 | **Interactive game plot multi-branch derivation** — Given a key plot decision, derive 3 outcomes matching character personalities. | `Character Model` `Logic Branch Reasoning` |

### 6. Social Media & Marketing Automation

> `Browser Automation` `RPA` `IM API` `Real-time Monitoring`

| # | Case | Key Capabilities |
|---|---|---|
| 76 | **Xiaohongshu "trendy" post direct output** — Upload product photo, auto-add emoji-heavy review copy. | `Visual Feature Extract` `Stylized NLG` |
| 77 | **Short-video golden 3-second script** — Scrape TikTok/Douyin trends, generate hook script and camera direction. | `Trend Scraping` `Audio-visual Language` |
| 78 | **Social media fan humanized auto-reply** — Randomly humanized auto-reply to common repetitive questions. | `API Monitoring` `Intent ID` `Varied Reply` |
| 79 | **Competitor social media viral post analysis** — Daily scrape competitor's top posts, reverse-engineer topic angle. | `Web Data Scraping` `Attribution NLP` |
| 80 | **Matrix account one-click content distribution** — Put article in folder, auto-publish to WeChat / Zhihu / Toutiao. | `File Monitoring` `RPA or API` |
| 81 | **Full giveaway campaign management** — Auto-post giveaway, clean fake accounts, randomly select real fans, DM winners. | `Platform API` `Code Execution` `Random Algo` |
| 82 | **Brand annual marketing calendar reminders** — One week ahead, push brand-aligned marketing copy and strategy for holidays. | `Long-term Calendar Memory` `Scheduling` `Creative Synthesis` |
| 83 | **Live room moderation & comment distillation** — Real-time ingest comment stream, auto-ban toxic words, surface top-3 audience questions. | `Stream Processing` `Sensitive Word Filter` `Aggregation` |
| 84 | **Viral poster dynamic update** — Based on user's referral tier, auto-run script to replace invite code and copy in poster. | `Image Processing Lib` `Dynamic Synthesis` |
| 85 | **KOL batch custom outreach** — Import blogger list, batch-generate heartfelt collaboration invites praising specific posts, and send. | `Web Content Quick Read` `Email Automation` `NLG` |
| 86 | **Trending event rapid content creation** — On industry-related hot topic, generate high-quality commentary draft in 10 min. | `High-frequency Monitoring` `Rapid Gen` |
| 87 | **Real user UGC collection net** — Auto-search all brand mentions, compile positive-sentiment image-text screenshots. | `Full Web Search` `Sentiment Classification` `Screenshot` |
| 88 | **Executive / IP persona WeChat script** — Custom daily posting plan, remind and provide draft for one-click publish. | `Persona Prompt Tuning` `Scheduled Task Mgmt` |

### 7. Multimedia, Design & Code Support

> `Image Processing` `Code Gen` `Shell/FFmpeg` `Vector DB` `Multimodal`

| # | Case | Key Capabilities |
|---|---|---|
| 89 | **AI image prompt enhancer** — Input "cyberpunk girl," expand to full Midjourney prompt with lighting and engine params. | `Prompt Engineering` `Design Vocabulary` |
| 90 | **Local untagged asset library natural language search** — Scan thousands of unnamed assets, add vector tags, search by description. | `Multimodal Tagging` `Local Vector DB` |
| 91 | **Video rough-cut marking** — From audio transcript, auto-cut silent segments, record valid segment timestamps for editor. | `Audio-video Transcript` `Logic Calculation` |
| 92 | **Virtual voice-over TTS pre-processing** — Convert colloquial text to TTS-ready format, annotate emphasis and pauses. | `Phonology Rules` `SSML Format Output` |
| 93 | **Event invitation batch auto-synthesis** — Read 100-person CSV, run Python with design template, render 100 personalized invitation images. | `Code Execution (Image Render)` `Batch File Write` |
| 94 | **Hand-drawn sketch → front-end prototype** — Send whiteboard sketch photo, Agent generates running HTML/Tailwind CSS page. | `Visual Layout Understanding` `Code Gen` `Local Preview` |
| 95 | **Animation script keyframe timeline calculation** — Based on VO script, calculate speaking pace, generate timestamped keyframe script for AE. | `Data Calculation` `Specific File Format Gen` |
| 96 | **Complex game plot tree visualization** — Read branching story text, auto-convert to Mermaid code, render into flow network. | `Logic Topology Extract` `Mermaid Code Draw` |
| 97 | **All-platform idea fragment collector** — Send flash ideas anytime, auto-tag and file into correct Notion creative project. | `Multi-endpoint Input` `NLP Classification` `Knowledge API Write` |
| 98 | **Music composition chord recommendation** — Input melody direction or mood, recommend 3 chord progression arrangements. | `Domain Knowledge (Music Theory)` `Logic Derivation` |
| 99 | **Personal e-book EPUB one-click packaging** — Combine Markdown chapters and cover image into standard EPUB via local script. | `Directory Parsing` `Compile Script Execution` |
| 100 | **AI assistant self-"weekly review & evolution"** — Agent reviews its own execution logs, generates "how to give me better instructions" report. | `Self-reflection` `Long-text Summary` `NLG` |

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
