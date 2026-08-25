# Talk Track — What Can Gemini Enterprise Do?

## Slide 1: Title — "What Can Gemini Enterprise Do?"

> **Time:** ~1 minute

"Today I want to show you the full breadth of what Gemini Enterprise can do for your institution — not just chat, but nine distinct capabilities that cover everything from analyzing your research data to building custom AI agents for your campus.

We'll walk through three groups: Content & Research tools, Knowledge & Discovery tools, and Platform & Extensibility — and then I'll show you several of these live."

---

## Slide 2: File Analysis & Code Generation

> **Time:** ~2 minutes

"You already know Gemini can chat. Here's what's different in Gemini Enterprise.

*[reveal file upload card]* First: **file analysis.** Drop a CSV, a PDF, a spreadsheet — any document — and Gemini reads the actual content. This isn't summarizing a title. It's parsing a 10,000-row enrollment dataset and telling you which programs are declining. It's reading a 40-page grant RFP and pulling out the eligibility criteria. Your data never leaves your Google Workspace tenant.

*[reveal code generation card]* Second: **code generation from your data.** Upload that enrollment CSV and say 'write me a Python script to forecast next year's enrollment by program.' You get working code. SQL queries against your data. Visualization scripts. From raw institutional data to working analysis in one prompt — no data science team required.

*[reveal cross-reference card]* Third — and this is the one that surprises people: **cross-referencing.** Upload multiple documents in the same conversation. Upload last year's budget memo AND this year's enrollment data and ask 'which programs lost students but gained funding?' Gemini connects the dots across files."

---

## Slide 3: Multi-Model Access

> **Time:** ~2 minutes

"This is the capability that makes Gemini Enterprise a platform, not just a chatbot.

*[reveal flow diagram]* Look at this architecture. In the center: Gemini Enterprise — your secure hub. On the left: Claude from Anthropic, connected through the platform. On the right: other partner and open models.

Why does this matter? Because different models are better at different things. Claude excels at nuanced reasoning and careful analysis. Gemini excels at multimodal understanding and Google integration. Some models are better at code. Some at creative writing. Multi-model access means your faculty and staff pick the best tool for each job — all through one interface, all under one governance layer.

*[reveal benefits row]* Three things that matter for IT leadership: One — single governance. All models flow through your institution's policies, logging, and compliance. Two — best-of-breed. Your researchers get the best model for each task without managing multiple accounts. Three — data stays in your tenant. No third-party data exposure, regardless of which model processes the request."

---

## Slide 4: External Connectors & Custom Agents

> **Time:** ~3 minutes

"Now here's where Gemini Enterprise goes from a tool your people use to a platform your institution builds on.

*[reveal connectors]* **External Connectors.** You can plug Gemini into your existing systems — your SIS, your LMS, your CRM, your HR platform, your research databases. This means someone in admissions can ask Gemini a natural language question like 'how many transfer students from community colleges enrolled in STEM programs last fall?' and get an answer — without writing SQL, without exporting data, without waiting on an analyst.

*[reveal data card]* Your institutional data becomes AI-ready. Query it through conversation.

*[reveal custom agents]* **Custom Agents.** These aren't simple chatbots — these are purpose-built AI agents that connect to your systems, follow multi-step workflows, and take actions. Three examples that are live at institutions right now:

**Grants AI** — discovers funding opportunities matched to a faculty member's research profile, checks eligibility against your institution's constraints, and helps draft proposals in the funder's required format.

**AI Tutor** — we'll dive deeper into this on the next slide, but this is a personalized learning agent built on YOUR course content.

**Admissions Agent** — automates application triage, surfaces anomalies, routes files to the right reviewer."

---

## Slide 5: Student Lifecycle — "We Used to Have to Build This from Scratch"

> **Time:** ~2-3 minutes

"Now here's the bigger picture. Universities have been trying to build an AI platform for student success for years — one that covers the entire lifecycle from attracting and enrolling students, to supporting and engaging them, all the way through graduation and employment.

*[reveal lifecycle bar]* This is the student journey. Three phases: Attract and Enroll, Support and Engage, Graduate, Complete, Employ. Every university has this funnel.

*[reveal integrations bar]* To make AI work across this lifecycle, you need back-end integrations — your student information system, your LMS, your CRM, your internal databases. That's the plumbing.

*[reveal AI capabilities]* Then you layer on the AI capabilities. On the enrollment side: automated admissions processing — AI that reads applications, scores candidates, routes paperwork. In the middle: student analytics, 24/7 AI support, and automated tutoring built on YOUR course content. And on the graduation side: AI for employability — career matching, alumni engagement, donation outreach.

*[reveal platform bar]* All of this runs on Google Cloud Platform — secure, compliant, intelligent. The data governance, the identity management, the audit logging — it's all there.

The point is: institutions used to have to build every one of these boxes from scratch. Custom engineering, custom integrations, months of development. With Gemini Enterprise, several of these capabilities come out of the box. Let me show you the one that gets the most excitement."

---

## Slide 6: AI Tutor — No Custom Build Required

> **Time:** ~3 minutes

"This is the one faculty love. An AI Tutor that runs on YOUR content — not general internet knowledge.

*[reveal top cards]* Two key things make this work. First: **Your Content, Your Tutor.** Upload your syllabi, your textbooks, your lecture notes. The tutor answers student questions grounded only in YOUR materials. No hallucinations, no random internet answers — just your curriculum. This is NotebookLM under the hood.

Second: **24/7 Student Support.** It's 2 AM during finals week. Office hours are over. The TA is asleep. Your AI Tutor is still answering questions, explaining concepts, and generating practice problems. For large lecture classes with 300+ students, this is transformative.

*[reveal bottom cards]* It's also **adaptive** — a freshman asking about thermodynamics gets a different explanation than a senior. The tutor meets each student where they are. And it generates **practice questions and step-by-step solutions** for exam prep.

*[reveal built-on bar]* Here's the key message: **this is built with Gemini Enterprise Gems and NotebookLM.** No engineering team required. A faculty member can set this up in an afternoon. Create a Gem with your course instructions, load your materials into NotebookLM, and your students have a tutor. That's the shift — what used to require a custom software project is now a configuration task."

---

## Slide 7: Demos

> **Time:** Transition slide

"Now let me show you several of these in action. I'll walk through the tools live so you can see exactly how they work."

**Recommended demo order (for a 30-minute demo session):**

| # | Demo | Time | Key Moment |
|---|------|------|------------|
| 1 | AI Assistant — File Analysis | 5-7 min | Upload CSV + PDF, cross-reference |
| 2 | Grounded Web Search | 3-5 min | Live grant/literature search |
| 3 | Research Agents (Gems) | 5-7 min | Create a Gem live |
| 4 | NotebookLM | 5-7 min | Upload 3 papers, generate Audio Overview |
| 5 | Deep Research | 3-5 min | Launch query, discuss while it runs |

**Tips:**
- Have all demo files pre-downloaded and ready
- Test PDF uploads and Audio Overview generation before the session
- For Deep Research, launch the query early — discuss results when they arrive
- Keep a "prompt cheat sheet" tab open for audience Q&A

---

## Slide 8: Thank You

> **Time:** ~1 minute

"That's the full picture — nine capabilities, one platform, all secured within your institution's Google Workspace.

Whether you're a researcher analyzing data, a PI building lab tools, or an administrator evaluating AI for your campus — Gemini Enterprise has something for you.

I'd love to schedule a deeper dive with your team, set up a pilot program, or just answer questions. Let's talk."
