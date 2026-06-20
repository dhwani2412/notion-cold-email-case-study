# 📧 Notion — Cold Email Outbound Case Study

> **Hypothetical campaign** — designed as a portfolio piece to demonstrate 
> end-to-end outbound strategy and execution.

---

## 🎯 The Scenario
Notion wants to acquire more B2B customers (teams & companies) 
through cold email outbound — specifically targeting Notion for Teams.

---

## 👤 Ideal Customer Profile (ICP)

| Field | Detail |
|---|---|
| **Job Title** | Operations Manager, Chief of Staff, Founder |
| **Company Size** | 20–200 employees |
| **Industry** | Tech startups, Marketing agencies, Consulting firms |
| **Pain Point** | Scattered docs, no single source of truth, messy tools |
| **Signal** | Actively hiring Chiefs of Staff or multiple Project Managers |

---

## 🔍 Lead List Building Strategy

- **Signal used:** Companies hiring Chiefs of Staff (indicates scaling + collaboration chaos)
- **Tools:** Apollo.io (filters: title + company size + industry) + Clay for enrichment
- **List size:** 45 highly targeted contacts (not a broad blast)
- **Validation:** Hunter.io / Prospeo to verify emails before sending
- **Target bounce rate:** Under 2%

---

## 🤖 AI Personalization Layer

Every email is personalized automatically using Clay + AI.
No two emails look the same. Here is how it works:

| Variable | Where It Comes From | Example Output |
|---|---|---|
| `{firstName}` | Apollo.io contact data | Priya |
| `{company}` | Apollo.io company data | Razorpay |
| `{hiring_signal}` | Job board scraping via Clay | hiring a Chief of Staff |
| `{recent_news}` | Clay AI browses company LinkedIn and news | just expanded to 3 new cities |
| `{pain_assumption}` | AI infers based on company stage | internal docs chaos during rapid growth |
| `{social_proof_match}` | Matched by industry via Clay | a fintech team of 20 people |

### Generic Email vs AI Personalized Email

❌ Generic (what most people send):
> Noticed {company} is hiring a Chief of Staff — thought Notion might help.

✅ AI Personalized (what this campaign sends):
> Noticed Razorpay is hiring a Chief of Staff AND just expanded to 3 new cities — that kind of growth usually means internal docs chaos comes next.

### How the AI personalization is built

- Clay pulls hiring signals from job boards automatically
- Clay AI (Claygent) browses each company LinkedIn page and recent news
- AI column writes a unique first line per prospect based on their data
- n8n pushes the enriched personalized list to Instantly for sending

---

## 📩 Email Sequence Strategy

Before writing a single email, I used 3 core principles:

**1. Problem Sniffing** — Find a specific pain they are already feeling

**2. Extremely Relevant Social Proof** — Show someone exactly like them already solved it

**3. Lead Magnet / Crafted Offer** — Give something valuable before asking for anything

---

### Email 1 — Cold Open (Problem Sniffing + Lead Magnet)

**Subject:** your team is scaling faster than your docs

**Framework:** PAS — Problem, Agitate, Solution

Hi {firstName},

Noticed {company} is hiring a Chief of Staff — usually means
the team is growing faster than current systems can handle.

Most teams at that stage end up with docs scattered across
Google Drive, tasks lost in Trello, updates buried in Slack.

No one knows what the latest version of anything is.

I put together a 5-step Notion workspace template for
agencies scaling past 20 people. Takes 10 minutes to set up.

Want me to send it over?

{signature}

---

### Follow-up 1 — Day 3 (Social Proof)

**Subject:** re: your team is scaling faster than your docs

**Framework:** Extremely Relevant Social Proof

Hey {firstName},

A {social_proof_match} (15 people, 3 client teams)
was dealing with the exact same chaos last month.

After setting up Notion — SOPs, client docs, and project
timelines all in one place — their onboarding time dropped 40%.

Happy to send you what their setup looks like?

{signature}

---

### Breakup Email — Day 7

**Subject:** should I stop reaching out?

Hey {firstName},

No worries if the timing isn't right.

Should I close the loop on my end?

{signature}

---

## 💡 Why This Sequence Works

| Principle | Where It Shows Up |
|---|---|
| **Problem Sniffing** | Email 1 — hiring signal = chaos signal |
| **Social Proof** | Follow-up 1 — real agency, real result |
| **Lead Magnet** | Email 1 CTA — template offer, zero commitment |
| **Low Friction CTA** | Every email ends with a yes/no question |
| **Breakup Email** | Day 7 — permission-based close, highest reply rate |

---

## 🛠️ Tools Used

| Function | Tool |
|---|---|
| Lead sourcing | Apollo.io |
| Enrichment & personalization | Clay |
| Email verification | Hunter.io |
| Sending & sequences | Instantly |
| Automation | n8n |

---

## 📊 Expected Metrics (based on 2026 benchmarks)

| Metric | Target |
|---|---|
| List size | 45 contacts |
| Expected reply rate | 5–7% |
| Bounce rate | Under 2% |
| Meetings booked (est.) | 2–3 |

---

## 👩‍💻 Built by
**Dhwani Kaushik** — Growth & Outbound Marketer  
[GitHub](https://github.com/dhwani2412)
