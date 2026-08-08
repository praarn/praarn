<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00C9A7&height=220&section=header&text=Prapti%20Nayak&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20%2B%20AI%20Systems%20Builder%20%E2%80%94%20Solo%2C%20End%20to%20End&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=900&color=00C9A7&center=true&vCenter=true&multiline=true&repeat=true&width=780&height=90&lines=I+don't+build+demos+%E2%80%94+I+build+systems+that+actually+run.;eBPF+kernels+%7C+multi-agent+pipelines+%7C+production+ML;India-first+design.+Deterministic+where+it+matters.;9.51+CGPA+%C2%B7+RIT+%C2%B7+Information+Science+%26+Engineering" alt="Typing SVG" />

<p>
<a href="https://linkedin.com/in/praptirnayak"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:praptinayak2005@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://prn-speaks.blogspot.com"><img src="https://img.shields.io/badge/Blog-FF5722?style=for-the-badge&logo=blogger&logoColor=white"/></a>
<a href="https://github.com/praarn"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://leetcode.com/u/praarn/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white"/></a>
<a href="https://www.notion.so/0b156230180745709db431ff8d7cc8b9"><img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"/></a>
<a href="https://www.canva.com/projects"><img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white"/></a>
</p>

<img src="https://komarev.com/ghpvc/?username=praarn&style=for-the-badge&color=00C9A7&label=PROFILE+VIEWS" />

</div>

<br/>

## `whoami`

```yaml
name: Prapti Ramachandra Nayak
location: Bengaluru, India
role: Full-stack developer — backend, frontend, ML, and infra, owned end to end
education: B.E. Information Science & Engineering, Ramaiah Institute of Technology (CGPA 9.51/10)
focus: AI observability · LLM orchestration · developer tooling · India-localized civic-tech
domains: disaster response · legal aid · healthcare access · public grievance redressal · personal finance
philosophy:
  - "Deterministic logic where correctness matters; LLMs where judgment does — never the reverse."
  - "Every audited project has a documented list of bugs I found and fixed, not just what shipped clean."
  - "If it can't run against a real cloud account / real dataset / real API, it's a mockup, not a project."
currently: exploring AI observability, LLM routing, and dev tooling as underexplored startup spaces
outside_of_engineering: reading books, writing poetry and prose
```

<br/>

## Experience

| Role | Organization | Duration |
|---|---|---|
| Project Intern | Pinnacle Labs (Remote) | Jul 2026 – Present |
| Project Intern — built the Sentinel backend (FastAPI, WebSockets, JWT auth) + React/Vite frontend | Navodita Infotech (Remote) | Apr 2026 – May 2026 |
| Content Writing Intern — wrote on social issues, supported fundraising outreach | InAmigos Foundation (Remote) | Mar 2026 – Apr 2026 |

<br/>

## Featured Builds

Each project below ships a full stack — not just a model in a notebook. Expand any card for the real architecture.

<br/>

<details open>
<summary><a href="https://github.com/praarn/ACDS"><b>🛡️ Autonomous Cyber Defense System (ACDS)</b></a> — real-time intrusion detection, kernel to dashboard in under 5 seconds</summary>
<br/>

A 7-layer autonomous defense pipeline: **eBPF kernel probes** for syscall-level telemetry, deep packet inspection on encrypted traffic *without decrypting it*, a **4-model ML ensemble** (XGBoost, Random Forest, Autoencoder, Isolation Forest), an on-device LLM (Llama 3.2) that turns raw detections into MITRE ATT&CK-mapped explanations, and a Neo4j attack-graph engine with risk propagation — all streamed live to a React dashboard over Kafka/WebSockets.

- **99.16% accuracy · 0.9995 AUC-ROC** across 1.1M+ samples
- Built to solve real SOC pain: signature-based IDS misses zero-days and encrypted C2 traffic, and analysts drown in >90% false-positive rates
- Every alert is fully attributed: ML-scored, LLM-explained, and graphed in attack-path context

`Python` `XGBoost` `PyTorch` `eBPF` `Kafka` `Neo4j` `FastAPI` `React`
</details>

