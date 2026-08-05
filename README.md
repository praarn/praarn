<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00C9A7&height=220&section=header&text=Prapti%20Nayak&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20%2B%20AI%20Systems%20Builder%20%E2%80%94%20Solo%2C%20End%20to%20End&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=900&color=00C9A7&center=true&vCenter=true&multiline=true&repeat=true&width=780&height=90&lines=I+don't+build+demos+%E2%80%94+I+build+systems+that+actually+run.;eBPF+kernels+%7C+multi-agent+pipelines+%7C+production+ML;India-first+design.+Deterministic+where+it+matters.;9.51+CGPA+%C2%B7+RIT+%C2%B7+Information+Science+%26+Engineering" alt="Typing SVG" />

<p>
<a href="https://linkedin.com/in/praptirnayak"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:praptinayak2005@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://prn-speaks.blogspot.com"><img src="https://img.shields.io/badge/Blog-FF5722?style=for-the-badge&logo=blogger&logoColor=white"/></a>
<a href="https://github.com/praarn"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<img src="https://komarev.com/ghpvc/?username=praarn&style=for-the-badge&color=00C9A7&label=PROFILE+VIEWS" />

</div>

<br/>

## `whoami`

```yaml
name: Prapti Nayak
role: Full-stack developer — backend, frontend, ML, and infra, owned end to end
education: B.E. Information Science & Engineering, Ramaiah Institute of Technology (CGPA 9.51/10)
focus: AI observability · LLM orchestration · developer tooling · India-localized systems
philosophy:
  - "Deterministic logic where correctness matters; LLMs where judgment does — never the reverse."
  - "Every audited project has a documented list of bugs I found and fixed, not just what shipped clean."
  - "If it can't run against a real cloud account / real dataset / real API, it's a mockup, not a project."
currently: exploring AI observability, LLM routing, and dev tooling as underexplored startup spaces
```

<br/>

## Featured Builds

Each project below ships a full stack — not just a model in a notebook. Expand any card for the real architecture.

<br/>

<details open>
<summary><b>🛡️ Autonomous Cyber Defense System (ACDS)</b> — real-time intrusion detection, kernel to dashboard in under 5 seconds</summary>
<br/>

A 7-layer autonomous defense pipeline: **eBPF kernel probes** for syscall-level telemetry, deep packet inspection on encrypted traffic *without decrypting it*, a **4-model ML ensemble** (XGBoost, Random Forest, Autoencoder, Isolation Forest), an on-device LLM (Llama 3.2) that turns raw detections into MITRE ATT&CK-mapped explanations, and a Neo4j attack-graph engine with risk propagation — all streamed live to a React dashboard over Kafka/WebSockets.

- **99.16% accuracy · 0.9995 AUC-ROC** across 1.1M+ samples
- Built to solve real SOC pain: signature-based IDS misses zero-days and encrypted C2 traffic, and analysts drown in >90% false-positive rates
- Every alert is fully attributed: ML-scored, LLM-explained, and graphed in attack-path context

`Python` `XGBoost` `PyTorch` `eBPF` `Kafka` `Neo4j` `FastAPI` `React`
</details>

<details>
<summary><b>🌍 Sentinel</b> — AI disaster prediction & response system, built India-first</summary>
<br/>

A full-stack disaster intelligence platform running on **live USGS seismic and weather data**: an ML risk-prediction engine, an NLP layer reading social media for panic signals, a per-user **Individual Vulnerability Score**, graph-based evacuation-route optimization (NetworkX), satellite hotspot analysis, a shelter/resource allocation optimizer, and a responder AI copilot — with multi-channel real-time alert dispatch over WebSockets and offline PWA support for low-connectivity disaster zones.

`FastAPI` `Next.js` `NetworkX` `HuggingFace` `WebSockets`
</details>

<details>
<summary><b>☁️ CloudOps Enterprise Platform</b> — a dashboard backed by real, deployable infrastructure</summary>
<br/>

Two layers that work together: a live operations console visualizing services, network topology, security posture, and ML models — and **real Terraform/Docker/Kubernetes IaC** that a user can run against an actual AWS account to produce the infrastructure the console visualizes, including a genuinely working SageMaker fraud-detection endpoint and CI/CD in GitHub Actions and Jenkins. Runs standalone as a demo, or for real against live cloud.

`Terraform` `Docker` `Kubernetes` `AWS SageMaker` `Node.js`
</details>

<details>
<summary><b>📰 Verafide</b> — fake news detection, and the 95%→86% accuracy gap I found and fixed</summary>
<br/>

A locally-trained ML classifier layered with LLM-reasoned verdicts (Groq), OCR-capable document/batch ingestion, and an AI summarizer chatbot, presented through a custom "verification desk" editorial UI. Trained on a 13,343-row balanced dataset across 13 topic buckets — and shipped with a diagnosed root cause for an accuracy drop from a benchmark-looking 95% down to a real-world 86%, traced to narrow-dataset overfitting and corrected rather than hidden.

`FastAPI` `SQLAlchemy` `React` `Groq` `OCR`
</details>

<details>
<summary><b>🧭 Saral</b> — bureaucracy simplifier, a genuine polyglot microservice system</summary>
<br/>

Four independent services — frontend, API gateway, a Python AI service, and a background worker — talking over HTTP and a shared Postgres/Redis backend, built on one rule: **the fast path never blocks on the slow path.** Document upload returns instantly; extraction, OCR, and LLM reasoning run asynchronously on a durable BullMQ queue that survives crashes. The AI service only trusts requests carrying an internal shared token, so an accidental port exposure still isn't an open door.

`Node.js` `Python` `BullMQ` `Postgres` `Redis`
</details>

