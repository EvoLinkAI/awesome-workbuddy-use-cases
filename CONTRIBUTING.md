# Contributing Guide

Thank you for helping make this the most comprehensive AI Agent use case library!

**Language:** English | [简体中文](CONTRIBUTING.zh-CN.md)

---

## How to Contribute

### 1. Fork & Clone

```bash
git clone https://github.com/YOUR_USERNAME/awesome-workbuddy-use-cases.git
cd awesome-workbuddy-use-cases
```

### 2. Find the Right File

Place your case in the most relevant file:

| Your use case type | File |
|---|---|
| Organized by job role | `use-cases/by-profession/` |
| Organized by task type | `use-cases/by-task/` |
| Detailed whitepaper entry | `use-cases/whitepaper/` |

Also add a summary line in `README.md` under the relevant section.

### 3. Use the Template

#### For README / by-task files:

```markdown
| N | **[Case Name]** — [One-sentence scenario description]. | `Capability 1` `Capability 2` `Capability 3` |
```

Example:
```markdown
| 101 | **Email digest auto-send** — Every morning, summarize unread emails by priority and send a digest to your phone. | `IMAP` `NLP Classification` `Push Notification` |
```

#### For by-profession files:

```markdown
- **[Case Name]** — [Scenario description in English.]
```

#### For whitepaper table files:

```markdown
| **[Case Number]. [Case Name]** | [Detailed scenario description — what triggers it, what it does, what it produces.] | **[Capability 1]**、[Capability 2]、[Capability 3]. |
```

---

## Case Quality Checklist

Before submitting, verify your case meets these criteria:

- [ ] **Specific and actionable** — Not "help me work better" but "read CSV, calculate anomalies, email report."

- [ ] **Names concrete inputs and outputs** — What file/data goes in? What file/message/action comes out?

- [ ] **Real workflow, not hypothetical** — Based on a task that someone actually does regularly.

- [ ] **Correct Agent capabilities labeled** — The capability tags should reflect what the Agent actually needs.

- [ ] **Not a duplicate** — Search the repo for similar cases before adding.

---

## Submitting a PR PR

1. Create a new branch: `git checkout -b add-case-[brief-name]`
2. Make your changes
3. Commit: `git commit -m "Add: [case name] to [section]"`
4. Push and open a Pull Request

**PR title format:** `Add: [Case Name] — [Section]`

Example: `Add: Automated lease renewal reminder — by-profession/real-estate`

---

## Capability Tag Reference

Use consistent tags so cases are easily searchable:

| Tag | Meaning |
|---|---|
| `Browser Automation` | Controlling web browsers, form filling, scraping |
| `File I/O` | Reading/writing local files |
| `Shell Execution` | Running terminal/command-line commands |
| `Code Execution` | Running Python, JS, or other scripts |
| `API Call` | Calling external REST APIs |
| `OCR` | Optical character recognition from images/PDFs |
| `Multimodal` | Processing images, audio, or video |
| `NLP` | Natural language understanding/classification |
| `NLG` | Natural language generation / text writing |
| `Scheduling` | Time-based triggers, cron jobs |
| `File Monitoring` | Watching directories for changes |
| `Email Automation` | Sending/reading emails via IMAP/SMTP |
| `Calendar API` | Reading/writing calendar events |
| `Vector DB / RAG` | Semantic search over local knowledge bases |
| `Memory` | Persistent long-term information recall |
| `Push Notification` | Sending alerts via Telegram, WhatsApp, etc. |
| `Image Processing` | Manipulating images with libraries like Pillow |
| `Git/Shell` | Git operations, code repository management |
| `RPA` | Robotic process automation for legacy systems |
| `Workflow Orchestration` | Multi-step, multi-tool pipelines |

---

## Questions?？

Open an [Issue](../../issues) or start a [Discussion](../../discussions).