<details>
<summary><a href="https://github.com/praarn/disasterResponseSystem"><b>🌍 Sentinel</b></a> — AI disaster prediction & response system, built India-first</summary>
<br/>

A full-stack disaster intelligence platform running on **live USGS seismic and weather data**: an ML risk-prediction engine, an NLP layer reading social media for panic signals, a per-user **Individual Vulnerability Score**, graph-based evacuation-route optimization (NetworkX), satellite hotspot analysis, a shelter/resource allocation optimizer, and a responder AI copilot — with multi-channel real-time alert dispatch over WebSockets and offline PWA support for low-connectivity disaster zones.

`FastAPI` `Next.js` `NetworkX` `HuggingFace` `WebSockets`
</details>

<details>
<summary><a href="https://github.com/praarn/cloudOpsFunctional"><b>☁️ CloudOps Enterprise Platform</b></a> — a dashboard backed by real, deployable infrastructure</summary>
<br/>

Two layers that work together: a live operations console visualizing services, network topology, security posture, and ML models — and **real Terraform/Docker/Kubernetes IaC** that a user can run against an actual AWS account to produce the infrastructure the console visualizes, including a genuinely working SageMaker fraud-detection endpoint and CI/CD in GitHub Actions and Jenkins. Runs standalone as a demo, or for real against live cloud.

`Terraform` `Docker` `Kubernetes` `AWS SageMaker` `Node.js`
</details>

<details>
<summary><a href="https://github.com/praarn/verafideFakeNewsDetector"><b>📰 Verafide</b></a> — fake news detection, and the 95%→86% accuracy gap I found and fixed</summary>
<br/>

A locally-trained ML classifier layered with LLM-reasoned verdicts (Groq), OCR-capable document/batch ingestion, and an AI summarizer chatbot, presented through a custom "verification desk" editorial UI. Trained on a 13,343-row balanced dataset across 13 topic buckets — and shipped with a diagnosed root cause for an accuracy drop from a benchmark-looking 95% down to a real-world 86%, traced to narrow-dataset overfitting and corrected rather than hidden.

`FastAPI` `SQLAlchemy` `React` `Groq` `OCR`
</details>

<details>
<summary><a href="https://github.com/praarn/bureaucracySimplifier"><b>🧭 Saral</b></a> — bureaucracy simplifier, a genuine polyglot microservice system</summary>
<br/>

Four independent services — frontend, API gateway, a Python AI service, and a background worker — talking over HTTP and a shared Postgres/Redis backend, built on one rule: **the fast path never blocks on the slow path.** Document upload returns instantly; extraction, OCR, and LLM reasoning run asynchronously on a durable BullMQ queue that survives crashes. The AI service only trusts requests carrying an internal shared token, so an accidental port exposure still isn't an open door.

`Node.js` `Python` `BullMQ` `Postgres` `Redis`
</details>

<details>
<summary><a href="https://github.com/praarn/legalAdvisor"><b>⚖️ NyaySetu — AI Legal Navigator</b></a> — rights and next steps, cited to the actual Act and Section</summary>
<br/>

A multilingual (13 Indian languages) legal-guidance platform: describe a legal problem in plain language and get back your **rights** — each tied to a named Act and Section, never a vague generalisation — concrete next steps, a procedural timeline, a ready-to-fill document (complaint letter, legal notice, FIR draft), and a follow-up chat scoped to the situation. Six domains are covered (consumer, tenancy, employment, family, criminal, cyber), each backed by a transparent, inspectable keyword-scoring intent classifier instead of a black-box model — so a "why was I routed here" question always has a real answer.