<details>
<summary><b>🔬 Research Assistant Crew</b> — five LLM agents, every claim gets a confidence stamp</summary>
<br/>

A question goes in; five specialized agents — planner, searcher, summarizer, fact-checker, writer — collaborate to produce a sourced report where every claim in the prose carries a visible, hoverable verdict: Verified, Plausible, Unverified, or Contradicted. Built entirely on free-tier infrastructure (Groq LLM, DuckDuckGo search, no paid API), and designed to degrade gracefully rather than crash when the free tier gets rate-limited.

`FastAPI` `React` `Groq` `DuckDuckGo Search`
</details>

<details>
<summary><b>📊 Data Pipeline Orchestrator</b> — five agents, zero silent transformations</summary>
<br/>

Ingest → Clean → Analyze → Visualize → Report, as five stateless agents behind a REST API and a deliberately zero-build vanilla JS frontend. Cleaning proposes a dry-run diff; nothing touches the data until a human approves it. Every statistical finding is backed by a real `scipy` test — t-test, ANOVA, Pearson, regression — never a heuristic dressed up as significance.

`Flask` `pandas` `scipy` `Vanilla JS`
</details>

<details>
<summary><b>📚 clutchExams</b> — an academic resource platform, on its third real rebuild</summary>
<br/>

A folder-tree academic resource browser — notes, papers, slides — with recursive global search, open browsing/download with no forced signup, and a single audited admin account (JWT + bcrypt) for uploads and management. Rebuilt twice: from a shared-token prototype to a real per-account auth system with a full login audit trail, without ever touching the neo-brutalist frontend identity that made v1 worth keeping.

`Node.js` `Express` `React` `JWT` `Tailwind`
</details>

<details>
<summary><b>📈 Skill Gap Mapper</b> — career-intelligence, audited post-build for real production bugs</summary>
<br/>

Resume-to-role fit scored by a deterministic, weighted algorithm — 50% skill coverage, 30% experience relevance, 20% project quality — layered with live job-market data, ATS compatibility checks, and resume optimization suggestions. Shipped with a documented post-launch audit that caught and fixed 7 real issues, rather than a README that pretends the first build was clean.

`FastAPI` `Next.js` `TypeScript` `Groq`
</details>

<details>
<summary><b>🏥 Healthcare Cost Predictor</b> — every number is traceable, none of them come from an LLM</summary>
<br/>

An India medical-cost estimator with government health-scheme eligibility checks and empanelled-hospital surfacing. The one non-negotiable design rule: no cost figure or eligibility result is ever generated by an LLM — every number traces back to a structured JSON data source, and every approximation is explicitly labeled as one instead of being silently substituted.

`FastAPI` `Pydantic` `Next.js` `TypeScript`
</details>

<details>
<summary><b>⚖️ Public Grievance Analyzer</b> — governance intelligence a government official could actually defend</summary>
<br/>

Clusters public complaints via HDBSCAN embeddings, ranks severity, and routes each cluster to the responsible authority. Classification is deliberately deterministic and auditable — LLM usage is scoped only to summarization — because a government user needs to be able to defend a system-assisted decision, not just trust a black box.

`FastAPI` `PostgreSQL` `pgvector` `HDBSCAN`
</details>

<details>
<summary><b>💰 Ledger</b> — a personal finance advisor that still runs if the LLM doesn't</summary>
<br/>

A multi-agent finance system — budgeting, debt, tax, and retirement agents — where every calculation is 100% deterministic and independent of LLM availability, including an employer-match-gap analyzer built on real marginal tax-bracket data. The LLM explains; it never computes.

`FastAPI` `React` `Groq` `SQLite`
</details>

<details>
<summary><b>📖 Shelfwise</b> — a book platform that deliberately stayed dependency-light</summary>
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

<img height="165" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=praarn&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
<img height="165" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=praarn&layout=compact&theme=tokyonight&hide_border=true"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=praarn&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=praarn&theme=tokyo-night&hide_border=true" width="98%"/>

</div>

> **Note on the stats widgets:** the primary `github-readme-stats.vercel.app` endpoint is frequently overloaded — a long-running, widely reported issue on that project, not specific to this profile. The mirror above (rickstaa's fork) is the most reliable public alternative. If any widget shows a broken-image icon: hard-refresh (GitHub caches these aggressively), wait a few minutes, or fork [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats) and deploy your own instance to Vercel (free, ~2 minutes) and point the URL at that instead.

<br/>

## Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/praarn/praarn/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

> This animation renders itself from your real contribution graph — it needs a one-time GitHub Actions setup (using [Platane/snk](https://github.com/Platane/snk)) that commits the SVG to an `output` branch on a schedule. Steps:
> 1. In your `praarn/praarn` repo, add `.github/workflows/snake.yml` using the Platane/snk action (points at branch `output`).
> 2. Push once — the Action generates the SVG automatically on schedule.
> The `<img>` tag above is already wired to the resulting file, so once the workflow runs, the animation appears with no further edits needed.

<br/>

## Certifications

<div align="center">

<img src="https://img.shields.io/badge/NPTEL-Artificial%20Intelligence-2C5364?style=for-the-badge"/>
<img src="https://img.shields.io/badge/NPTEL-Machine%20Learning-2C5364?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Snowflake-Python%20%26%20SQL-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white"/>

</div>

<br/>

<div align="center">

### Open to full-stack, AI, and platform engineering roles.

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3500&pause=1200&color=8A8A8A&center=true&vCenter=true&width=600&lines=Reach+out+via+LinkedIn+or+email+above+%E2%80%94+I+reply.;Currently+shipping+in+AI+observability+%26+LLM+routing." />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,50:2C5364,100:0F2027&height=120&section=footer" width="100%"/>

</div>
