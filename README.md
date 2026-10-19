<div align="center">

# Hi, I'm Manny 👋

### Technical SEO / AEO · Automation · Web Systems · Applied AI

I work at the intersection of **search, data, content architecture, and the web**.

My background spans agency SEO, full-stack development, consulting, and machine-learning evaluation, so I’m comfortable working with marketers, developers, data-minded teams, and the systems connecting them.

<a href="https://www.mannyroy.com">
  <img alt="Manny Roy Consulting" src="https://img.shields.io/badge/Manny_Roy_Consulting-FAF6F0?style=for-the-badge&logoColor=2A261A" />
</a>
<a href="https://www.linkedin.com/in/amandadroy">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-3F6AA8?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:manny@mannyroy.com">
  <img alt="Email Manny" src="https://img.shields.io/badge/Email-D56B5B?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

📍 Prince Edward Island, Canada

</div>

---

## What I Do

I like taking recurring problems apart, figuring out **why they happen**, and building systems that make processes easier to run, measure, and maintain.

My work commonly includes:

- 🔎 **Technical SEO & AEO** — crawlability, indexation, information architecture, content systems, internal linking, migrations, structured data, AI-search experimentation
- 📊 **Data & measurement** — GA4, Search Console, Looker Studio, Tableau, SQL/BigQuery, Python, API-driven analysis
- ⚙️ **Automation & internal tooling** — CLI tools, reporting workflows, data pipelines, API integrations, repeatable QA
- 🤖 **Applied AI** — LLM APIs, RAG, prompt engineering, evaluation, coding agents, human-in-the-loop workflows
- 🌐 **Web systems** — Ghost, WordPress/WooCommerce, Next.js, TypeScript, CMS architecture, DNS/CDN, accessibility
- ✍️ **Technical content** — B2B SaaS, web and AI topics, documentation, glossaries, content architecture, editorial systems

> **The stack varies; holistic thinking doesn’t.**

---

## Featured Work

### 🔎 [Canadian AI-Driven RFP Finder](https://github.com/amandadr/rfp-finder)

**Python · APIs · SQLite · LLM scoring · CLI · document processing**

A pipeline for finding and ranking Canadian public-sector RFP and tender opportunities.

It currently handles:

- CanadaBuys ingestion and incremental fetching
- persistence, deduplication, and amendment tracking
- configurable business profiles and eligibility rules
- explainable filtering and scoring
- optional OpenAI / Ollama relevance scoring
- PDF attachment extraction and enrichment
- CLI workflows and automated testing

While it has a few edges to sharpen, this is one of my favourite examples of turning a messy, repetitive research problem into something structured, inspectable, and reusable.

---

### 🚚 [WooCommerce → Trexity Automation](https://github.com/amandadr/woo-trexity-plugin)

**PHP · WordPress · WooCommerce · REST APIs · Action Scheduler · production automation**

A modular WordPress plugin built to automate local-delivery fulfillment between WooCommerce and Trexity.

After an eligible WooCommerce order is paid, the plugin validates the order against delivery, cart, payment, and duplicate-submission rules before creating the shipment through Trexity's API.

It handles considerably more than a simple API call:

- maps WooCommerce shipping methods to Trexity service types
- validates local-delivery eligibility and cart rules
- prevents duplicate shipment creation
- schedules pickup windows in the merchant's timezone
- handles alcohol-specific delivery requirements
- supports both classic WooCommerce checkout and WooCommerce Blocks
- stores shipment IDs, tracking information, errors, and skip reasons on the order
- provides manual and queued submission workflows through Action Scheduler
- includes authenticated API handling, retries, and transport fallbacks
- declares WooCommerce High-Performance Order Storage compatibility
- exposes filters and actions so behaviour can be adapted without modifying plugin internals

The repository also includes documentation for the architecture, configuration, checkout logic, eligibility rules, and extension hooks.

This is a good example of a real operational problem, several systems that need to agree with each other, and enough edge cases that the automation has to earn trust before it can save anyone time.