- **Urgency detection** flags situations implying immediate danger and surfaces emergency contacts (NALSA, Police, Women's/Child helplines) ahead of regular guidance
- Auto-generates fillable legal documents with live preview and client-side PDF export
- Deliberately backend-free — intent classification, document generation, and session state all run client-side or via a single serverless route — with the Groq-backed chat degrading gracefully to an offline rule-based engine when unconfigured

`Next.js 16` `TypeScript` `Tailwind CSS v4` `Groq`
</details>

<details>
<summary><a href="https://github.com/praarn/researchAssitantCrewAgentic"><b>🔬 Research Assistant Crew</b></a> — five LLM agents, every claim gets a confidence stamp</summary>
<br/>

A question goes in; five specialized agents — planner, searcher, summarizer, fact-checker, writer — collaborate to produce a sourced report where every claim in the prose carries a visible, hoverable verdict: Verified, Plausible, Unverified, or Contradicted. Built entirely on free-tier infrastructure (Groq LLM, DuckDuckGo search, no paid API), and designed to degrade gracefully rather than crash when the free tier gets rate-limited.

`FastAPI` `React` `Groq` `DuckDuckGo Search`
</details>

<details>
<summary><a href="https://github.com/praarn/dataPipelineOrchestratorAgentic"><b>📊 Data Pipeline Orchestrator</b></a> — five agents, zero silent transformations</summary>
<br/>

Ingest → Clean → Analyze → Visualize → Report, as five stateless agents behind a REST API and a deliberately zero-build vanilla JS frontend. Cleaning proposes a dry-run diff; nothing touches the data until a human approves it. Every statistical finding is backed by a real `scipy` test — t-test, ANOVA, Pearson, regression — never a heuristic dressed up as significance.

`Flask` `pandas` `scipy` `Vanilla JS`
</details>

<details>
<summary><a href="https://github.com/praarn/academicBuddy"><b>📚 clutchExams</b></a> — an academic resource platform, on its third real rebuild</summary>
<br/>

A folder-tree academic resource browser — notes, papers, slides — with recursive global search, open browsing/download with no forced signup, and a single audited admin account (JWT + bcrypt) for uploads and management. Rebuilt twice: from a shared-token prototype to a real per-account auth system with a full login audit trail, without ever touching the neo-brutalist frontend identity that made v1 worth keeping.

`Node.js` `Express` `React` `JWT` `Tailwind`
</details>

<details>
<summary><a href="https://github.com/praarn/skillGapMapper"><b>📈 Skill Gap Mapper</b></a> — career-intelligence, audited post-build for real production bugs</summary>
<br/>

Resume-to-role fit scored by a deterministic, weighted algorithm — 50% skill coverage, 30% experience relevance, 20% project quality — layered with live job-market data, ATS compatibility checks, and resume optimization suggestions. Shipped with a documented post-launch audit that caught and fixed 7 real issues, rather than a README that pretends the first build was clean.

`FastAPI` `Next.js` `TypeScript` `Groq`
</details>

<details>
<summary><a href="https://github.com/praarn/healthAssistant"><b>🏥 Healthcare Cost Predictor</b></a> — every number is traceable, none of them come from an LLM</summary>
<br/>

An India medical-cost estimator with government health-scheme eligibility checks and empanelled-hospital surfacing. The one non-negotiable design rule: no cost figure or eligibility result is ever generated by an LLM — every number traces back to a structured JSON data source, and every approximation is explicitly labeled as one instead of being silently substituted.

`FastAPI` `Pydantic` `Next.js` `TypeScript`
</details>

<details>
<summary><a href="https://github.com/praarn/publicGrievanceIntelligence"><b>⚖️ Public Grievance Analyzer</b></a> — governance intelligence a government official could actually defend</summary>
<br/>

Clusters public complaints via HDBSCAN embeddings, ranks severity, and routes each cluster to the responsible authority. Classification is deliberately deterministic and auditable — LLM usage is scoped only to summarization — because a government user needs to be able to defend a system-assisted decision, not just trust a black box.

`FastAPI` `PostgreSQL` `pgvector` `HDBSCAN`
</details>

<details>
<summary><a href="https://github.com/praarn/financeLedgerAgentic"><b>💰 Ledger</b></a> — a personal finance advisor that still runs if the LLM doesn't</summary>
<br/>

A multi-agent finance system — budgeting, debt, tax, and retirement agents — where every calculation is 100% deterministic and independent of LLM availability, including an employer-match-gap analyzer built on real marginal tax-bracket data. The LLM explains; it never computes.

`FastAPI` `React` `Groq` `SQLite`
</details>

<details>
<summary><a href="https://github.com/praarn/shelfWiseOnlineLibrary"><b>📖 Shelfwise</b></a> — a book platform that deliberately stayed dependency-light</summary>
<br/>

Merges Open Library and Project Gutenberg into a single catalog with content-based recommendations, reading-level scoring, and reading-streak tracking — built as a single deployable Next.js app on purpose, trading a heavier stack for something that's actually simple to run and reason about.

`Next.js` `TypeScript` `SQLite`
</details>

<br/>

## Language & Tool Fluency

<div align="center">
<img src="https://skillicons.dev/icons?i=python,java,ts,js,cpp,react,nextjs,tailwind,fastapi,flask,nodejs,pytorch,sklearn,huggingface,postgres,mysql,sqlite,neo4j,mongodb,docker,kubernetes,terraform,aws,kafka,git,github,vscode&theme=dark&perline=9" />
</div>

<br/>

## GitHub, by the Numbers

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=praarn&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=praarn&layout=compact&theme=tokyonight&hide_border=true"/>

<img src="https://streak-stats.demolab.com/?user=praarn&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=praarn&theme=tokyo-night&hide_border=true" width="98%"/>

</div>

> **Note on the stats widgets:** these are free, community-run services (not GitHub's own), so any one can occasionally show a broken-image icon under load. `github-readme-stats.vercel.app` and `streak-stats.demolab.com` are the actively maintained official domains — the streak widget previously pointed at `.herokuapp.com`, which Heroku retired its free tier on, which is why it may have rendered oddly. If a widget still doesn't load: hard-refresh (GitHub caches these aggressively), wait a few minutes, or fork [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) / [DenverCoder1/github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) and deploy your own instance to Vercel (free, ~2 minutes), then point the URL above at that instead.

<br/>

## Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/praarn/praarn/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

> **Why it's not loading yet:** this isn't a broken link — it's expected until the one-time GitHub Actions setup below is done. The image points at a file (`output/github-contribution-grid-snake-dark.svg`) that doesn't exist in your `praarn/praarn` repo until an Action generates and commits it, so right now the URL 404s.
>
> **Setup (one time, ~2 minutes):**
> 1. In your `praarn/praarn` repo on GitHub, create a new file at `.github/workflows/snake.yml` and paste in:
> ```yaml
> name: generate snake
> on:
>   schedule:
>     - cron: "0 0 * * *"   # once a day
>   workflow_dispatch: {}
>   push:
>     branches: [ main ]
> jobs:
>   generate:
>     runs-on: ubuntu-latest
>     steps:
>       - uses: Platane/snk@v3
>         with:
>           github_user_name: praarn
>           outputs: |
>             dist/github-contribution-grid-snake.svg
>             dist/github-contribution-grid-snake-dark.svg?palette=github-dark
>       - uses: crazy-max/ghaction-github-pages@v4
>         with:
>           target_branch: output
>           build_dir: dist
>         env:
>           GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
> ```
> 2. Commit it, then go to the **Actions** tab and either wait for the scheduled run or click **Run workflow** to trigger it immediately.
> 3. Once it finishes, it pushes the SVG to a new `output` branch — the `<img>` tag above is already pointed at that file, so the animation just appears. No further README edits needed.

<br/>

## Certifications

<div align="center">

<img src="https://img.shields.io/badge/NPTEL-Artificial%20Intelligence-2C5364?style=for-the-badge"/>
<img src="https://img.shields.io/badge/NPTEL-Machine%20Learning-2C5364?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Snowflake-SnowPro%20Associate%20Platform-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white"/>
<img src="https://img.shields.io/badge/Cloudthat-Generative%20AI%20with%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Skill%20Nation-Generative%20AI%20Tools-2C5364?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Free%20Academy.ai-Claude%20Code%20AI%20Powered%20Coding-D97757?style=for-the-badge"/>

</div>

<br/>

<div align="center">

### Open to full-stack, AI, and platform engineering roles.

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3500&pause=1200&color=8A8A8A&center=true&vCenter=true&width=600&lines=Reach+out+via+LinkedIn+or+email+above+%E2%80%94+I+reply.;Currently+shipping+in+AI+observability+%26+LLM+routing." />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,50:2C5364,100:0F2027&height=120&section=footer" width="100%"/>

</div>
