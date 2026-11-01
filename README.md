# Hi, I'm Chloe 👋

📍 **SF Bay Area, CA** | 🧭 **Principal PM** | 🚀 **Building full-cycle AI products**

![Product Management](https://img.shields.io/badge/-Product%20Management-0052CC?style=flat-square&logo=trello&logoColor=white)
![LLM Evaluation](https://img.shields.io/badge/-LLM%20Evaluation-412991?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/-RAG-FF6F00?style=flat-square&logo=databricks&logoColor=white)
![Recommendation Systems](https://img.shields.io/badge/-Recommendation%20Systems-009688?style=flat-square&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-000000?style=flat-square&logo=anthropic&logoColor=white)

> I turn human judgment into measurable product quality. After a decade shipping 0→1 and at-scale AI/ML products, I'm now building full-cycle AI tools end to end — from the underlying architecture to the practical apps people actually use.

<br>

---

## 💡 About Me

**Most recently Principal PM at Walmart** (Data & Ads Global Product Org), where I ran the human-in-the-loop evaluation program behind AI-driven products — designing eval frameworks, scorecards, and annotator operations that made models measurably better.

My background blends **Computer Science** and an **MBA** (Cornell University) — technical fluency paired with consulting-grade strategy. I care equally about the low-level architecture and the real-world application.

**What I work on**

- 🧪 **LLM & AI evaluation** — eval harnesses, scorecards, quality benchmarks, and human-in-the-loop pipelines
- 🧭 **Annotator operations at scale** — onboarding, calibration, and quality governance across global vendor teams
- 🎯 **Recommendation & personalization** — ranking, relevance, and retention-driving ML products
- 🛠️ **Full-cycle product building** — 0→1 prototypes through scaled launches, hands-on as both planner and builder
- 📊 **Quantitative impact** — every initiative tied to revenue, retention, quality, or efficiency

<br>

---

## 🗂️ Selected Work

I build to learn. Projects are grouped by capability, newest first within each group. Dates are when each was built (→ when it last got real work, not README edits).

**Status** — **Release**: installable app with a download · **Tested**: test suite running in CI · **Demo**: works end to end, no automated tests · **Concept**: a short build made to argue one product position

### Now building — the startup

| Project | When | Status | What it demonstrates |
|---|---|---|---|
| **[Throughline](https://github.com/chloe4ai/throughline)** · [live](https://chloe4ai.github.io/throughline/) | Sep → Oct 2026 | Tested | Documentation, billing and home-exercise adherence for outpatient PT (Physical Therapy) clinics, built toward a real product. One rule holds it together: the claim is derived from the note, never typed alongside it. Underneath is a tested billing engine — Medicare's 8-minute rule vs. the AMA (American Medical Association) rule of eights, MPPR (Multiple Procedure Payment Reduction), assistant modifiers and contract math — applied in the order that changes the dollars. |

<br>

### AI evaluation & measurement — the thesis

| Project | When | Status | What it demonstrates |
|---|---|---|---|
| **[Agent Ad Measurement Lab](https://github.com/chloe4ai/agent-ad-measurement-lab)** · [live](https://chloe4ai.github.io/agent-ad-measurement-lab/) | Oct 2026 | Demo | When an AI agent fetches a page with a sponsored block, the fetch proves only that the page was downloaded. This lab measures what actually reached the person — inclusion in the answer, whether the sponsorship label survived, whether the tracked link survived, and whether the traffic was a live user or a crawler. Billing on fetch overcounts by **3.8×**. Viewability, rebuilt for agents. |
| **[LLM Eval Scorecard](https://github.com/chloe4ai/llm-eval-scorecard)** · [live](https://chloe4ai.github.io/llm-eval-scorecard/) | Aug → Oct 2026 | Tested | Side-by-side human eval with the parts most scorecards skip: randomized pane order with a position-bias test, bootstrap confidence intervals on the score gap, Krippendorff's α and weighted κ across raters, and a sample-size readout. Answers *can you act on this yet?*, not just *who won?* |

<br>

### Ad tech, growth & marketplace — the day job, built out

| Project | When | Status | What it demonstrates |
|---|---|---|---|
| **[Notification Lab](https://github.com/chloe4ai/notification-lab)** · [live](https://chloe4ai.github.io/notification-lab/) | Oct 2026 | Tested | Push notifications as a retention channel, not a volume dial. A 180-day cohort simulation grid-searches 54 send policies across three personas and reports what a 30-day test cannot see: D90 retention and how many people can still be reached by push or email. Frequency capping, applied to notifications. |
| **[Ad Creative Optimizer](https://github.com/chloe4ai/ad-creative-optimizer)** · [live](https://ad-creative-optimizer.vercel.app) | Apr → Nov 2026 | Tested | Predicts creative fatigue across Google, Meta and TikTok with an exponential-decay model over each platform's feed, and alerts before the decay shows up in ROAS. Per-platform frequency caps, because a Meta impression and a TikTok impression are not the same unit of attention. |
| **[Offsite Ads Demo](https://github.com/chloe4ai/offsite-ads-demo)** · [live](https://chloe4ai.github.io/offsite-ads-demo/) | Apr → Oct 2026 | Demo | The off-site flow end to end — objective, budget, bid type, audience, multi-placement preview, 7-day KPIs — with Amazon DSP and Walmart Connect side by side. The $500 floor and the $10,000 floor select for different advertisers, and the whole build follows from that. |
| **[Mochi Market](https://github.com/chloe4ai/farmers-market-app)** · [live](https://farmers-market-app-six.vercel.app/) | Apr 2026 | Demo | Sales logging, inventory forecasting and dynamic pricing for vendors who either sell out or throw out. A small marketplace business, built end to end. |

<br>

### Recommendation & data-driven scouting

| Project | When | Status | What it demonstrates |
|---|---|---|---|
| **[Adaptation Radar](https://github.com/chloe4ai/adaptation-radar)** · [live](https://chloe4ai.github.io/adaptation-radar/) | Jul → Oct 2026 | Tested | Ranks books by screen-adaptation potential from four live public APIs, with every weight a slider so the model is something you argue with. A scheduled harvest records history, so the board shows the *slope*, not just the level. |
| **[StreamScope](https://github.com/chloe4ai/streamscope)** · [live](https://chloe4ai.github.io/streamscope/) | Apr → Sep 2026 | Tested | A cross-platform CTV recommendation engine that unifies viewing history across Netflix, HBO Max, Hulu, Disney+ and Prime. |

<br>

### Product prototypes — built to argue a position, not to look pretty

Each one picks a narrow problem and takes a position on it. The README in each explains the
problem, the positions it defends, and what it deliberately is *not*.

| Project | When | Status | What it demonstrates |
|---|---|---|---|
| **[Readwise Learning Loop](https://github.com/chloe4ai/readwise-learning-loop)** · [live](https://chloe4ai.github.io/readwise-learning-loop/) | Oct 2026 | Demo | What you learn in AI conversations should come back for review too. Imports a Claude or ChatGPT export and keeps the few sentences worth remembering, then reranks Daily Review by what you are working on this week — a relevance score, a spacing constraint and a diversity pass, the shape of an ad-ranking stack at small scale. |
| **[Glean Compass](https://github.com/chloe4ai/glean-compass-v2)** · [live](https://chloe4ai.github.io/glean-compass-v2/) | Jul 2026 | Concept | Priority drift, detected. Precision over recall on purpose: two flags, not forty, and dismissal is training data rather than a delete button. |
| **[Glean EI · full-stack](https://github.com/chloe4ai/glean-ei-fullstack)** · [live](https://chloe4ai.github.io/glean-ei-live/) | Jun 2026 | Demo | Proactive beats search — with a real Express backend, confidence genuinely recomputes server-side and agents stream over SSE. |
| **[Glean Delivery Intelligence](https://github.com/chloe4ai/glean-delivery-intelligence)** · [live](https://chloe4ai.github.io/glean-delivery-intelligence/) | Jun 2026 | Concept | Proactive beats search — but only if every pushed insight can show the weight and measured precision of the signals beneath it. |
| **[NerdWallet Money Next Steps](https://github.com/chloe4ai/nerdwallet-pm-prototype)** · [live](https://chloe4ai.github.io/nerdwallet-pm-prototype/) | Jun 2026 | Concept + Demo | Sequencing beats ranking: clear the 24% APR balance *before* the rewards card. Plus a [full-stack build](https://github.com/chloe4ai/nerdwallet-money-platform) on Next.js + Express + SQLite with a live funnel. |
| **[Stitch Fix Household](https://github.com/chloe4ai/stitchfix-household)** · [live](https://stitchfix-household.vercel.app) | Jun 2026 | Concept | Household is an account architecture, not a product category — cross-category browse, shared member profiles, and recommendations that learn across people. |
| **[Lyft Verticals](https://github.com/chloe4ai/lyft-verticals)** · [live](https://chloe4ai.github.io/lyft-verticals/) | Jun 2026 | Concept | Airports, scheduled rides and event egress are three marketplaces, not three filters on one — flight-aware pickup, price-lock, post-event demand staging. |
| **[Midi Health](https://github.com/chloe4ai/midi-health-prototype)** · [live](https://midi-health.vercel.app) | Jun 2026 | Concept | Five specific conversion changes to a telehealth funnel, each tied to the anxiety it removes. |

<br>

### Tools I built because I wanted them

| Project | When | Status | What it is |
|---|---|---|---|
| **[Email Finder](https://github.com/chloe4ai/email-finder)** | Oct 2026 | Release | Chrome extension that finds someone's work email from their LinkedIn profile in one click. A free, open-source take on Wiza / Apollo that runs entirely in the browser — no account, no server. |
| **[Sotto](https://github.com/chloe4ai/sotto)** | Jul → Oct 2026 | Release | Privacy-first on-device voice dictation for macOS and Windows, one hotkey per language. Speak softly, never type. |
| **[WeChat MCP Bridge](https://github.com/chloe4ai/wechat-mcp-bridge)** | Sep 2026 | Demo | Gives Claude read access to your own WeChat history on macOS after every single-tool solution broke — ~15 lines of glue between two surviving projects, plus the four permission gates that cost people an afternoon. |
| **[Meeting Scribe](https://github.com/chloe4ai/meeting-scribe)** | Aug 2026 | Release | Menu-bar app that notices a Zoom/Meet/Teams call has started and handles the notes — on-device, with consent treated as a product surface. |
| **[LinkedIn Schedule Send](https://github.com/chloe4ai/linkedin-schedule-send)** | Aug 2026 | Demo | The button LinkedIn should have shipped. |
| **[AI Trackers](https://github.com/chloe4ai/ai-trackers)** | Jun 2026 | Demo | Three scheduled trackers whose entire logic lives in natural-language `SKILL.md` files rather than code — an agent reads them, gathers live data, and delivers a bilingual digest. A bet on prompts-as-programs. |
| **[Notch](https://github.com/chloe4ai/notch)** | Jun 2026 | Demo | Local-first macOS work journal that traces your day into AI summaries. |

<br>

### Chinese history in code — creative side projects

Four ink-wash animatics from *Romance of the Three Kingdoms* (三國演義), every scene drawn procedurally in code with a synthesized score, each exporting a real `.webm` (no stock footage, no AI-generated imagery). Plus one original song, made with a local music model.

| Project | When | What it is |
|---|---|---|
| **[Three Visits 三顧茅廬](https://github.com/chloe4ai/three-visits)** · [live](https://chloe4ai.github.io/three-visits/) | Aug 2026 | The fourth film and the first with no battle: the same gate three times, the season turning behind it. |
| **[Six Expeditions 六出祁山](https://github.com/chloe4ai/qishan)** · [live](https://chloe4ai.github.io/qishan/) | Aug 2026 | Seven years, six campaigns, one returning shot — repetition as the subject. |
| **[Guandu 官渡](https://github.com/chloe4ai/guandu)** · [live](https://chloe4ai.github.io/guandu/) | Aug 2026 | A hundred-day daylight siege over a supply line, which needed a new visual language from scratch. |
| **[Red Cliffs 赤壁](https://github.com/chloe4ai/red-cliffs)** · [live](https://chloe4ai.github.io/red-cliffs/) | Jul 2026 | The first film: one night on a river, burning ships, public-domain Ming and Qing portraits for the faces. |
| **[天不再借](https://github.com/chloe4ai/tianbuzaijie)** · [live](https://chloe4ai.github.io/tianbuzaijie/) | Aug 2026 | An original song answering 《向天再借五百年》: lyrics and arrangement written by me, three vocal takes generated locally with ACE-Step, and lyric timing measured from the audio with Whisper plus dynamic-programming alignment. |

<br>

---

## 📈 Track Record

- **Walmart** — Principal PM, Data & Ads · lifted model response quality **42%** and helpfulness **38%** across 10,000+ enterprise users; scaled eval ops to **600+ annotators** across 4 vendor partners
- **iHerb** — Lead PM · improved recommendation precision **33%**, cut churn **22%**, raised inter-annotator agreement from 71% → **94%**
- **Wish** — Senior PM · boosted engagement **38%** and grew active users **147%** on the personalized recommendation engine
- **Amazon** — Senior PM · lifted forecast accuracy **24%** and cut stockouts **18%** across millions of SKUs

<br>

---

## 📊 GitHub Activity

[![GitHub Contribution Graph](https://ghchart.rshah.org/chloe4ai)](https://github.com/chloe4ai)

<br>

---

## 🌱 What I'm Focused On

- **Building a full-cycle AI product** — owning architecture and application end to end, starting with [Throughline](https://github.com/chloe4ai/throughline) for outpatient PT clinics
- **Open to Product Manager roles** — AI/ML, evaluation, personalization, and platform products
- **Sharing what I learn** — practical patterns for human-in-the-loop evaluation and AI product development

<br>

---

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/-in%2Fchloect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chloect/)
[![Email](https://img.shields.io/badge/-chloetan.cornell@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:chloetan.cornell@gmail.com)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/chloe4ai)

---

> *"Ship measurable quality."* — I build evaluation systems and AI products that turn human judgment into outcomes you can prove.
