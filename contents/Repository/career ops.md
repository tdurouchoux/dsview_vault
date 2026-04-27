---
already_read: true
link: https://github.com/santifer/career-ops
read_priority: 0
relevance: 5
source: Alpha Signal
tags:
- AI_agent
type: Content
upload_date: '2026-04-27'
---

https://github.com/santifer/career-ops
## Summary

**Career-Ops** is an open-source, AI-powered job search system built on **Claude Code** and **Gemini CLI**, designed to automate and optimize the job application process. It evaluates job offers using a structured **A-F scoring system** (10 weighted dimensions), generates **ATS-optimized PDF resumes**, scans job portals (e.g., Greenhouse, Ashby, Lever), and processes applications in **batch mode**.

### **Key Features**
- **Auto-Pipeline**: Evaluates job URLs/descriptions, generates tailored CVs, and tracks applications.
- **6-Block Evaluation**: Assesses role fit, CV match, compensation, and interview prep (STAR+R method).
- **Interview Story Bank**: Accumulates behavioral stories (STAR+Reflection) for interviews.
- **Negotiation Scripts**: Provides salary negotiation frameworks and counter-offer strategies.
- **ATS PDF Generation**: Creates keyword-optimized resumes using Space Grotesk + DM Sans.
- **Portal Scanner**: Supports 45+ companies (e.g., Anthropic, OpenAI, Retool) and job boards (Ashby, Greenhouse).
- **Batch Processing**: Parallel evaluation with sub-agents.
- **Dashboard TUI**: Terminal-based UI for tracking applications.
- **Human-in-the-Loop**: AI recommends, user decides—no auto-submissions.

### **Tech Stack**
- **Agent**: Claude Code / Gemini CLI
- **PDF Generation**: Playwright/Puppeteer + HTML templates
- **Scanner**: Playwright + APIs (Greenhouse, etc.)
- **Dashboard**: Go + Bubble Tea (TUI)
- **Data**: Markdown/YAML/TSV

### **Quick Start**
1. Clone repo, install dependencies (`npm install`).
2. Configure `profile.yml` and `portals.yml`.
3. Add CV (`cv.md`) and personalize via CLI.
4. Run `/career-ops` with job URLs/descriptions.

### **Use Cases**
- Evaluate job offers (scores <4.0 discouraged).
- Generate tailored resumes per job description.
- Scan portals for new postings.
- Track applications in a centralized dashboard.

### **Disclaimer**
- **Local tool**: No data collection; AI responses depend on user prompts.
- **Compliance**: Users must adhere to job portal ToS.
- **No guarantees**: AI may hallucinate; always review outputs.

**GitHub**: [santifer/career-ops](https://github.com/santifer/career-ops) | **License**: MIT
## Links

- [Gemini CLI Repository](https://github.com/google-gemini/gemini-cli) : Official repository for Google's Gemini CLI, which can be used as an alternative AI-powered CLI tool for running Career-Ops.
- [cv-santiago Portfolio](https://github.com/santifer/cv-santiago) : Portfolio website of the author, featuring AI-powered tools, case studies, and a personal website template.
- [Career-Ops Official Website](https://career-ops.org) : Official website for Career-Ops, providing additional details, documentation, and updates about the project.
- [Santifer's Personal Website](https://santifer.io) : Personal website of Santiago, the creator of Career-Ops, featuring career-related tools and projects.

## Topics

![[topics/Tool/Playwright]]

![[topics/Platform/ATS Applicant Tracking System]]

![[topics/Library/Bubble Tea]]

![[topics/Library/Lipgloss]]

![[topics/Concept/Terminal User Interface TUI]]

![[topics/Tool/Go]]

![[topics/Tool/Claude Code]]

![[topics/Concept/Agentic Workflows]]