➡️ [Explore the plugin](https://github.com/amandadr/woo-trexity-plugin)

---

### 🧭 [Manny Roy Consulting Ghost Theme](https://github.com/amandadr/mrc-ghost-custom)

**Ghost · Handlebars · JavaScript · content architecture · technical SEO**

The custom theme and content architecture behind [mannyroy.com](https://www.mannyroy.com).

Beyond styling, it includes:

- custom Ghost routing
- a structured technical glossary
- audience and resource collections
- SEO-conscious information architecture
- accessibility work
- local development tooling
- living technical documentation
- public documentation at [docs.mannyroy.com](https://docs.mannyroy.com)

I use the site as a practical test bed for **SEO, GEO/AEO, internal linking, content architecture, publishing systems, and technical experimentation** while marketing my own services.

---

### 🎨 [Organized Chaos Arts](https://github.com/amandadr/organized-chaos-arts)

**Next.js · TypeScript · Sanity · Tailwind · architecture documentation**

A developing platform for an arts organization I'm co-founding, built around maintainable content architecture and eventual membership functionality.

The repository includes:

- Next.js App Router
- Sanity-backed editorial content
- documented design tokens
- architecture and content-model documentation
- ADRs for technical decisions
- Relume-based component foundations
- an `AGENTS.md` workflow for coding agents and Cursor

This project is a good example of how I like to work with AI-assisted development: **the agent can move quickly, but the architecture and rules stay explicit and human-approved**.

---

### 🗺️ [The Good Detour - Travel Merchant](https://github.com/amandadr/hyrule-merchant)

**Astro · API ingestion · Zod · data validation · testing**

A noncommercial portfolio prototype built around a snapshot of the Hyrule Compendium API. Rather than build a compendium, I wanted to exercise my creativity and lean into a static ecommerce prototype where travellers of Hyrule can prep themselves for the journey ahead.

What makes this one interesting to me is the data layer:

- API snapshots are ingested separately from the application
- Zod validates and normalizes source records
- source facts stay separate from invented shop data
- dated snapshots preserve provenance
- the site can build against the last known-good dataset without depending on a live API

It’s a playful take on an API system, but the UX and architecture reflect something I care about professionally: **knowing where information came from, what was transformed, what was invented, and how it's percieved**. While I can't share proprietary tooling, this portfolio piece can highlight these skills and help you take on a White Maned Lynel.

---

### ⚔️ [Hyrule Compendium](https://github.com/amandadr/hyrule-compendium)

**JavaScript · APIs · AWS Lambda · fuzzy search · Docker**

An older project that still earns a spot because it shows where a lot of my web instincts started.

Features include:

- API-driven content
- category browsing and detailed records
- typo-tolerant fuzzy search
- a Lambda-hosted search helper
- Dockerized deployment
- responsive UI

➡️ [View the live project](https://hyrule.amandadroy.com)

---

## Current Focus

<table>
<tr>
<td width="50%" valign="top">

### 🔍 Search & Content Systems

- Technical SEO
- AEO / GEO experimentation
- Content architecture
- Structured knowledge
- Internal linking
- Search and AI visibility
- Technical publishing systems

</td>
<td width="50%" valign="top">

### ⚙️ Tooling & Automation

- Python and SQL
- BigQuery
- APIs
- Cursor / coding agents
- RAG
- LLM evaluation
- Repeatable analysis workflows

</td>
</tr>
</table>

---

## Tools I Reach For

### Search & Measurement

<p>
  <img alt="Google Search Console" src="https://img.shields.io/badge/Search_Console-3C7A89?style=flat-square&logo=google&logoColor=white" />
  <img alt="Google Analytics" src="https://img.shields.io/badge/GA4-3F6AA8?style=flat-square&logo=googleanalytics&logoColor=white" />
  <img alt="Screaming Frog" src="https://img.shields.io/badge/Screaming_Frog-7A8E2B?style=flat-square&logoColor=white" />
  <img alt="Ahrefs" src="https://img.shields.io/badge/Ahrefs-E76F51?style=flat-square&logoColor=white" />
  <img alt="SEMrush" src="https://img.shields.io/badge/SEMrush-D56B5B?style=flat-square&logoColor=white" />
  <img alt="Looker Studio" src="https://img.shields.io/badge/Looker_Studio-6B4E71?style=flat-square&logo=looker&logoColor=white" />
</p>

### Code & Data

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3C7A89?style=flat-square&logo=python&logoColor=white" />
  <img alt="SQL" src="https://img.shields.io/badge/SQL-3A5A40?style=flat-square&logo=postgresql&logoColor=white" />
  <img alt="BigQuery" src="https://img.shields.io/badge/BigQuery-3F6AA8?style=flat-square&logo=googlebigquery&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-6B4E71?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-E8C868?style=flat-square&logo=javascript&logoColor=2A261A" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-2A261A?style=flat-square&logo=github&logoColor=white" />
</p>

### AI & Automation

<p>
  <img alt="Cursor" src="https://img.shields.io/badge/Cursor-2A261A?style=flat-square&logoColor=white" />
  <img alt="OpenAI" src="https://img.shields.io/badge/LLM_APIs-3A5A40?style=flat-square&logo=openai&logoColor=white" />
  <img alt="RAG" src="https://img.shields.io/badge/RAG-3C7A89?style=flat-square&logoColor=white" />
  <img alt="Prompt engineering" src="https://img.shields.io/badge/Prompt_Engineering-C76D3A?style=flat-square&logoColor=white" />
  <img alt="Workflow automation" src="https://img.shields.io/badge/Workflow_Automation-6B4E71?style=flat-square&logoColor=white" />
</p>

### Web Systems

<p>
  <img alt="Ghost" src="https://img.shields.io/badge/Ghost-2A261A?style=flat-square&logo=ghost&logoColor=white" />
  <img alt="WordPress" src="https://img.shields.io/badge/WordPress-3F6AA8?style=flat-square&logo=wordpress&logoColor=white" />
  <img alt="WooCommerce" src="https://img.shields.io/badge/WooCommerce-6B4E71?style=flat-square&logo=woocommerce&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-2A261A?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img alt="Sanity" src="https://img.shields.io/badge/Sanity-D56B5B?style=flat-square&logo=sanity&logoColor=white" />
</p>

---

## Writing & Research

When I have the gusto, I write about what I'm working on at [**mannyroy.com/blog**](https://www.mannyroy.com/blog/).

I’m especially interested in:

- technical SEO and AI search
- content architecture and information retrieval
- sustainable web ownership
- accessibility and performance
- applied AI and automation
- explaining web concepts without assuming the reader already speaks fluent developer

I’m also building a public [**web glossary**](https://www.mannyroy.com/glossary/) with **200+ entries across 13 topic collections**, written for both general and technical readers.

---

<details>
<summary><strong>A little more about how I work</strong></summary>

<br>

I like small teams, useful documentation, and knowing why a system works instead of merely knowing which button to press.

A lot of my work follows the same loop:

**investigate → prioritize → build → validate → measure → improve**

I’m particularly fond of tools that remove repetitive work while leaving important judgment with the person responsible for the outcome.

Woodworking has probably reinforced that more than anything else:

> **Measure twice, cut once.**

Investigate before concluding. Test before shipping. Communicate risk before it becomes somebody else’s surprise.

</details>

---

## Connect

<div align="center">

I run [**Manny Roy Consulting**](https://www.mannyroy.com) from Prince Edward Island.

If you're nearby, I'm always happy to grab a coffee.  
If you're not, the internet works too.

<br>

<a href="https://www.linkedin.com/in/amandadroy">
  <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-3F6AA8?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://www.mannyroy.com">
  <img alt="Website" src="https://img.shields.io/badge/mannyroy.com-E8C868?style=for-the-badge&logoColor=2A261A" />
</a>
<a href="mailto:manny@mannyroy.com">
  <img alt="Email" src="https://img.shields.io/badge/Email-D56B5B?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br><br>

*Build once. Maintain well.*

</div>
