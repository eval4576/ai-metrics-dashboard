# AI Product Metrics Dashboard
### A live metrics dashboard with AI-generated product narratives for PM standups and leadership updates

**Live Demo → [eval4576.github.io/ai-metrics-dashboard](https://eval4576.github.io/ai-metrics-dashboard)**

---

## What It Does

Select a product dataset, review live charts, and generate an AI-written product narrative in seconds — the kind a senior PM would present in a weekly leadership standup or board update.

**Dashboard features:**
- **4 KPI cards** — primary metrics with period-over-period delta indicators
- **Revenue / growth line chart** — actual vs. target trajectory over 12 months
- **Retention cohort curves** — side-by-side cohort comparison to identify retention trends
- **Funnel conversion bar chart** — step-by-step drop-off visualization
- **Distribution doughnut** — revenue or user segment breakdown

**AI Narrative generates:**
- **Executive summary** — the most important story in the data, written for a leadership audience
- **Wins this period** — specific, number-backed performance highlights
- **Watch items** — risks and anomalies that need PM attention
- **Funnel insight** — what the conversion pattern reveals about the product
- **Retention signal** — what cohort health tells you about long-term growth
- **Recommended action** — one sharp, data-justified next step for the week

Output copies as clean Markdown for Notion, Confluence, or any PM tool.

---

## Datasets Included

| Dataset | Domain | Key Metrics |
|---|---|---|
| Ghost Kitchen Marketplace | Multi-sided Marketplace | GMV, partner retention, order funnel, platform split |
| Automotive SaaS (CarRX) | B2B SaaS / Mobile | MAU, repeat booking rate, enterprise partners, NPS |
| B2B SaaS Platform | B2B SaaS | ARR, activation rate, churn, expansion revenue |

Each dataset is modeled on real product scenarios from my experience leading product across marketplace and SaaS platforms.

---

## Why I Built This

PMs are drowning in dashboards but starving for narrative. The data exists — Heap, Segment, Mixpanel, Looker — but synthesizing it into a clear, opinionated story for leadership takes hours every week.

This tool bridges that gap. It doesn't just display metrics — it reasons about them. The AI is prompted to write like a PM who owns the numbers: specific, direct, and tied to a recommended action. Not a summary. A point of view.

The narrative format is modeled on the weekly product updates I wrote leading product at Kitchen United (Google Ventures, $100M Series C) and Connected Dealer Services — distilled into a repeatable, AI-augmented workflow.

Built as part of the **AI PM Toolkit** at [Motionova Labs](https://motionovalabs.com).

---

## Built With

- **Vanilla HTML / CSS / JavaScript** — zero dependencies beyond Chart.js
- **Chart.js 4.4** — revenue, retention, funnel, and distribution visualizations
- **Anthropic Claude API** (`claude-sonnet-4-20250514`) — product narrative generation
- **GitHub Pages** — zero-infrastructure deployment

---

## How to Run Locally

```bash
# Clone the repo
git clone https://github.com/eval4576/ai-metrics-dashboard.git

# Open directly in browser — no build step needed
open index.html
```

No backend, no environment variables, no build pipeline. The app calls the Anthropic API directly from the browser.

---

## The PM Thinking Behind the Metrics

The four chart types were chosen deliberately — each one answers a different strategic question:

| Chart | Question it answers |
|---|---|
| Revenue / Growth line | Are we on track? Where did we diverge from target and why? |
| Retention cohorts | Is the product getting better? Are newer cohorts retaining better than older ones? |
| Funnel conversion | Where are we losing users? What's the highest-leverage drop-off to fix? |
| Segment distribution | Is our revenue / user base healthy or dangerously concentrated? |

That's the same diagnostic framework I apply in discovery and roadmap planning — metrics should tell you where to look, not just what happened.

---

## Part of the AI PM Toolkit

This is **Project 2** in a series of AI tools built to demonstrate applied AI product management:

| # | Project | Status |
|---|---|---|
| 01 | AI Discovery Interview Analyzer | ✅ [Live](https://eval4576.github.io/ai-discovery-analyzer) |
| **02** | **AI Metrics Dashboard + Narrative** | **✅ Live** |
| 03 | AI PRD Generator | ✅ [Live](https://eval4576.github.io/ai-prd-generator) |
| 04 | Marketplace AI Opportunity Audit | 🔜 Coming soon |
| 05 | AI Onboarding Flow Analyzer | 🔜 Coming soon |
| 06 | Product Strategy Memo Series | 🔜 Coming soon |
| 07 | PM Agent Prototype (Capstone) | 🔜 Coming soon |

---

## About

Built by a Senior Product Manager with 8+ years across venture-backed marketplaces, platform APIs, and B2B SaaS — including Kitchen United (Google Ventures, $100M Series C) and Connected Dealer Services (CarRX).

**[Portfolio](https://motionovalabs.com) · [LinkedIn](https://www.linkedin.com/in/eddievaldivia/) · [GitHub](https://github.com/eval4576)**
